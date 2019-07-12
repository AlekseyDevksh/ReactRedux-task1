# Task 1

Implement an application that can display the following pages:

- **/** - home
- **/login** - login and password page
- **/profile** - dashboard

If the user clicks on the **Profile** page and he is not “authorized” - transfer to the **/login** page. 
  
The login form (**/login**) accepts mock data:
  
```sh
username: Admin
password: Admin12345
```

If incorrect data is entered, output the message:
> "The username or password you entered is incorrect"

If correct data is entered - transfer to **/profile** page.
User authorization information will be stored in localStorage with the parameter true / false.

Design: https://zpl.io/2GAeqmJ
