<!-- TITLE: Documentation -->

# Eslint

Eslint-
        ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.

Intallation:-

Use the code to install the eslint into the local system.
$Sudo npm install -g eslint



![alt text](https://github.com/psaini134/ESlint/blob/master/Desktop/ESlint/images/image1.png "Logo Title Text 1")

you should then setup a configuration file:-
$eslint –init


![alt text](https://github.com/psaini134/ESlint/blob/master/Desktop/ESlint/images/image2.png "Logo Title Text 1")

After that, We create Json files where we write the rules that are checked in the JavaScript code.

$touch .eslintrc.json

![alt text](https://github.com/psaini134/ESlint/blob/master/Desktop/ESlint/images/image3.png "Logo Title Text 1")

After these we use 
$subl .   (to open the editor for write the rules into the json file.)




![alt text](https://github.com/psaini134/ESlint/blob/master/Desktop/ESlint/images/image4.png "Logo Title Text 1")

Normally we write the ("extends': "eslint:recommended") to use the all rules that are present in the eslint version that installed into the local system.

![alt text](https://github.com/psaini134/ESlint/blob/master/Desktop/ESlint/images/image5.png "Logo Title Text 1")

We also write the customized rules into the json file and check the rule into the javascript code.

![alt text](https://github.com/psaini134/ESlint/blob/master/Desktop/ESlint/images/image6.png "Logo Title Text 1")


After writing the rules into the json file, we check the javascript code.
to run the command:-

eslit filename.js



![alt text](https://github.com/psaini134/ESlint/blob/master/Desktop/ESlint/images/image7.png "Logo Title Text 1")

$eslint test.js



and use the 'eslint --fix filename.js to fix the error into the file'.




