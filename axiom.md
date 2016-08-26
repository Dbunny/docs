

Docs server is a node app running on NODEJS-server instance
===========================================================

connect ssh 
add credentials, sonnection string exemple

is the app running test

    DEBUG=myapp:* npm start

run th app in th ebackground

run the app

how to save a doc from stackedit

files are saved on the NODEJS-server instance here : /home/doc

the above folder is the root of docs, if you want to store a tech type of doc you may want to store a doc in /home/doc/tech as mydoc.md

how the doc server is parsing the file



troubleshooting

make sure stackedit ip is allowed to ssh in our server, if not sure wide open ssh try again then check the auth.log to add the new ip in the firewall inbound rules in AWS console

forder permissions, meke sur folder permissions are set to the user docs

check credentials and path are correct, the root folder for docs is /home/docs





get this to parse md file
https://www.npmjs.com/package/angular-md