# DT2213-project
Gesture sound mapping using MobMuPlat.
This is the result of a project in the course Musical Communication and Music Technology([DT2213](http://www.kth.se/student/kurser/kurs/DT2213?l=en)) at KTH Royal Institute of Technology, Stockholm.

Written by Simon Johansson, Isak Nilsson and Helga Svala Sigurdardottir.

#2 Description
This is a two-part instrument written in pure data and MobMuPlat. The primary melody instrument generates a synthesized string sound and is controlled by tilting the phone. [Karplus-Strong string synthesis](http://en.wikipedia.org/wiki/Karplus%E2%80%93Strong_string_synthesis) was used to generate the plucked string sound. The secondary rhytmic instrument generates a drum sound and a bass string sound when tilted. The bass sound follows the root chord note of the melody instrument if played with two phones.

TODO - Timbre, etc,

#2 Installation
Download the [MobMuPlat](http://www.mobmuplat.com/) app.
Download and open main.pd and main.mmp from your smart phone.
Open the app, go to the network settings and set the input and output port to the same value (e.g. 54321).
Open the main.mmp file within the app.

#2 Description
#3 Single phone
You can with a single phone either controll the string melody or a simple 
#3 Multiple phones

#2 Disclaimer
The pure data patch is only tested on Android and not OSX.
The MobMuPlat app sometimes crashes for unknown reasons.