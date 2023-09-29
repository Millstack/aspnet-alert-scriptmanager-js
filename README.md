# aspnet-alert-scriptmanager-js
apart from AlertMessage mrthod to show a pop up alert message at the top to notify certain important message to the user, but here if we redirect to other page then it wont work as the thread will be abanded, so we can use server side method using JavaScipt to render HTML code and send the alert prompt to the user which works even with redirect

Snippet page refernce
`https://www.codeproject.com/Tips/284507/how-to-show-the-message-and-redirect-to-other-page`

## 3 Types of ScriptManager codes

### 1. Alert message and Redirect
showing alert message to user and then redirecting from `Home` to `Welcome`

### 2. Alert message and Redirect with parameters in URL
showing alert message to user and then redirecting from `Home2` to `Welcome2` while passing parameters in the url so to use those parameters in redirected page (for fetching the user details, etc)

### 3. Alert message and Redirect with parameters in URL with User confirmation (OK / Cancel)
showing alert message to user and then redirecting from `Home3` to `Welcome3` while passing parameters in the url so to use those parameters in redirected page, only when user clicks on `OK` button and if `cancel` button is clicked then redirecting stops
