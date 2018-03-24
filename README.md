# Installation-of-Visual_studio-with-jest-javascript-

Step1:-Download VS code file (.deb for ubuntu) from the given url:-

https://code.visualstudio.com/download

Step2:- Now go to downloaded file.

Step3:-open Terminal and go to the folder where code.deb file is downloaded and run the command to install vs code:

sudo dpkg -i code_1.21.1-1521038896_amd64.deb

Step4:-Now create a folder in your system this is your project for eg familyCare

Step5:-create the new documents in the familyCare folder i.e. sum.js, sum.test.js 

Step6:-now open this folder in visual studio

1.click on file option.
2.select open folder option.

Step7:-now open the terminal in visual studio by clicking-

ctrl+~

Step8:-Now to create or initialise the package.json in your folder run the command:

npm init

Step9:-add the following section in package.json

{
  "scripts": {
    "test": "jest"
  }
}

Step10:-Now to install the Jest in visual studio run the following command:

npm install --save-dev jest

Step11:-Finally run your project by run the command:

npm test
