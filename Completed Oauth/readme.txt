I finished the Oauth thing, but it is a little complicated to run. First you will need to run the server.js by typing in command window "node server.js" you will need to have node json installed before you run it. Then you will open your browser and type in the address "http://localhost:3000/" then you will see the application. Then you can click the login button and choose your google account.
The following is more specific steps for windows envrionment setting
You need to download both weather_with_map.html and server.js and put them in the same directory.
You need node.js to run the server-side code. 
Download node.js from its official website.
Install node.js.
After sucessful installation, you will see node.exe in the path C:/Profram Files/nodejs (Default)
Then you need to search in the start "Edit the system environment variables"  
Click "Environment varaibles" under "Advanced" 
Select "Path" under "Variables" and then click "Edit" 
If there is no "C:/Profram Files/nodejs" click "New" and browse to this location to add this path manually
Then click "OK" 
Restart the windows machine 
After restarting, open terminal and type "node -v" and "npm -v", if the version number displays the installation is sucessful
then type "npm install express-session" in the command line 
run "npm install express google-auth-library" 
run "node server.js" This starts the machine as a local server looking at port localhost:3000
then type in your browser "http://localhost:3000" 
Then you should see the web application running
click on the Login with google button
choose your account to continue 
You should see your name and email address displayed on the website
