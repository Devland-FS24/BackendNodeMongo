Previous requirements:

DEFAULT BROWSER, GOOGLE CHROME.
Visual Studio Code: CHOOSE CONTEXTUAL MENUS OPTION WHEN ASKED


IMPORTANT!! MAKE SURE YOU HAVE INSTALLED:
* NodeJS 21.4.0 for windows 10/11
* Visual Studio Code.
* MongoDB 64 bits for Windows MSI installer.

 (OPTIONAL) POSTMAN for Windows 10

(RECOMMENDED OPTION) NVM: NODE VERSION MANAGER.
https://realworlddev.hashnode.dev/installing-nvm-on-windows-11

* NVM ALLOWS YOU TO INSTALL AND USE MULTIPLE VERSIONS OF NODE JS. THIS IS BECAUSE THE NEW
VERSIONS OF NODE JS MAY NOT FULLY SUPPORT OLD VERSIONS OF ANGULAR.

--------------------------------------------------

WHAT'S THIS APPLICATION ABOUT?

Description:

This is a NODEJS backend API implementing a MongoDB No-sql database.


--------------------------------------------------

HOW TO RUN IT LOCALLY?

--- RUN MONGODB:

1- Download the GITHub repository "BackendNodeMongo".

2- Create the folder C:\BackendNodeMongo and install the repository inside this folder.

3- Go to this folder with the Windows Explorer and type CMD in the address bar overwritting the path. Hit enter.

4- In the command prompt console type in "npm install"

5- After the installation of packages is finished, type in "npm run start".
    If succeeded you should see the message "Database connected".
    The database name is "node-typescript-app"

6- (OPTIONAL). You can open another Command Prompt console window as mentioned on step 3
    then type in "code ." then hit enter. Visual Studio Code will open your 
    BackendNodeMongo project locally in your computer.

7- You can preload employees manually using POSTMAN. Open POSTMAN on your local
    computer with Windows 10/11 and use the following URL to POST new employees
    to the MongoDB database:

    URL: http://localhost:4000/employee

    JSON EXAMPLE DATA IS PROVIDED HERE BELOW:
    {
        "name": "elena Martin",
        "email": "pedro@mail.com",
        "mobile": "999999",
        "dob": "21-18-1952",
        "doj": "25-12-2023"
    }

------ SCREEN CAPTURES AVAILABLE IN THE SCREEN CAPTURES FOLDER:

        \\BackendNodeMongo\Screen Captures

--------------------------------------------------


Highlights:

- Full Backend API made with NODEJS 21, MongoDB and TypeScript.


