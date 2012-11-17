Nou-u Test
==========

Hello world!

In order to complete this test you have to follow this steps:

1) Fork this repository
-----------------------

Fork this repository to your computer o just download the source.

Install Symfony2 (follow INSTALL.md instructions).

Create *nou-u_test* database and create the schema:

    php app/console doc:sch:create

Load fixtures:

    php app/console doctrine:fixtures:load


2) Make a reservation
---------------------

We have create three entities for you:

    * Hotel
    * Room
    * Customer

Hotel and Room have an obvious relation between them (OneToMany).

You have to:
    
    * Create a reservation form: a customer would be able to make a reservation (one room)
    * You cannot make a reservation of a room thats already taken (in a range of dates)
    * Store check-in and check-out date for every reservation

3) List
-------

We provide each Hotel a list of their room reservations

You have to

    * Create a list of Hotels with a link
    * The link follow to another page with a list of the hotel's reservation

4) Validate!
------------

To make sure all user data (reservation form) is entered correctly you have to validate both client-side and server-side.
We'll love to see some jQuery action on this task =)

5) Routes
---------

All these pages have to be connected between them (simple link) and all the options will be avaliable on the web index


6) Finish
---------

Send us you public repository link to check the solution, or just email us your source code: jmadrid[at]omitsis[dot]com
You are free to add or modify whatever you like on this sample app.

Good luck! 