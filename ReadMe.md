# L03 Practice Hands On

# Components 

Lesson 3 Practice Hands-On
Directions
For your Lesson 3 Practice Hands-On, you will be working within a project provided below. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page.

Setup
Start off by downloading the starter project and unzipping it. The starter project will be in a folder named React.

Starter Project

After unzipping, move the starter project folder to the FEFReact folder located inside the FullStackWeb folder and rename it from React to L03HandsOn.

Open up your terminal/command prompt.

Run the following to navigate to your Desktop

cd Desktop
Next, navigate to the FullStackWeb directory in your terminal.

cd FullStackWeb
Then, navigate to the FEFReact directory in your terminal.

cd FEFReact
Navigate into the L03HandsOn directory:

cd L03HandsOn
Now that you are in the L03HandsOn directory, run the following:

npm install
Once npm has finished installing, you can test that the server is working with the following command:

npm start
You should now see your browser open up a blank page with an alert box saying "It's alive!".

Tip!
You can stop this process by pressing Control + C in the terminal, but for now, keep the server running.

Add the necessary import statements at the top of the src/index.js file and remove the alert that currently lives in that file:
import React from 'react';
import ReactDOM from 'react-dom';
Requirements
Add the code for the following requirements within the src/index.js file.

Step 1
Create a component named App that returns the following array:
const favoriteCars = ['Honda CR-V ', 'Toyota Highlander', 'Ford F-150', 'BMW X3', 'Subaru Crosstrek']
Step 2
Next, create a new component named List that maps over the following array and returns a numbered list of the array items.
Step 3
Lastly, include a ReactDOM.render() that renders the App component
Hint! Return the data from the List component within the App component