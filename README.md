Download Link: https://assignmentchef.com/product/solved-cop3330-object-oriented-programmingeuchre-project-part-2
<br>
<strong>Assignment Scope</strong>

<ol>

 <li>Add methods to classes to accomplish specific tasks</li>

 <li>Use class HashSet</li>

 <li>Convert a HashSet to an ArrayList</li>

 <li>Convert an ArrayList to a HashSet</li>

 <li>Iterate through a HashSet</li>

 <li>Generate objects of specific classes</li>

 <li>Compile and run a project</li>

 <li>Compress a project and submit to Webcourses</li>

 <li>Decompress compressed project and verify it is a Netbeans project</li>

</ol>




<strong>References</strong>

<ol>

 <li>docx</li>

 <li>Setting up a project in Netbeans.docx</li>

 <li>Netbeans right click menu help.docx</li>

</ol>

<strong> </strong>

<strong>Deliverables</strong>

To complete this assignment you must submit your <strong>compressed Netbeans project </strong>to Webcourses.

<strong> </strong>

<strong>Tasks</strong>

<table width="667">

 <tbody>

  <tr>

   <td colspan="2" width="667"><strong>Activity</strong></td>

  </tr>

  <tr>

   <td width="181"><strong>Euchre project</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>Euchre class</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>constants</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>Constants class</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>core package</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>AiPlayer class</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>Card class</strong></td>

   <td width="486">Update class to include:1.      Method hashCode, it shalla.       Return type intb.      Receive no parametersc.       Include local variable hashCode of data type int initialized to the value of zerod.      Concatenate member variable face and its hashcodee.       Concatenate member variable value and its hashcodef.        Concatenate member variable color and its hashcodeg.      Return the local variable hashCode2.      Method equals, it shalla.       Return type booleanb.      Receive one parameter of data type Objectc.       Check if the parameter is an instanceof class Cardi.      If true1.      Explicitly convert the parameter to an instance of class Card2.      Return the result of comparing if the face, suit, and color match an existing object3.      Code example:return (card.face.equals(this.face) &amp;&amp;card.color.equals(this.color) &amp;&amp;card.suit.equals(this.suit));ii.      Else1.      Return false </td>

  </tr>

  <tr>

   <td width="181"><strong>Deck class</strong></td>

   <td width="486">Update class to1.      Write a custom constructor thata.       Receives no parametersb.      Calls method generateDeck()c.       Calls method displayDeck()d.      Calls method shuffleDeck()e.       Calls method displayDeck()2.      Write method generateDeck so thata.       Return type is voidb.      Receives no parametersc.       Instantiates the member variable of type Set calling the constructor for class HashSetd.      Loops through the values of enumeration Facei.      Loops through the values of enumeration Suit1.      Instantiates an instance of class Card2.      Sets the face value of the card3.      Sets the suit of the card4.      Determines the color of the card based on the suit and sets the color of the card5.      Verifies the instance of Card created is not contained in the HashSet of cardsa.       If it does not exist, add the instance of class Card to the HashSet3.      Write method displayDeck so thata.       Return type is voidb.      Receives no parametersc.       Iterates through the HashSet collection outputting to the console the face value, suit, and color of each card4.      Write method shuffleDeck so thata.       Instantiates an instance of class ArrayList, explicitly for data type of class Card passing the member variable of interface Set as an argumentb.      Call static method Collections.shuffle passing the ArrayList from above as an argumentc.       Reinstantiate the member variable of interface Set by calling the constructor for class HashSet passing the ArrayList above as an argument </td>

  </tr>

  <tr>

   <td width="181"><strong>Game class</strong></td>

   <td width="486">Update class to1.      Update the custom constructor to call method generateDeck()2.      Add method generateDeck so thata.       Return type is voidb.      Receives no parametersc.       Instantiates the member variable of class Deckb.</td>

  </tr>

  <tr>

   <td width="181"><strong>HumanPlayer class</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>IPlayer interface</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>Player class</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>Team class</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>userinterface package</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>Euchre application</strong></td>

   <td width="486"> </td>

  </tr>

  <tr>

   <td width="181"><strong>Test Case 1</strong></td>

   <td width="486">Test Case 1 passes</td>

  </tr>

  <tr>

   <td width="181"><strong>Test Case 2</strong></td>

   <td width="486">Test Case 2 passes</td>

  </tr>

  <tr>

   <td width="181"><strong>Test Case 3</strong></td>

   <td width="486">Test Case 3 passes</td>

  </tr>

  <tr>

   <td width="181"><strong>Test Case 4</strong></td>

   <td width="486">Test Case 4 passes</td>

  </tr>

  <tr>

   <td width="181"><strong>Test Case 5</strong></td>

   <td width="486">Test Case 5 passes</td>

  </tr>

  <tr>

   <td width="181"><strong> </strong></td>

   <td width="486">Source compiles with no errors</td>

  </tr>

  <tr>

   <td width="181"><strong> </strong></td>

   <td width="486">Source runs with no errors</td>

  </tr>

  <tr>

   <td width="181"><strong> </strong></td>

   <td width="486">Source includes comments</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Perform the following test cases</strong>

<table>

 <tbody>

  <tr>

   <td colspan="3" width="638"><strong>Test Cases</strong></td>

  </tr>

  <tr>

   <td width="166"><strong> </strong></td>

   <td width="166"><strong>Action</strong></td>

   <td width="307"><strong>Expected outcome</strong></td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 1</strong></td>

   <td width="166"><strong>Project view</strong></td>

   <td width="307">Completed project view should look like figure 1</td>

  </tr>

  <tr>

   <td width="166"><strong>Test case 2</strong></td>

   <td width="166"><strong>Regression testing; Run application</strong></td>

   <td width="307">The console window should look like figure 2</td>

  </tr>

  <tr>

   <td width="166"><strong>Test case 3</strong></td>

   <td width="166"><strong>Regression testing; Run application </strong></td>

   <td width="307">The JOptionPane.showMessageDialog() method call should look like figure 3</td>

  </tr>

  <tr>

   <td width="166"><strong>Test case 4</strong></td>

   <td width="166"><strong>Run application</strong></td>

   <td width="307">The console window should look similar to figure 4 for the initial display of the deck of cards</td>

  </tr>

  <tr>

   <td width="166"><strong>Test case 5</strong></td>

   <td width="166"><strong>Run application</strong></td>

   <td width="307">The output in the console window should display the deck of cards after being shuffled and should NOT be in the same order as the first output, similar to figure 5</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

Figure 1 Project View




Figure 2 Output in console window




Figure 3 Display from JOptionPane.showMessageDialog() method




Figure 4 Initial display of deck of cards




Figure 5 Display of deck of cards after shuffle