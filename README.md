# UI-SPEC-DOCUMENT

# User Interface Specification Document

The user interface specification document in English for the user management screen. This interface will come from 3 sections: user registration screen, admin screen and button container.
* Ability to add new User with rectangle shape +New User button on the top left of the page
* Ability to save user with rectangle shape Save User button on the top right of the page
* Ability to hide disabled user with tick button that writes 'Hide Disabled User' right to the button
* Right half of the page should include New User header row and below that there must be four input rows, one select row and one tick button one under the other.
* Left half of the page should include an SQL like table which shows the users and information about them

## Button Container

The button container will be above the admin and user registration screens. The horizontal length of the container will be 100 px, the vertical length will be 8 px. The buttons in the container are as follows:

1. New User
2. Hide Disabled User
3. Save User

### New User Button

* This button will be on the far left of the container and will be rectangular. The margins of the button should be 50 px from the left, 10 px from the top and bottom.
* The button to be rectangular should have the color code #167BB3 or close tones of the specified color.
* A "+" icon will be placed to the left of the "New User" text in the button. The icon and text will be centered inside the button.
* This button will lead the administrator to the new user screen.

### Hide Disabled User Button
* This button will be in the container as "Check Button". The text "Hide Enable User" will be located adjacent to the right of the check box.
* This button will be 5 px to the right of the "New User" button and will be vertically centered according to the container height.
* This button will hide the inactive users in the admin screen.

### Save User Button
* This button will be on the far right of the container and will be rectangular. The margins of the button should be 5 px from the right, 1 px from the top and bottom.
* The button to be rectangular should have the color code #167BB3 or close tones of the specified color. The icon and text will be centered inside the button.
* This button allows to save information or updates on the user registration screen.

## User Registration Screen
This section will appear on the left side of the screen when a user login or update will be made by the administrator. This screen will open when the "New User" button is pressed or an existing user is clicked on the admin screen. The user information requested on the screen is as follows:

* Username
* Display Name
* phone
* Email
* User Roles
* Enable (User activity) When the "Save User" button is clicked, the information found here will be sent to the admin screen.
* The container with the title "New User" will have a length of 50 px horizontally and 8 px vertically. The "New User" title should be 24 pts.
* The user information under the title should be written as a list. The requested user information should be on the left of the screen. The boxes where the information will be written should be rectangular text boxes. Text boxes should be 5 px high and 30 px wide.
* The space between the two text boxes should be 2 px. The texts of the requested information should center the text boxes vertically.
* The "User Roles" box should present 3 options during information entry and these options should appear when the box is clicked. Inside the box should be a placeholder with the words "Select user roles...". The user roles to be found in the options are as follows.
 1. Guest
 2. Admin
 3. SuperAdmin
* The "Enable" option should be on the screen as a check box, unlike other information.

## Administration Screen
Some information of users registered in the system should appear. The information to be displayed is as follows:

* User ID
* Username
* Email
* Enabled (User activity(true/false)) Only "Enabled=true" users should appear on the screen by filtering with the "Hide Disabled User" button in the button container. Admin should be able to update their information by clicking on an existing user. There should be a filter icon and a sort icon next to the information titles.
* When the header in each column is clicked, there should be 3 options and you should give an icon accordingly.
  1. ASC(ascendant)
  2. DESC(descendant)
  3. By creation time
* In the screen divided into "New User" and "Administrator", this screen should be on the left.
* The color of the title section of the table should be #0E98E5. Text and icons must be white in color. Text font size should be 12.
* In the section with user information, the colors should be consecutively white and lightblue. The texts should be 12 pts in black.
