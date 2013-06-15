Public Hello World(s) Phonegap Cloud Build
==========================================

Simple Hello world (HTML5 + JS + CSS) examples that use PhoneGap's API and PhoneGap Cloud Build to create iOS Apps


How To & What To
================

1.- Go to build.phonegap.com

2.- Setup a new app to use this repo (I believe you can do so - if not just clone this and use your own)

3.- Setup your own csr, cer, pem, p12 files and create your own mobile provision files (yes you will need to sign up as a developer with apple)

3.1.- Help (Mac & Windows - Windows version can be used in Linux): http://help.adobe.com/en_US/air/build/WS5b3ccc516d4fbf351e63e3d118666ade46-7ff0.html#WSfffb011ac560372f46768d8712cd1d13954-7ffc

4.- Change the index.html file accordingly to build with the different js and css files

5.- Build using phonegap cloud (provide your key files)

6.- Download ipa and send it to your devices for testing

7.- Enjoy


App Config Settings
===================

There are 2 ways:

	1.- Via Phone Gap Build App Settings

	2.- Using a config.xml file (https://build.phonegap.com/docs/config-xml && https://github.com/phonegap/phonegap-start/blob/master/www/config.xml)

	2.1.- Don't forget to check out the current version of the Phone Gap Api (their xml file uses an outdated version)
