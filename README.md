# AutomationProtractor


PREREQUISITES: Download and Installation-
How to Install :
1. Install nodeJS on our machine : https://nodejs.org/en/download/.
 --> Open command prompt, type <npm -version>.
2. Install protractor : 
  --> Open Command prompt, type <npm install -g protractor>
  --> Press Enter.
3. Install JDK
4. Install WebDriver Manager :
  --> Open Command Prompt, type <webdriver-manager update>
  --> This will install latest WD manager and chromedriver if not available on your machine or else, it will update them to the latest version.
5. Start webdriver manager :
  --> Open Command Prompt, type <webdriver-manager start>
  --> Keep this command prompt open, do not close this
  --> In browser, type <localhost:4444>, click on console.
  --> If the console shows "Session" title, with "Create Sessions" and "Refresh Sessions" buttons, means webdriver is running properly. This is nothing but Selenium Server.
6. Download and install Visual Studio Code : https://code.visualstudio.com/download
  --> Used to write the code
  
  
HOW TO WRITE THE SCRIPT:
1. Create a workspace for the project
  --> Create a folder where you want to save the projects
2. Open Workspace in Visual Studio Code
  --> Open Visual Studio Code --> File --> Open Folder
  --> Select Created folder.
3. Use npm init to create a package.json file
  --> Open new command prompt, use <cd> to navigate to workspace folder created.
  --> Type <npm init>
  --> It will ask you multiple questions, like package name, git repository, version, etc. Fill all that info. If you do nt want any value filled, just press enter and leave it "default" or blank.
  --> In the folder from File explorer, notice that package.json file will be created.
  --> In VS Code, notice that package.json will be created.
  --> This is equivalent to pom.xml in maven
4. Add Dependencies for your project here
  --> This is a JSON file, so JSON syntax should be used.
  --> Above "Scripts" tag, add dependency tag
  --> "dependencies":{      },
  --> Add all your dependencies within these curly braces using JSON Syntax.
5. Adding basic dependencies in your project from VS Code : https://www.npmjs.com/package/protractor
  --> Protractor: "protractor":"^Latest Version Number"; e.g. "protractor":"^7.0.0" [Used to write logic]
  --> Jasmine: "jasmine":"^Latest Version Number"; e.g. "jasmine":"^3.6.1" [Used to write Test cases]
6. Install dependencies in VS Code
  --> Save the changes in package.json
  --> Click on View --> Terminal
  --> Open Terminal tab
  --> Type npm install
7. Create Files from VS Code-
  --> Configuration file (conf.js) (Specify where selenium is running and where are your specifications)
  --> Specification File (spec.js) (For Writing Actual JS Code)
  
  
How to Run The code:
1. In terminal of VS Code, type <protractor conf.js>
2. To Clear the terminal, type <clear> in terminal
