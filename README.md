# gmail-notifier
Python script for Gmail and the [Dream Cheeky Webmail Notifier](http://dreamcheeky.com/webmail-notifier)  based around [WebMail Notifier Linux driver](https://github.com/danielkaefer/usblamp)

## Setup

Be sure to create a API project in the [Google Developer Console]((https://console.developers.google.com/apis/), enable the gmail API's and download the credential file to the project folder as `client_secret.json`. 

Also be sure to build and install the [Webmail Notifier Linux driver(https://github.com/danielkaefer/usblamp) (though it says for Linux I have built this on OSX 10.11.4 with the addution of the `libusb` package available from [homebrew](http://brew.sh/)).

## Running

You can run the tool simply with `$ python notifier.py`. The first time you run this you will be directed to sign in with your Google account allowing the tool access to your account. After this the till will run on its own with no further input required.

##License
This tool is protected by the [GNU General Public License v2](http://www.gnu.org/licenses/gpl-2.0.html).

Copyright [Jeffrey Hann](http://jeffreyhann.ca/) 2016
