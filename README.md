Notes App
______________________________________________________________________________________

Summary

Welcome to your first React project!
In this project you will need to create a notes app - add notes, change notes, delete notes and more.

General Requirements

Like any project here at ITC, you will have to follow the milestones, and complete them one after another.
We will constantly check your github repository, so please commit and push your code frequently.
After you are done with a certain milestone, commit with a message that indicates your progress, e.g. “Milestone 3 done”, we will be able to know where you are and how to guide you.

Before you start
Read the milestones, get a general overview of the project.
Plan your app, you can even grab a piece of paper to draw your app on, and decide on which components you want to implement, and what they will do.

Extras
You can use 3rd party libraries if you want to, but be careful! It might look easy and time saving, but it also could complicated your process, as you’ll need to learn something new (each library has its own learning curve)
You can use a UI library if you want to (like Bootstrap), make sure to look for a React version of this library before you use it (if there is none, maybe it is better to skip it for now)
This is a design free project, use your imagination, but spend more time on coding the functionalities then making it pretty (we learn programming, not design)



Milestone 1

Features:
Create a basic form with input (multiline textarea), that allow the user to add notes
For every note added there should be the text and the date the note was created at
Display the notes in a grid



Milestone 2

Features:
Display date in human readable format: Aug 31th 12:30 PM
You can use the JavaScript Date object, or a date library you find online (there are many good ones)
Add a delete button, that when clicked prompting the user with a message “Are you sure you want to delete your note?” (you ca use JavaScript global confirm() function), and if the user hits confirm, delete the note from the list 



Milestone 3

Features:
Add an optional note title: in the form add an input for note title
In the note, display the title above the text
The user can add a note even without a title (then no title will be displayed in the note)


Milestone 3.1

Features:
Make your textarea to resize dynamically when use types text (add/remove rows)
Research online on how to do it
Remove the manual resize handler in the bottom right corner of the textarea 
You can use a library if you find one

Milestone 4

Features:
Add a popup modal to show a note
When a note is clicked, the modal should show the note information
You can use this library: https://github.com/reactjs/react-modal
Or you can search for a different one if you like (if you use a UI library, it might have a modal component)


Milestone 5

Features:
In the modal, add the ability to edit the note (title and body)
Use the form component in the modal to edit the note, if needed update your form component to be usable as a new note form and as an update note form
After the note is edited, add an update date
Show the update date in the note



Milestone 6

Features:
Deploy the app to Netlify
Read Netlify documentation on how to deploy.


Milestone 7

Features
Save notes to users storage
The notes should persist between reloads of the page
Do not use localstorage, as it is insecure. Use localforge instead, which uses indexedDB behind the scenes

Milestone 8

Features
Change the delete functionality to archive
Notes that have been archived should move to an archived section
Add the ability to move notes back to the list

Milestone 9

Features:
Add note as a reminder - when creating a note, add time to be reminded on
If a note should be reminded, show an alert to the user with the notes content


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
