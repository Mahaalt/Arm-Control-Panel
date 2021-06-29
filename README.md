# Arm Control Panel Interface

I preferred to separate the files to make the code more organized.

---------------------------------------------------------------------------------------------------------

At first, I made an index file that contains the external structure of the page.

I linked it to the index.php page via the form command.

---------------------------------------------------------------------------------------------------------

The index.php page is the one that sends the slider, on and off data to the database.

To access the database, I created a dp_conn.php page, Which contains the host information.

---------------------------------------------------------------------------------------------------------

main.js file contains javascript code to make the page more interactive.

The appearance of sliders numbers and their changing according to the change of the slider is part of its work.

---------------------------------------------------------------------------------------------------------

style.css to arrange and format the interface.

---------------------------------------------------------------------------------------------------------

The robfighter.sql file is a database file that contains two tables.

The first table called motor contains an IDM column, and MValue column to store the motor values after pressing the save button in the interface.

The second table, called switch, contains an IDS column, and an SValue column, which contains 'ON' and 'OFF' buttons and a value of either one or zero.

The point of these two numbers is that zero means closed and one means open.

For example, when you press the 'ON' button, the value of on will be updated in the database and change from zero to one, and the value of the 'OFF' button will also be changed to zero instead of one and vice versa.

---------------------------------------------------------------------------------------------------------

finally,
I aspire to continue to develop this interface and make it more beautiful, smooth, and suitable for all devices
