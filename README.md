Login Basics
===
Login Basics is an implementation of an Android app that support Login with Facebook, Google Plus (G+) and your own login logic.
The aim of this project is to serve as basis to build apps that require login as a feature.

Screenshots
-------
<a href="url"><img src=./art/Screenshot_2015-10-22-15-50-10.png height="550"  ></a>
<a href="url"><img src=./art/Screenshot_2015-10-22-15-50-24.png height="550"  ></a>
<a href="url"><img src=./art/Screenshot_2015-10-22-15-50-34.png height="550"  ></a>
<a href="url"><img src=./art/Screenshot_2015-10-22-15-54-04.png height="550"  ></a>
<a href="url"><img src=./art/Screenshot_2015-10-22-15-54-47.png height="550"  ></a>


Steps
-------
In order to make the project ready for your app you need to:

Facebook
-------

- Create an Facebook app at https://developers.facebook.com/apps/;
- Replace the value of facebook_app_id at strings.xml;
 

Google
-------
- Go to the Google Developers Console at https://console.developers.google.com/ and create a new project (or get to one you already have);
- In the left sidebar, select APIs & auth (the APIs sub-item is automatically selected) find the Google+ API and set its status to ON;
- Get a configuration file at [Google Developers](https://developers.google.com/mobile/add?platform=android&cntapi=signin&cnturl=https:%2F%2Fdevelopers.google.com%2Fidentity%2Fsign-in%2Fandroid%2Fsign-in%3Fconfigured%3Dtrue&cntlbl=Continue%20Adding%20Sign-In) by:     
		a) Select the correct project and package then click on Continue;    
		b) Click the button on the bottom to Generate configuration files    
		c) Download the google-services.json for your app and put it at the app/ or mobile/ module directory in your Android project. (The file contains configuration details, such as keys and identifiers, for the services you just enabled)
		
Own Logic
-------
- Replace the code at doInBackground on UserLoginTask at the LoginActivity to your own logic;
- Be happy :)

Me
-------
André Batista da Silva
* LinkedIn [andrebts](https://br.linkedin.com/in/andrebts)
* andrebtsa@gmail.com

License
-------
    Copyright (C) 2015 andrebtsa
    Copyright (C) 2013 The Android Open Source Project

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.