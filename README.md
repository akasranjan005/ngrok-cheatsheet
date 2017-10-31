# ngrok-cheatsheet
Features of ngrok and its use


# Setup your ngrok's config.yml file
 * Signup on the ngrok webiste, https://dashboard.ngrok.com
 * After signup you will get your auth token
 
`./ngrok authtoken <YOUR_TOKEN_HERE>`

This command will save the auth token into the config.yml file. Doing this opens up a lot of features for you. Which i am going to explore.

`./ngrok http -auth 'user:password' <PORT>`

This command will start an ngrok server on your local machine on port 80 and set the authentication as shown in the figure,

![Alt text](https://raw.githubusercontent.com/akasranjan005/ngrok-cheatsheet/master/auth_ngrok.PNG "Authentication Screen Ngrok")



