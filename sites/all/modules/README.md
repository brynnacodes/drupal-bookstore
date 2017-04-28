# Corner Bookstore

A drupal website built for a small bookstore in Portland, OR. This site features book reviews, an embedded google map, and user management.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [MAMP](https://www.mamp.info/en/)
* [PHP 5.2.5 or higher](http://www.php.net/)

## Installation

**Step 1**: Clone this repository to your local computer

```console
git clone https://github.com/brynnacodes/drupal-bookstore
```

**Step 2**: Open MAMP and set the web server document root to the project directory

**Step 3**: Start the Apache and MySQL servers

**Step 4**: Navigate to localhost:8888/phpMyAdmin and import the bookstore.sql.zip file into a database with the same name.

**Step 5**: Visit the website at [http://localhost:8888](http://localhost:8888).

## Planning

* Create 2 basic pages - an "About" page, and a "Locations" page.
* Include a Contact form with a "Contact" link in the main menu. Make sure that anyone, regardless of their user role, can use the form to send you website feedback.
* Create features for location, book reviews, and site configuration.
* Create a "Book Review" custom content type. The title field should be labelled "Book Title". It should also include fields for "Book Author", "Rating", and "Review Body".
* Create a View and block for reviews to display the newest three reviews on the home page.
* Create a custom "Reviewer" role. The Reviewer role should have all the same permissions as an authenticated user, and also be able to create new book reviews.
* Create a special coupon to display as a block on the front page which is visible to authenticated users and not anonymous users. It should say something like "This week: use this coupon code to get 25% off on all Science Fiction!"


LICENSE AND COPYRIGHT
---------------------
Copyright Brynna Klamkin-McCarter - 2017 - MIT License
