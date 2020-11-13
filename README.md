## 2 Factor Authentication using Speakeasy

Use the **authenticator extension or mobile app** for getting the code from token.

- /api/register - For registering the user
- /api/verify - For verifying the user (Pass userId and token as payload - request body)
- /api/validate - For validating the token, If the token expires after some period of time.

- Used node-json-db => Use this if you're looking for quick setup which works as a database (json file)
- Used speakeasy => Used this to enable 2FA functionality.


It was so much fun to do this hands on!

In the near time, This is soon going to be integrated in almost all apps. Passing additional info with ususal info such as username, password.

[Blog Regarding 2FA](https://blog.logrocket.com/implementing-two-factor-authentication-using-speakeasy/ "Blog Regarding 2FA")
