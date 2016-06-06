# FDTP Develepment Environment Setup
***
### AJAX
Install WAMP server 

Run the examples from the www folder inside wamp

***

### Web Services
You will need JAVA EE Kepler and glassfish server installed 
***

##### JAVA
+ Install JAVA SDK 7
+ Set Path 


##### Install JAVA EE 7 : 
+ Download [EE7](http://www.oracle.com/technetwork/java/javaee/downloads/index.html) 
+ unzip glassfish. 
You will have a glassfish folder

##### Download Eclipse EE :
+ [eclipse ee kepler **(use only kepler)**](http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/keplerr) 

##### Configure Eclipse 
+ point the jdk path to eclipse 
 + Go to Window > Preferences. 
   Then under +Java+Installed JREs hit Add.
 + Select 'Standard VM' then Next
	JRE Home = C:\Program Files\Java\jdk1.7.XXXX
 + the rest should fill in

##### Configure Glassfish
+ Click on Window - Show views - Server
+ You can see the server tab with an error 
+ Click on that to add a server 
+ First we have to add the glassfish server adapter 
+ Click on download additional server adapters and then choose glassfish serevr tools
+ Wait unitl it installs. Restart eclipse if it is not restarted automatically.
+ Go to servers tab
+ You will have the same error message 
+ Click again to open 
+ This time you will see glasfish folder with options 
+ Select glassfish4 and hit next 
+ Now choose the folder where you have unzipped glassfish that came when you downloaded JAVA EE
  + the unzipped folder will have glasfish as a subfolder 
	choose this folder **(Eg : D:\glassfish4\glassfish)**
+ Leave defalut settings 
+ Click finish 
+ Now the server tab will have the glassfish server 
+ Test it by right cicking on it and choosing glasfish -> view admin console 
+ The server admin tab will open 