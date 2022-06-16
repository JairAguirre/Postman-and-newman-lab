# Postman-and-newman-lab


Quick Summary

This lab is about a manual test of an API  using Postman. nn the instruttions below you can find how to execute the test using newman. 

Solution: 

The methods tested were: 
  1. Add pet ( POST). 
  2. Get Pet (GET). 
  3. Place an order for a pet (POST). 
  4. Get the order plced (GET). 

The link of my postman collection is:  https://www.getpostman.com/collections/ca0b7a187355c8f3d3f8 

For running this code using newman  you will need: 

1. Install node.js
2. Install npm 
Once you verify the instalation of the previews steps: 
3. Install newman using:  npm install -g newman 
4. For running my colleciton you must use: newman run link_of_collection 
 in my case, you have to type:  newman run https://www.getpostman.com/collections/ca0b7a187355c8f3d3f8
newman
5. You should get a table with a summary of the execution and succesfull message. 
