# _Bookstore Website_

#### _Drupal Week 1 code review, 4-22-16_

#### By _**Matt Knutson**_

## Description

_This weeks code review focused on site building with Drupal.  No coding was necessary._

## Review Requirements:

* Did you create a "Book Review" custom content type? Are the fields named correctly and in the correct order?_
* Is there an "About" page and a "Locations" page?
* Is there a Contact form with a "Contact" link in the main menu?
* Are the 4 "Book Review" fields all set to required? Does the rating field use either radio buttons or a menu?
* Did you create the "New Books" view and display it as a block?
* Did you create a feature for the "Book Review" content type and the "New Books" view?
* Did you create the "Reviewer" role and assign it the correct permissions?
* Did you create the coupon block on the front page and make it only visible to authenticated users?
* Is there a "Site Configuration" feature tracking the specified Strongarm variables? Did you make changes and then recreate your "Site Configuration" feature?
* Are you able to discuss the process you used for your project and the concepts behind it with an instructor using correct terminology?
* Did you export your database at the end of your project and include it with your repository with login information in a clear readme?

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
