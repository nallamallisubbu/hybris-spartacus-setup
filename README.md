<b>Requirements to Setup Local </b>

<p>Angular development environment should be install following softwares:</p>

•	Angular CLI: 9.1 or later.<br>
•	node.js: 10.14.1 or later, < 13.0. The most recent 12.x version is recommended <br>
•	yarn: 1.15 or later<br>
•	Visual Studio<br>
•	SAP Commerce Cloud Instance – 1905 or higher<br>

<p>Following are the steps to create project and enable Spartacus libraries <br>
1. ng new <project-name> --style=scss   ##Create new Angular project with default SCSS styles (Eg: project-name : hybris -angular-client </br>
2. cd <project-name> <br>
3. code .   # #code will be open in Visual Studio to edit app <br>
4. ng add @spartacus/schematics --baseUrl  https://localhost:9002  --baseSite electronics-spa <br>
<p> Use following command to add base URL if want to connect public instance. <br>
5. ng add @spartacus/schematics --baseUrl  https://api.c39j2-walkersde1-d3-public.model-t.cc.commerce.ondemand.com --baseSite  electronics-spa <br>
6. ng serve <br>
7. open http://localhsot:4200
