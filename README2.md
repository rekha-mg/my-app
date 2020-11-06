### First Reactjs Project
* Refered from the below link

>https://www.tutorialspoint.com/reactjs/reactjs_environment_setup.htm

* After successfully installing NodeJS, we can start installing React upon it using npm. You can install ReactJS in two ways

* 1.Using webpack and babel.

* 2.Using the create-react-app command.

### I have created using the second method.

### Using the create-react-app command
* Instead of using webpack and babel you can install ReactJS more simply by installing create-react-app.

* Step 1 - install create-react-app
* Browse through the desktop and install the Create React App using command prompt as shown below −

>C:\Users\Tutorialspoint>cd C:\Users\Tutorialspoint\Desktop\
> C:\Users\Tutorialspoint\Desktop>npx create-react-app my-app
* This will create a folder named my-app on the desktop and installs all the required files in it.

* Step 2 - Delete all the source files
Browse through the src folder in the generated my-app folder and remove all the files in it as shown below −

>C:\Users\Tutorialspoint\Desktop>cd my-app/src
>C:\Users\Tutorialspoint\Desktop\my-app\src>del *
>C:\Users\Tutorialspoint\Desktop\my-app\src\*, Are you sure (Y/N)? y
* Step 3 - Add files
Add files with names index.css and index.js in the src folder as −

>C:\Users\Tutorialspoint\Desktop\my-app\src>type nul > index.css
>C:\Users\Tutorialspoint\Desktop\my-app\src>type nul > index.js
In the index.js file add the following code

>import React from 'react';
>import ReactDOM from 'react-dom';
>import './index.css';

* Step 4 - Run the project
Finally, run the project using the start command.
