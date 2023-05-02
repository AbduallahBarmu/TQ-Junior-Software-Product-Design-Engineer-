# TQ-Junior-Software-Product-Design-Engineer-

Pages: 
User Management Page (/) 
## Header( "New User" button with + icon  , "checkbox" Hide Disabled User on the left side  , "Save User" button on the right corner of the Header)
    - clicking on "New User" button will open a modal dialog that necessary to field to save new user information in the table 
    - clicking on "Save User" button will save new user information in the table after filling the dialog with new user information 
    - clicking on "checkbox" will hide Disabled users from the users table

## right section: table displaying the users data, including 4 columns filling the width and height of the right section 
between (header and bottom section)then each column is scrolled in itself if/when there are multiple rows:

    - ID column : 
        id number of the user

    - User Name column : 
        string of the user name

    - Email column : 
        string of the email address format 

    - Enabled Column : 
        boolean indicating whether True of False 

## left section is a modal dialog that appears when a Admin clicks the "New User" button to add new user (user form includes labels and input boxes for the following fields)
    - Username
        the name of the new user

    - Display Username
        the name of the new user that will be displayed

    - Phone
        phone number of the new user
   
    - Email
         Email address of the new user
    - User Roles (with select element ):
        - Guest
        - Admin
        - SuperAdmin

    - Enabled (checkbox)


Markdown Syntex : 

[+ New User](#link)    [x]  Hide Disabled User                               [Save User](#link)


| ID | User Name |      Email          | Enabled  |

|----|-----------|--------------------------------|

| 1  | AdminUser | AdminUser@gmail.com | ture     |

| 2  | Test User | janedoe@gmail.com   | true     |




##  New User 

### Username : 

[______]  <!-- Input box -->

### Display Username:

[______]  <!-- Input box -->

### Phone :

[______]  <!-- Input box -->

### Email :

[______]  <!-- Input box -->

### User Roles: select user roles ..

- [ ] Guest
- [ ] Admin
- [ ] SuperAdmin

### Enabled: 

- [ ]  <!-- Checkbox -->



