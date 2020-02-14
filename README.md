# Developer Profile Generator
An application to generate a PDF resume from a user provided GitHub profile

## The Assignment
This project was an assignment for UW Fullstack Coding Bootcamp. The instructions were to create a command-line application that would dynamically create a PDF from a GitHub username that invoked with the command: node index.js.The application is also supposed to ask for the user's favorite color, and use the input to add color to the PDF. The PDF was to include the following information from the GitHub profile:
* profile image
* username
* location with a link to Google Maps
* link to the GitHub profile
* link to the user's GitHub blog
* user bio
* number of repositories
* number of stars
* number of followers
* number of users following

## The Process
To make this application I used Node.js and ran my JavaScript in the console. Therefore all I needed was a index.js file to complete the assignment. I started by requiring all of the node modules I would need (inquirer, axios and puppeeter). Next I made an asynchronous function that would prompt the user with questions using inquirer. After the promise was fulfilled, I used axios to retrieve data from the user-inputted GitHub profile. I organized the data into an object, and then used template literals to place the object values into HTML. I styled the HTML with Bootstrap and colored the cards using the inputted favorite color. Next I used puppeteer to capture the HTML page on a PDF file and save it into the file. 

## The Outcome
The application runs using Node in the console, and asks the user for a name, GitHub username and favorite color. It then takes the data from the inputted GitHub user and generates a PDF with the required information. Here is an example of the PDF that is generated from my GitHub:

![Image of generated PDF](https://github.com/austenpturner/profile-generator/blob/master/assets/profile-PDF-image.jpg)

## Thanks for reading! :smile:
Please contact me with any questions or comments: austenpturner@msn.com
