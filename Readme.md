## Title 
**Hall-Booking API**


## Description:
**API created Using Below End-Points for a Hall Booking Application**

**Workspace created API can be checked for Ease of Use**

**https://www.postman.com/rajganez/workspace/hall-booking/collection/34103499-b234716a-8d82-45d5-91a6-1194a1627791?action=share&creator=34103499**


*Creating a Room using Path : "/create-room" and below JSON Objects*

> No. Of Seat Available

> Amenities in Room

> Price for 1 Hour

> Room Name

> Room ID <!---Generated Automatically--->


*Booking a Room using Path : "/book-room" and below JSON Objects*

> Customer Name

> Date

> Start Time

> End Time

> Room ID <!---Passed as a Params denoting a booking made by the customer--->


> Booking Date <!---Automatically Generated when booking is done--->


> Booking Status <!--- After Submitting all details, Is Assigned to Booked --->

*Path : "/rooms" to list all the Booked rooms with below details*

<!---Only Booked Rooms are passed into this API--->

<!---Remaning Rooms can be accessed mentioned in "book-room.js" file--->

> Room Name

> Booked Status

> Customer name

> Date

> Start Time

> End Time

*Path : "/customers" to list all the customers who booked the rooms with below details*


<!---Customer Details with Room name will be displayed--->

> Customer Name

> Room Name

> Date

> Start Time    

> End Time

*Path : "/customers?customer_name = 'customer name'" with below details*


<!---For A Particular Customer Name Data will be fetched--->

> Customer name

> Room Name

> Date

> Start time

> End time

> Booking id

> Booking status

> Booking Date

## In Postman

*Using API URL :  http://localhost:8000/*

*Above End-Points will fetch required data*

