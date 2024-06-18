## Title 
**Hall-Booking API**


## Description:
**API created Using Below End-Points for a Hall Booking Application**

**Render Link is Used to Check the API Endpoints**

**Workspace created API can be checked for Ease of Use**

**https://www.postman.com/rajganez/workspace/hall-booking/request/34103499-7a18c3a0-6eb4-470d-ab86-c3769abd5b49?action=share&creator=34103499&ctx=documentation**


*Creating a Room using Path : "/create-room" and below JSON Objects*

> No. Of Seat Available

> Amenities in Room

> Price for 1 Hour

> Room Name

> Room ID <!---Generated Automatically--->


*Booking a Room using Path : "/book-room/RoomId" and below JSON Objects*

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

*Using API URL :  https://hall-booking-56qy.onrender.com/*

*Above URL Followed by the Above End-Points will fetch required data*

