# sezzle_calc


Archive.zip is the file with the working solution for the take home assignment. I have used ReactJS for the project and created the calculator using it. Have stored the calculations with the help of LocalStorage which keeps track of the 10 operations. 


Additionally, after executing the previous solution, I tried using web socket i.e with the help of backend server to send the data to the socket and display accordingly on the front end. But there was some connection issue in the socket and conneciton was failing. I wanted to upload the socket solution as well as I had tried to implement something I didn't know in the first place and tried to debug it for sometime but could not find a way out. 
This solution displays the calculator and enables the user to calculate the input.


Steps:

download and decompress the zip file
using the terminal, use 'npx create-react-app (appName)' command to create a react app.
in the appName folder, copy and paste the contents of the decompressed folder, accordingly. 
all the components will be under src directory, where the root file App.js lies. 
when done, run 'npm install' if there are some dependencies if not installed.

when everything is done, run 'npm start' to start the app.


to run the second solution:
follow the above steps 

and in a separate terminal window, run 'node index.js' to start the server so that it can start listening. 


***I have not included node_modules folder as it has been placed in .gitignore. it will be automatically installed when 'npm i' is run or a react app is created using 'npx' command. 
