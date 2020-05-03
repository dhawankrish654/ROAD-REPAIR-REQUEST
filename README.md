**[\# Image-Based-Road-Repair-Android-Application]{.underline}**

**A may be BOON for the PWD department of our country for the management
of roads.**

I started building this application firstly as a project for my college
stuff but during the built I realised the fact that this application
could serve as a boon for the country's Public Works Department for
management of roads. India is a country with the second largest road
network in the world. Out of the total stretch of 5.4 million km of road
network, almost 97,991 km
is covered by national highways. It is already a huge challenge for the Indian
government to provide world-class roads, due to the sheer magnitude. To
add to it, India has to spend almost around ₹20,000 to ₹30,000 crore on
the maintenance of roads every year. Contributing to this problem, this
android based application may surely serve the country better if used
nation and may also reduce the total amount of wealth wasted for the
same purpose.

Starting with the explanation, Its an Android application with a Google
Firebase Realtime Database management system with a multiple user
interface. The local people of the country are our basic customers whom
we are serving and the PWD authorities are the administrator to this app
.The admin has launched repair vehicles through out the city with valid
driver authentication in the app for the repair of roads tracked via GPS
.The customer if anywhere wants to report a pit or a pothole in a road
may login into the app under the customer's section and report to the
nearest found driver and send the phots and description of the condition
of a road. The nearest driver would be alerted and navigated upto the
site. As soon as the repair work is completed the driver would take a
photograph of the completed work for assurance and update in the
application and the customer request would be dumped with him/her being
alerted that request has been fulfilled along with the photograph .
Thats the complete working of my application in a nutshell. Further are
some other details of the app and requirements, how to implement it.

The API's that have been used in this project are-

-Google Maps and Directions Api

-Google FireBase authorization and storage

-GLIDE API

The [Requirements]{.underline} to run this project are-

A GOOGLE MAPS API KEY GOOGLE FIRSEBASE ACCOUNT WITH STORAGE, REALTIME
DATABSE AND AUTHORIZATION (Email & Password in my case), GOOGLE
DIRECTION API KEY AND A MINIMUM SDK VERSION OF 23.

The working with snapshots of the application is explained below.

Firstly someone has to download the latest version of Android Studio
i.e. 3.6 and clone the repo or download the project and extract it.

![](.//media/image1.jpeg){width="3.171527777777778in" height="4.0625in"}

(The landing page of the application where the user has to select
his/her role)

The PWD department authorised persons should download this app and
create a firebase account and link this particular application to that.
Then activate the realtime databse and authorization of users with any
liked format(Email password int his case or mobile otp verification).

The second duty of the department is too create and provide user ids and
password for the repairing agents so that they could locate the site of
repair. Then the drivers should download the app and login under the
agents section and set out through out the city with repair workers.

![](.//media/image2.jpeg){width="2.2604166666666665in"
height="2.5625in"}

(The login/registration page for the customer/agents.)

The details of a particular driver would be reflected in the firebase
database as shown under the drivers available section.

User Interface- the local user or the local public may download the
application and login under the customer section. As soon as they locate
a wreck in the road anywhere they can press the required button as shown
and the customer request would pop up on the database as shown. The
request would be raised upto the nearest driver(with the details and
photos of the site) available and the customer would have too update the
photo of the condition too with his/her details so that they can be
delivered to the driver.(CUSTOMER INTERFACE SHOWN BELOW)

![](.//media/image3.jpeg){width="3.2708333333333335in"
height="3.4789009186351705in"}
![](.//media/image4.jpeg){width="3.0729166666666665in"
height="4.4375in"}

![](.//media/image5.jpeg){width="3.439990157480315in"
height="6.114583333333333in"}

(Driver's interface after receiving a request)

Once a driver gets a request he would shift under the drivers working
criteria the database and set out for the location with complete map
guidance and start the repair work.

![](.//media/image6.png){width="6.268055555555556in" height="4.21875in"}

(Firebase Realtime Database)

Once completed, the driver has to update the customer with the photo of
the completed site so that the customer request is dumped from the
server.

**So this was the complete working of the application and considering
some more ideas, this application could surely help us all in other ways
too. For example in a taxi driving app , crime vehicle app , waste
collection app and much more. Please give it a try download it and run
it following the above steps and commit your changes and please
appreciate it by giving a star.**

**Thank you....**
