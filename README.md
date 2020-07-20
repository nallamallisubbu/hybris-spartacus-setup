Requirements to Setup Local

Angular development environment should include the following:

•	Angular CLI: 9.1 or later.
•	node.js: 10.14.1 or later, < 13.0. The most recent 12.x version is recommended.
•	yarn: 1.15 or later
•	Visual Studio
•	SAP Commerce Cloud Instance – 1905 or higher

Following are the steps to create sample project and add Spartacus libraries
	ng new <project-name> --style=scss   ##Create new Angular project with default SCSS styles (Eg: project-name : hybris -angular-client
	cd <project-name>
	code .   # #code will be open in Visual Studio to edit app
	ng add @spartacus/schematics --baseUrl  https://localhost:9002  --baseSite electronics-spa
Use following command to add base URL if want to connect public instance.
	ng add @spartacus/schematics --baseUrl  https://api.c39j2-walkersde1-d3-public.model-t.cc.commerce.ondemand.com --baseSite  electronics-spa
	ng serve
	open http://localhsot:4200
