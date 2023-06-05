# Welcome to the CovEd Web Development Workshop!

To get started with making your own website, follow the instructions below!

## Installation

### Download Starter Code

First, you're going to need to download the starter code onto your computer. To do so, click the green "Code" button in the upper right hand corner of the screen, followed by "Download ZIP":

<img src="https://github.com/jacksonmoody/coved-workshop/assets/56370370/78155395-3654-4b0b-b19b-059e520ce458" width="300">
<br><br>

Once the download has completed, find where the .ZIP file is located on your computer and unzip it ([mac](https://support.apple.com/guide/mac-help/zip-and-unzip-files-and-folders-on-mac-mchlp2528/mac)) ([windows](https://support.microsoft.com/en-us/windows/zip-and-unzip-files-f6dde0a7-0fec-8294-e1d3-703ed85e7ebc)).

### Download Node.js

If you haven't already, you will also need to download Node.js: https://nodejs.org/en/download

### Download Code Editor

If you haven't already, you will also need to download a code editor. We're going to be using Visual Studio Code in this workshop, which you can download here: https://code.visualstudio.com/Download

However, feel free to use a different code editor if you feel more comfortable with that!

### Install Dependencies

Lastly, you will need to open the project and install some dependencies. To do so, open Visual Studio Code (or your code editor of choice) and click "Open Folder". Then, select the .ZIP file you extracted earlier.
<br><br>
<img src="https://github.com/jacksonmoody/coved-workshop/assets/56370370/b1a54097-e62f-4ba2-9001-1c6defea5f52" width="300">

Once you've opened the .ZIP file, click on "Terminal" > "New Terminal" to open a new terminal window.
<br><br>
<img src="https://github.com/jacksonmoody/coved-workshop/assets/56370370/b1492e57-333d-4a4e-b731-19fffdcdbec9" width="300">

Once this terminal window opens, type in `npm install` to install the necessary dependencies.

## Running Your Code

If everything installed successfully, you can type in `npm run server` into the terminal window to run your development server! 
Try navigating to [http:localhost:8080](http:localhost:8080) to see the result!

<details>
<summary>Run into an error?</summary>
  
 - If you got an error like `npm command not found`, Node.js is probably not installed. Try following the instructions [here](https://nodejs.org/en/download) to install it. 
  
 - If you get an error like `command not found: http-server`, try running `sudo npm install http-server -g` and then trying again.
  
 - If you run into another error, or if those steps do not fix the error, please ask your instructor for help!
  
</details>
