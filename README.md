# user-management-UI-spec
---
## Requirments:

- User should be able to creat a new user.
- User should be able to view a table of users' details.
- User should be able to hide disabled users.
- User should be able to sort the columns numerically or alphabetically
- User should be able to filter the table 
---
## UI Components

- Users Table: contains ID/User Name/Email/Enable for each user
	
ID|User Name|Email|Enable
|--|---------|-----|------
1 | AdminUser | admin@piworks.net | true
2 | Test User | testuser@piworks.net | true

>Each column in the table has its own filter.

- 'New user' button
  - On_click: display new user form on the right of the page to fill the users' data
     - UserName
     - Display Name
     - Phone
     - Email
     - User Roles: dropdown list of Guest/Admin/SuperAdmin
     - Enabled: checkBox 
    
<p>&nbsp;</p>

- 'Hide Disabled Users' CheckBox
  - To display the enabled users only
  - [ ] Hide Disabled Users
  
<p>&nbsp;</p>

- 'Save User' button: save and submit the form.



