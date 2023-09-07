# RippleApiSharePointPrototype

This is a prototype proving that the RippleAPI can run on SharePoint Online.
The Prototype is written in React and Typescript using the Virtual DOM available in React to integrate the Ripple API

Here is a video demostrating the prototype

https://www.youtube.com/watch?v=XuYCJZR5zc4

SharePoint is used by most top 50  Major Banks in U.S. SharePoint is used by 90% of Fortune 500 companies. SharePoint is used by 80% Federal Government Agencies. 190 million people use SharePoint. There is a great need for microtransactions within Government Agencies to track and allocate resources. Most Corporations use SharePoint for their Intranet and custom development. Banks use SharePoint for almost all their regulatory monetary workflows.  SharePoint is already a very big part of these Entities infrastructure . By integrating XRP into a SharePoint Template. Corp to Corp transactions. XRP Template on the SharePoint MarketPlace.

The scaffolding of the webpart is created using yo @microsoft/sharepoint

Install the SharePoint Online SPFx Yeoman Generator
npm install @microsoft/generator-sharepoint -g

The Project template is using React

Tsconfig.json - It is a json file called typescript configuration file. It holds the configuration of typescript.

package.json. - details the metadata of the package like name version and its dependencies

Gulpfile.js - gulp file and it is used to run gulp task

Config folder -This folder contains your configuration settings which are used when you serve your project and the settings such as 
version number of webpart and settings related to cdn which are used to deploy spfx solution

SRC Folder - src folder contains the source code of the webpart


