# g2field

1.Field Master Monitor Page
--connect the g2field-be : "ssh g2field-be"
--open broswer and type the webpage : "localhost:8080"
--the page is under "Status/Field Master Monitor"
--the source code of the page is localated at "/home/newg2/Gm2FieldOnline/gm2fielddaq/online/custom/"
--the html file is "FieldMasterMonitorPage.html"
--the css file is "fieldmastermonitor.css"
--the javascript file is "FieldMasterMonitor.js"
--if want to change the page layout and style, change the .html and .css file
--if want read ODB data and replace the variable in html, change the .js file

2.Muon g-2 DQM / Monitor
--connect the g2field-be to ensure can open the page : "ssh g2field-be"
--open broswer and type the webpage : "localhost:3335"
**change the code locally when test ok, then go to g2field-be to change the "real" worked files**
--connect the g2bz-server : "ssh g2bz-server" 
--config the environment : ". gm2offline_setup.sh"
--to change the page go to : "/home/bzli/Gm2FieldOffline/srcs/gm2dqm/node/trolley"
--there are 2 subdirectory : "public" and "views"
--under "views" there are some .pug files which can change the layout and style of the page : "trolley-monitor.pug"
--under "public/script" there are some .js which can change the data of the page : "trolley-monitor.js"
