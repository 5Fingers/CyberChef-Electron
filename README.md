# CyberChef-Electron

## Introduction 
Needless to say - CyberChef is one of the biggest open source projects on the web today. <br>
https://gchq.github.io/CyberChef/

I use CyberChef on a daily basis, and when I have a lot of tabs open in the browser it's difficult and inconvenient to find it. <br>
That's why I created an electron version for CyberChef so that it can be run as a windowed system without the need for a tab in the browser.

## Usage
* Clone this repo:
```
git clone https://github.com/5Fingers/CyberChef-Electron.git
```
* Open the folder and run the command:
```
npm install
```
* Build this project depending your system
  * Windows:
  ```
  npx electron-builder build --win portable 
  ```
  * Mac
  ```
  npx electron-builder build --mac
  ```
* Run the portable file and Enjoy :)

## Screenshots
![Screen Shot 2022-08-02 at 18 25 11](https://user-images.githubusercontent.com/6413401/182414174-df6a06e0-4115-42ca-927d-0e4697831baa.png)

## Note
Using npx rather than npm will prevent electron-builder to be installed as a dependency!

## Acknowledgments
To the amazing guys who developed CyberChef (https://github.com/gchq/CyberChef) and of course to everyone who <br>
continues to support this amazing project.
