The purpose of this application is to provide an interface allowing easier management of a file platform. 

Features
========

* Create users with according home spaces with a generated password in one click. Delete them easily too.
* Users have access only to their space, and nothing else.
* Keep passwords in a secured macro (thanks to the Encryption Application macro).
* List users with an overview of space taken by the uploaded attachments
* A scheduler job can automatically clean attachements older than 2 months (possibility to add exclusions).
* Support of english and french languages.

 Warning : This package is bundled with a customized XWikiPreferences to set rights and colortheme, it will overwrite any existing preference.

Prerequisites
============

 * Filesystem Storage needs to be enabled.
 * This application needs the Encryption Application to be installed to safely store the users. password inside a wiki page.

Installation
============

We recommend using the Extension Manager to install this extension (Make sure that the text "Installable with the Extension Manager" is displayed at the top right location on this page to know if this extension can be installed with the Extension Manager).

You can also use the following manual method, which is useful if this extension cannot be installed with the Extension Manager or if you're using an old version of XWiki that doesn't have the Extension Manager:

* Log in the wiki with a user having Administration rights
* Go to the Administration page and select the Import category
* Follow the on-screen instructions to upload the downloaded XAR
* Click on the uploaded XAR and follow the instructions


 * This application has been tested with XWiki 5.4.x only.
