# _Bookstore Website_

#### _Drupal Week 1 code review, 4-22-16_

#### By _**Matt Knutson**_

## Description

_This weeks code review focused on site building with Drupal.  No coding was necessary.  The focuse was on using core and contrib modules and the creation of features for feature tracking._

## Setup/Installation Requirements

* Git clone <repository-url> this repository
* Change into the new directory
* Open MAMP, click on preferences-> Web Server->Document Root
Select the project directory.
* Start the Servers.
* In your browser, navigate to: http://localhost:8888/phpMyAdmin/
* Import the database that is located in the sites/all/db-backup called bookstore.sql(3).zip (The name of the database is: bookstore).
* Once the database is successfully downloaded, click on it on the far left of the screen, and find the tab at the top of the screen called 'Privileges'.
* Add the following user: User name: matt
* Change host to: localhost
* Password: Matt
* click 'go'
* User1 for the Drupal site: username: matt | password: matt
* There is also a reviewer user who can add reviews and edit their reviews as per the requirements
* Username: reviewer | password: matt

## Known Bugs

_None at this time_

## Support and contact details

_Contact Matt Knutson via Github with any issues_

## Technologies Used

* Drupal
* MAMP
* Contrib Modules:
- Views
- Strongarm
- DIFF
- Sweaver
- Features
- Ctools

### License

*This software is licensed under the MIT license.*

Copyright (c) 2016 **_Matt Knutson_**
