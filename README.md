1) npm install --save react-router-dom

Add flow. Flow provide some type checking and prevents unwanted data into the application
2) npm install --save flow-bin
 add the script to run flow.. in package.json, under scripts:
 "flow": "flow"

 then run -> npm run flow init
 this will create .flowconfig file
 .flowconfig provide options to add various stuff. Look at the documentation on how to use it.
 then add //@flow in each of the files we want to use it..like we have done in App.js
 then start the flow server, 
 npm run flow
the above step will flag issues if found.