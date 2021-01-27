# Test Plan 

## <p style="text-align: center;">Overall Test Plan</p>

I will use several types of test to ensure that "Arcadio" is functioning as intended. The project consists of both software and hardware, so each piece will need to be tested accordingly. A main test on overall system performance will be undergone in which a user will navigate to the web page of "Arcadio" and upload a game to play on the machine to play. The user will have no knowledge other than basic instructions on how to use the machine/web page. The game file will be in a set folder during this test, with the instructions stating what files are acceptable. This blackbox testing will serve to test if the system is responding correctly and easy to use (Test Case 1). 

Once the usability of "Arcadio" is tested, bugs and errors in performance will be recorded. In a second phase of testing the user will have the option of uploading a file of their choice that follows the technical specifications stated in the instructions (Test Case 2). This phase will include an overall testing of the web interface to ensure the accuracy of all buttons and navigation on the page. These functional test will serve to correct any bugs observed during normal usage.

After the systems performance, and web interface functionality are tested, a third and final phase of testing will be performed. This third phase will consists of checking the communication between the hardware and software. (Test Case 3) Ensuring the coin operator functions correctly to start the game, the joysticks and buttons function as intended by the web interface, and the LEDs are properly controlled. These test will be performed by myself (whitebox testing), and will include unit and integration testing.

## <p style="text-align: center;">Test Case Descriptions</p>



FSP1.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Full System Performance Test 1</b>

FSP1.2 &nbsp;&nbsp;&nbsp;&nbsp; The test will ensure machine is operational from game select to gameplay as a guest user.

FSP1.3 &nbsp;&nbsp;&nbsp;&nbsp; The guest user will login to the machine following the given instructions. Their goal is to choose a game to play, and then play the game.

FSP1.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: The user will have limited options as a guest, and will only be able to select a game to load and play on the machine.

FSP1.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The menus change accordingly, and the game loads correctly with easy to use controls.

FSP1.6 &nbsp;&nbsp;&nbsp;&nbsp; Normal

FSP1.7 &nbsp;&nbsp;&nbsp;&nbsp; Blackbox

FSP1.8 &nbsp;&nbsp;&nbsp;&nbsp; Functional

FSP1.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration

</br>
FSP2.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Full System Performance Test 2</b>

FSP2.2 &nbsp;&nbsp;&nbsp;&nbsp; The test will ensure that the entire system functions as expected while being ran as admin.

FSP2.3 &nbsp;&nbsp;&nbsp;&nbsp; The admin user will login to the machine following the given instructions, with additional administrative task enabled. The user will change some setting (led color, controls), and then choose a game to play.

FSP2.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: The user will have the ability to change system settings, and can choose a game to launch.

FSP2.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The menus and settings will change according to the changes made by the user. The game will then load and be playable on the machine.

FSP2.6 &nbsp;&nbsp;&nbsp;&nbsp; Normal

FSP2.7 &nbsp;&nbsp;&nbsp;&nbsp; Blackbox

FSP2.8 &nbsp;&nbsp;&nbsp;&nbsp; Functional

FSP2.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration

</br>
WU1.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Web User Test 1</b>

WU1.2 &nbsp;&nbsp;&nbsp;&nbsp; This test will test functionality of guest user upon logging into web interface.

WU1.3 &nbsp;&nbsp;&nbsp;&nbsp; A guest user will be asked to log into the web interface through the guest profile. 

WU1.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: The user will login to the guest profile.

WU1.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The web page will change after the guest properly authenticates.

WU1.6 &nbsp;&nbsp;&nbsp;&nbsp; Normal

WU1.7 &nbsp;&nbsp;&nbsp;&nbsp; Blackbox

WU1.8 &nbsp;&nbsp;&nbsp;&nbsp; Functional

WU1.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration

</br>
WU2.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Web User Test 2</b>

WU2.2 &nbsp;&nbsp;&nbsp;&nbsp; This test will check the functionality of all menu navigation as a guest user.

WU2.3 &nbsp;&nbsp;&nbsp;&nbsp; A guest user will login to the web page, and navigate all menu options. This will ensure the menu is responding properly, and test permissions of guest and admin accounts.

WU2.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: The user will click on menu tabs to navigate the web page.

WU2.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The menu will change the web page to a new page depending on the users selection.

WU2.6 &nbsp;&nbsp;&nbsp;&nbsp; Normal

WU2.7 &nbsp;&nbsp;&nbsp;&nbsp; Blackbox

WU2.8 &nbsp;&nbsp;&nbsp;&nbsp; Functional

WU2.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration

</br>
WU3.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Web User Test 3</b>

WU3.2 &nbsp;&nbsp;&nbsp;&nbsp; This test will ensure all performance of the web interface is quick to respond, and enjoyable to use.

WU3.3 &nbsp;&nbsp;&nbsp;&nbsp; A guest user will login to the machine, navigate to the games tab, and choose a game to play and upload.

WU3.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: The user will authenticate, navigate to the games tab by clicking on the menu option, and will select a game before hitting "Upload & Play"

WU3.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The web page will change accordingly, and will load the selected game to the machine to be played. No long wait times will be encountered, and the pages will be quick to respond.

WU3.6 &nbsp;&nbsp;&nbsp;&nbsp; Normal

WU3.7 &nbsp;&nbsp;&nbsp;&nbsp; Blackbox

WU3.8 &nbsp;&nbsp;&nbsp;&nbsp; Performance

WU3.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration

</br>
WA1.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Web Admin Test 1</b>

WA1.2 &nbsp;&nbsp;&nbsp;&nbsp; This test will ensure the LED lights can be controlled via admin login.

WA1.3 &nbsp;&nbsp;&nbsp;&nbsp; An admin user will login to the web interface, and change the LED lights via an admin settings page.

WA1.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: The admin user will navigate the web interface by clicking on the menu tabs. They will adjust the lights on the LED page with the controls available.

WA1.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The admin will navigate the settings page and the LEDs on the machine will change once any changes are made and saved.

WA1.6 &nbsp;&nbsp;&nbsp;&nbsp; Normal

WA1.7 &nbsp;&nbsp;&nbsp;&nbsp; Blackbox

WA1.8 &nbsp;&nbsp;&nbsp;&nbsp; Functional

WA1.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration

</br>
WA2.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Web Admin Test 2</b>

WA2.2 &nbsp;&nbsp;&nbsp;&nbsp; This test will ensure admin users are able to upload new games in the correct format to the "Arcadio", and can map controls to them.

WA2.3 &nbsp;&nbsp;&nbsp;&nbsp; The admin user will login and navigate to the games tab. Here they will choose a game to upload from another source. The web interface will determine if the selected file is suitable before running, and will allow the user to select controls to map.

WA2.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: The admin user will login to the web page, and will choose a game to upload by clicking on the games tab, clicking a game, and hitting "Upload and Play". The user will have several files to choose from to test detection of game files suitable for "Arcadio".

WA2.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The web page will respond according to user input, and will inform the user of selected games that cannot be uploaded as well as successful uploads.

WA2.6 &nbsp;&nbsp;&nbsp;&nbsp; Abnormal

WA2.7 &nbsp;&nbsp;&nbsp;&nbsp; Blackbox

WA2.8 &nbsp;&nbsp;&nbsp;&nbsp; Functional

WA2.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration

</br>
WA3.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Web Admin Test 3</b>

WA3.2 &nbsp;&nbsp;&nbsp;&nbsp; This test will ensure the admin user can change which games are visible to guest users.

WA3.3 &nbsp;&nbsp;&nbsp;&nbsp; The admin user will login to the machine, and navigate to the admin settings tab. Here they will choose which games are visible to guest users.

WA3.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: The admin user will login to the web page, navigate to the settings tab by clicking on the options icon, and will be able to choose which games guest users can see under the "Active Games" tab.

WA3.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The menu will respond as intended, and will allow the admin user to select which games guest accounts can see.

WA3.6 &nbsp;&nbsp;&nbsp;&nbsp; Normal

WA3.7 &nbsp;&nbsp;&nbsp;&nbsp; Blackbox

WA3.8 &nbsp;&nbsp;&nbsp;&nbsp; Functional

WA3.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration

</br>
C1.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Communication Test 1</b>

C1.2 &nbsp;&nbsp;&nbsp;&nbsp; This test will check the controls set in the web interface and the controls used within the game.

C1.3 &nbsp;&nbsp;&nbsp;&nbsp; I will login to the machine as an admin user, and will test several games with controls I set via the web interface and record. I will ensure each control functions according to the mapping set in the web interface.

C1.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: I will navigate the menu via the tabs, and will change to the controls setting menu for games. The inputs of the joysticks, and buttons will then be tested.

C1.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The web page will load as expected, and will set the controls of the "Arcadio". Once controls are set the game will display the control mapping.

C1.6 &nbsp;&nbsp;&nbsp;&nbsp; Normal

C1.7 &nbsp;&nbsp;&nbsp;&nbsp; Whitebox

C1.8 &nbsp;&nbsp;&nbsp;&nbsp; Functional

C1.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration

</br>
C2.1 &nbsp;&nbsp;&nbsp;&nbsp; <b>Communication Test 2</b>

C2.2 &nbsp;&nbsp;&nbsp;&nbsp; This test will check if coin operator is working properly to start a new game.

C2.3 &nbsp;&nbsp;&nbsp;&nbsp; I will login as a guest user and will launch a game, once the game has loaded I will insert a coin into the coin operator to start the game.

C2.4 &nbsp;&nbsp;&nbsp;&nbsp; Inputs: The web page will be navigated by the menu, and will be allow a game to be loaded.

C2.5 &nbsp;&nbsp;&nbsp;&nbsp; Outputs: The web page will change to the game tab and load the game as instructed. Once the game is at the play screen, a coin being inserted will cause the game to start.

C2.6 &nbsp;&nbsp;&nbsp;&nbsp; Normal

C2.7 &nbsp;&nbsp;&nbsp;&nbsp; Whitebox

C2.8 &nbsp;&nbsp;&nbsp;&nbsp; Performance

C2.9 &nbsp;&nbsp;&nbsp;&nbsp; Integration


## Test Case Matrix


|         		| Normal/Abnormal| Blackbox/Whitebox  | Functional/Performance  | Unit/Integration  |
| ------------- |:--------------:|:------------------:|:-----------------------:|:----------------:|
|     FSP1      | Normal         | Blackbox           | Functional              | Integration       |
|     FSP2      | Normal         | Blackbox           | Functional              | Integration       |
|     WU1       | Normal         | Blackbox           | Functional              | Integration       |
|     WU2       | Normal         | Blackbox           | Functional              | Integration       |
|     WU3       | Normal         | Blackbox           | Performance             | Integration       |
|     WA1       | Normal         | Blackbox           | Functional              | Integration       |
|     WA2       | Abnormal       | Blackbox           | Functional              | Integration       |
|     WA3       | Normal         | Blackbox           | Functional              | Integration       |
|     C1        | Normal         | Whitebox           | Functional              | Integration       |
|     C2        | Normal         | Whitebox           | Performance             | Integration       |


