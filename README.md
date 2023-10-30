# Hibachi-Reservations
Koto Hibachi Reservation Program

https://youtu.be/bpkGEpV3wuo


-How to use Koto Reservations-

To begin using Koto Reservations, the user should download into VSCode the zip file we provided, then unzip the file. In this folder, you should see app.py, helpers.py, tables.db, and a templates file consisting of 6 html pages. Make sure to move into this directory before running the application. Once in the directory, the user should run the “flask run” command to configure the application. From there, one can use the server given to arrive at our website.

The link will take you to our home page, which lists all the current reservations, organized by time. To place a reservation, the host/hostess should go to the “Check Availability” tab and input the date and number of people in the party. The dates only take Friday and Saturday because in the restaurant, those are the busiest days and require the most checking to make sure seats/tables work out (to the extent that hibachi reservations aren’t often recorded for other days). Once you press “Submit”, the website will check for times where tables are available, and redirect you to a “Submit Reservations” page. This page displays all the times that the reservation is available.

Once at the “Submit Reservations” page, the user will see a list of available times. The host/hostess should then input the name corresponding to the reservation and choose a time that best fits the customer and restaurant’s schedule. Press submit.

Delete Reservations allows the user to delete previous reservations that have been made. This is done by entering the correct name, date, time, and number of people into the Delete Reservations tab. If successful, the reservations will be removed from the SQL database as well as the days dictionary. The user will then be redirected to the home page. Otherwise, the website displays an apology that the reservation does not exist.
