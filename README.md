# T3A2-A - Tasmania Resort Online Platform

## Purpose

## Functionality / features

### Functionality
#### User management
1. This application will allow users to create their own accounts to save all their profiles.

2. User will have their own group. Staff and customer accounts will have different pages to let them use the application differently.

<!-- Show the schedule. -->
3. The user could open their own profile page to show the history of purchase and booking. And show/download the schedule of their booking.

<!-- Keep feedback. -->
4. The user could leave their opinion or suggestion after they purchase the item. And the website will display them.

5. The user could freely change their password and upload their own profile picture. (need to save the pic on the cloud -s3)

6. Users have to log in before they purchase the item, so they will save purchase history.

If we have time :

1. Staff accounts will have their own page to work on.

<!-- Guests with different VIP levels have different discounts. -->
2. Customer accounts will have different VIP levels to get discounts or free services.

3. Staff accounts could send messages to other staff or leave group chat notices through this application.

<!-- Booking room online -->
#### Booking room online
1. This application will allow user to book their room online.

2. It will display all the available rooms with price and every kind of room will have its own detail pages.

3. Each room can only book once at the same time.

4. When customers book a room it will let them choose the time they want to stay and filter the available rooms.

5. It will have the payment function to organize the payment.

If we have time :

1. It will have the webhook to ensure the payment is successful.

2. Every time when the room is booked we should let staff confirm. The booking will be done whenever the staff confirms the booking.

<!-- Chef prepare list. -->
3. The application should show the staff how many rooms are used in the next few days and it should give the chef the number of people, to help them prepare the food.

<!-- Sell souvenirs online. -->
####  Online souvenirs shopping:
1. This application allows users to buy souvenirs online. 

2. It will display all the items on the webpage and each item will have the product details page/pop-up.

3. It will have a cart page to organize the purchase of products.

<!-- Online Checkout. -->
4. It will have the payment function to organize the payment.

If we have time :

1. It will have the webhook to ensure the payment is successful.

<!-- Choose your food. -->
#### Food services

1. This application allows the user to choose or order their food when they are in the hotel.

2. It should display menu to show customer witch kind of dishes is available.

3. It will have the payment function to organize the payment.

If we have time :

4. It will have the webhook to ensure the payment is successful.

5. It should give the staff or chef a message to show when and what the customer ordered. And chef could use the application to ensure the food is finished prepared and sent to the correct customer.

#### Booking the nearby tour

1. This application could show the available tour nearby. 

2. Each tour lane will have its own number limit and start/end time. Customers could book anyone they are interested in.

3. Online checkout and webhook confirmation

If we have more time:

1. Use API check the upcoming weather.

### Features
1. Online shopping.
    - Display the whole items and each item have its own details page.
    - Staff could Update/Delete the items and change the quantity.
    - Cart to let customers organize their purchases.
    - Users could check out online.

2. Display filter / search
    - Booking page will have the time and price filler.
    - All shopping pages will have a search bar to search the items or services.

3. Sign up and login
    - User could sign up by using a unique email.
    - User could log in by using email/username + password.
    - User could change and update their password.
    - User could upload their profile picture to the cloud and use them.
    - User could leave feedback and they will display with the item/services.
    - If we have more time, the User could use a google account to log in.

4. Role Control
    - Every user will have their own role. For example Customer, staff (admin, chef, front desk if we got time).
    - Staff account should be able to add, access, update and delete the item showing on the application.
    - Customer account could only access.

5. Cloud save pictures
    - User uploads the picture to the could use them as profile pictures.
    - Staff cloud use upload to change the display picture for each item. This picture should save in the cloud as well.

6. Payment and webhook.
    - Application should let the user have the online payment. (PayPal, Strip...)
    - Should have the webhook to track whether the payment is successful or not.

7. Display/ download the schedule for user/staff.
    - Customer should display their purchase history and the schedule for the purchases.
    - Staff should display their message for the purchases. Like, confirm room booking, food order and tour booking.
    - If we have time we could format them to pdf and be able to download them.

8. Send messages through the application
    - If we have time we could build an application chat feature.
    - It allows customers could leave messages to staff and get askers. 
    - It allows staff to talk with each other and have group chat areas.

## Target Audience

## Tech stack

## Dataflow Diagram

## Application Architechture Diagram

## User Stories

## Wireframes

## Screenshots of Trello Board
