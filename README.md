# _Cipher

#### _An encryption site built with Drupal 7.52_

#### By _**Chris Martinez**_

## Description
_This app's sole purpose is to produce a custom module which will encrypt an inputted string by shifting each letter a number of inputted places, up or down the alphabet._


## Specifications
| Behavior | Input Ex. | Output Ex. |
| --- | --- | --- |
| enter string ("phrase") to encrypt, a shift direction ("right" or "left"), and a shift value, which be the number of places translated through the alphabet (a->z)| Phrase is translated | "a" "right" "1" | "b"|
|many characters can be entered at once an they will all receive the same treatment per use| "buttons and bows"| "cvuupot boe cpxt"|
| spaces and special characters typically used in written language are accepted, but do not get any translated |"buttons & bows" "right" "1"| "cvuupot & cpxt"
|
| other special characters and foreign characters outside of  are not accepted and  the form will not submit| "ß utton & ßows 😊 | "| error message will alert the user|
|only "right" and "left" are acceptable inputs for direction| "kitty-corner"| error message|
|only positive integers greater than 0 are allowed for the shift value| -2.3| error message|



## Setup/Installation Requirements
* _Clone this repository to your desktop_
(https://github.com/cmartinez84/bookstore)
* _Open MAMP and go to Preferences> Webserver>Document Root and navigate to the root folder of bookstore_
* _From your server home page, got to PHPmyadmin>Import> and select the database from bookstore/sites/db_backup (this may take several minutes)_
# _You will need to create a to authenticate the database for use in the project. After the database has been imported, click on the database. Then go to privileges and create a user with the name "cipher" and password "cipher"._
# _To begin using the site, go to localhost:8889_
* _Log in with user name "cipher" and password "cipher" for admin privileges_
* _Click on "Cipher" in the navigation area and enter some values*



## Known Bugs
_None yet_

## Support and contact details
_cardamomclouds@yahoo.com_

## Technologies Used
_php_
_javascript_
_html_
_css_
_MAMP_
_Drupal 7.52_


### License
The MIT License (MIT)

Copyright (c) 2016 **_Chris Martinez_**
