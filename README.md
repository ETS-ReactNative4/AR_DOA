# AR_DOA

School Project at Bonch-Bruevich Saint Petersburg State University of Telecommunications (SPBSUT) . 

Russian: Санкт-Петербургский государственный университет телекоммуникаций (СПбГУТ) . 

## Goal

The goal was to make an AR application who related on DOA System . 

What is DOA ?
You can read about it [here (Russian)](www.sut.ru/doci/nauka/review/20174/64-70.pdf) or [here (English)]() .

## Examples

On this example, the text of the application is fetched by a REST Api (provided by handle.net, you can also use doi.org) . 
The API request the GHR (Global Handler Registery), who request itself a LHR (Local Handler Registery).

Screenshot of the Json provided by the REST Api in our case:

![RESTAPI](https://image.noelshack.com/fichiers/2019/16/5/1555626920-68747470733a2f2f696d6167652e6e6f656c736861636b2e636f6d2f66696368696572732f323031392f31362f332f313535353530353733312d73637265656e73686f742d323031392d30342d31362d61742d30312d33392d32382e706e67.png)

Demo of the fonctionnal application requesting the API of the GHR to fetch previously showed data:

![ARDemo](https://thumbs.gfycat.com/WatchfulCalmAngelwingmussel-size_restricted.gif)

## Special thanks

Mahmood Albahri - Teacher of DOA - IoT in СПбГУТ . 

СПбГУТ to grand us access to the GHR of Russia . 

## Install

Libraries used:
[ViroAR by ViroMedia](https://viromedia.com/viroar)

Prerequisites:

Android -> An ARCore supported device .

iOS -> iOS Device with A9 chip or higher and running iOS 11 or higher . 


Make sure to have npm and node installed on your pc . 

MACOS:
https://blog.teamtreehouse.com/install-node-js-npm-mac

LINUX:
https://blog.teamtreehouse.com/install-node-js-npm-linux

WINDOWS:
https://blog.teamtreehouse.com/install-node-js-npm-windows

--------------------------------------------------------

Register into ViroMedia and generate a new API Key
Edit `App.js` under your project

Download the ViroMedia testbed app:

iOS:
https://itunes.apple.com/us/app/viro-media/id1163100576?mt=8

Android:
https://play.google.com/store/apps/details?id=com.viromedia.viromedia

Now, make sure ngrok is also installed and run the command `npm install` .

After the installation is completed you can run `npm start`, the ngrok link should appear in the console.
You just have to copy it to the ViroMedia testbed app.

