Download Link: https://assignmentchef.com/product/solved-csis-3280-lab-5-original
<br>



Visual Studio Code

<ol>

 <li>Download the lab template from Blackboard</li>

 <li>Extract it</li>

 <li>Fill in the relevant code to create the solution and meet the requirements Solution</li>

</ol>

The flow of the program is as follows:

<ol>

 <li>The user will be prompted to upload a CSV file. When the file is uploaded the roster will be displayed with the players sorted by player number and a count at the bottom, please see the appendix. Requirements:</li>

 <li>By default, the app will sort the team members by last name.</li>

 <li>The team will display a total of the number of player objects it contains when printed</li>

 <li>The CSV file will be parsed into Player objects</li>

 <li>The player objects will all be added to a team</li>

 <li>The HTML form will prompt the user to upload a CSV file (you will use data/orioles.csv)</li>

 <li>Your code must only be using classes (except for the controller file)</li>

 <li>You must use a try/catch clause any time you are the data file 9. You must close your file handle when you are finished with the file.</li>

 <li>You must not leave any errors on the page.</li>

</ol>

<h1>Files and Template</h1>

The following classes and respective files are required for this lab:

<table width="0">

 <tbody>

  <tr>

   <td width="100"><strong>Class</strong><strong>Name</strong></td>

   <td width="173"><strong>File Name</strong></td>

   <td width="407"><strong>Description</strong></td>

  </tr>

  <tr>

   <td width="100">Player</td>

   <td width="173">inc/player.class.php</td>

   <td width="407">Contains the Player class, must have a constructor and toString methods.</td>

  </tr>

  <tr>

   <td width="100">Team</td>

   <td width="173">inc/team.class.php</td>

   <td width="407">Contains the team with storage for the players in the team</td>

  </tr>

  <tr>

   <td width="100">FileAgent</td>

   <td width="173">inc/FileAgent.class.php</td>

   <td width="407">This is the static utility class for getting the file contents</td>

  </tr>

  <tr>

   <td width="100">TeamParser</td>

   <td width="173">inc/TeamParser.class.php</td>

   <td width="407">This is a utility class for parsing the CSV file</td>

  </tr>

 </tbody>

</table>

This is the static Page class that is used to display parts of the

Page                  inc/Page.class.php

page (and HTML) to the browser.

Hints:

Refer to the demo code for Week 6.

Remember you should not have any errors, warnings, or info messages in your application You must not have any logic that should be handled by your classes in the controller file.

Keep a clean seperation between the view and the controller.

Ensure you use the appropriate class types.

Search the Internet to figure out how usort is called inside a class.

Appendix: