# nest-cam

![picture alt] (https://github.com/iyeremuk/nest-cam/blob/development/nest-api.jpg)

##Synopsis##

Nest cloud API is a near real-time data API offering subscription based access to data shared by Nest devices. Nest is a single device in structures,including all devices.Here data is built around the concept of devices with addressable data URL's called data locations.The video recorded by the nest device i.e camera is live fed in to the users desktop by means of REST API structure.
Various devices in the data model include:
* Thermostats
* Smoke control Aarms
* Cameras
* Yale clock
The data attributes for the nest camera is maintained in the form of json document as indicated by the below screenshot.
All the values updated in real-time are stored as JSON documents.

![picture alt] (https://github.com/iyeremuk/nest-cam/blob/development/camera%20metadata.png)

The below picture illustrates how the devices interact with in the NestAPI 
![picture alt] (https://github.com/iyeremuk/nest-cam/blob/development/hownestworks.PNG)

##List of functionalities enabled by Nest-cam##
-View list of devices at home
-View energy event status
-View or set Away state
-view postal Zip code
-set ETA

##Installation procedure ##

Install the dependencies from npm:

###npm install###
* Install node js
* Install git bash desktop
* Create a folder for placing all the project contents and files.
* Git bash on the empty project folder
* In the git bash command prompt clone this github repository using the following command:
 
 ### 'git clone https://github.com/iyeremuk/nest-cam.git' ### in the nodejs command prompt.
  Since the repository is installed with some missing loadash libraries, we need to run the below command everytime this github           repository is cloned
  ###'npm install'###
 In the VSCode browse open the project folder and locate the files that need to be reprogrammed or edited.
 The whole project can be built and run using the command:
 'ionic serve' from the git bash command prompt of the project folder.
Create a new product using this URL
https://developers.nest.com/products

Create a client product (NestCamera using the following permissions)
* Away read v2
* Camera read v2
* Camera read + images v2*
* Smoke+CO alarm read v4
* Thermostat read v4





