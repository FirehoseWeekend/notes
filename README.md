Firehose Weekend Notes
=====

Friday Night
----------

**Verifying the Installation works**
* Command: `ls` (This is lowercase L)
  * list sub directories
* `cd Desktop`
  * change directory to Desktop
* `mkdir`
  * Make a directory within this directory
  * Make "Firehose" directory
* Create basic template
  * `rails new weekend_app`
    * Be sure to change the directory into Firehose first so that this is a sub-directory inside of Firehose
* Click on the weekend_app folder and drag on to sublime
* Run rails server (inside the directory where app is located)
  * `rails s`
  * Then copy the http piece in the dump in Terminal and paste into browser
    * http://0.0.0.0:3000 (this is what was in the dump after I put in the “rails s” command)
  * Do Control-C in Terminal to exit the server
    * Need to exit the server in order to continue to put commands into Terminal
    * When you exit the server, then the app stops working.  So if you refresh your browser, you will get an error that your apps is not working.  App is fine, just restart the server.

