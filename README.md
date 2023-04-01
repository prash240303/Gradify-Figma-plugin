
# Gradify Figma Plugin
# NOTE : 
the Plugin has not been published yet on figma due to plain HTML , the plugin needs UI design and code which I dont know how to do yet . It would be helpful if I get some mentorship/help on this .


Gradify is a Figma plugin that allows designers to easily create beautiful gradients with customizable color stops and preview them in real-time. This plugin is built using HTML, CSS, and JavaScript and is intended to be used within the Figma design tool.

![image](https://user-images.githubusercontent.com/93905743/225101176-2814a0f8-7197-4072-a135-813ef2d08905.png)

## Installation
To use Gradify, you can either download the source code and run it locally or install it from the Figma plugin store. To install from the Figma plugin store, follow these steps:

Open Figma and navigate to the "Plugins" menu on the left-hand side of the screen.
Search for "Gradify" in the search bar.
Click on "Install" to add the plugin to your Figma workspace.
Alternatively, you can download the source code from the GitHub repository and run it locally by following these steps:
## Clone or download the repository.
Open the terminal and navigate to the repository directory.
Run the command npm install to install the necessary dependencies.
Run the command npm start to start the plugin.

## Usage
Once the plugin is installed, you can access it by selecting a shape or group of shapes and clicking on the "Plugins" menu on the top toolbar. From there, select "Gradify" and the plugin will open in a new window.

In the plugin window, you can adjust the gradient by adding or removing color stops, changing the colors, and adjusting the opacity and position of each stop. You can also adjust the angle and type of gradient (linear or radial) and preview the changes in real-time.

## Contributing
If you would like to contribute to Gradify, please submit a pull request with your changes. Before submitting a pull request, please make sure that your code is properly formatted and that all tests pass.





Below are the steps to get your plugin running. You can also find instructions at:

  https://www.figma.com/plugin-docs/setup/

This plugin template uses Typescript and NPM, two standard tools in creating JavaScript applications.

First, download Node.js which comes with NPM. This will allow you to install TypeScript and other
libraries. You can find the download link here:

  https://nodejs.org/en/download/

Next, install TypeScript using the command:

  npm install -g typescript

Finally, in the directory of your plugin, get the latest type definitions for the plugin API by running:

  npm install --save-dev @figma/plugin-typings

If you are familiar with JavaScript, TypeScript will look very familiar. In fact, valid JavaScript code
is already valid Typescript code.

TypeScript adds type annotations to variables. This allows code editors such as Visual Studio Code
to provide information about the Figma API while you are writing code, as well as help catch bugs
you previously didn't notice.

For more information, visit https://www.typescriptlang.org/

Using TypeScript requires a compiler to convert TypeScript (code.ts) into JavaScript (code.js)
for the browser to run.

We recommend writing TypeScript code using Visual Studio code:

1. Download Visual Studio Code if you haven't already: https://code.visualstudio.com/.
2. Open this directory in Visual Studio Code.
3. Compile TypeScript to JavaScript: Run the "Terminal > Run Build Task..." menu item,
    then select "npm: watch". You will have to do this again every time
    you reopen Visual Studio Code.

That's it! Visual Studio Code will regenerate the JavaScript file every time you save.
