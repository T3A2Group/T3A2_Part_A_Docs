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

### As a customer...

#### Basic functions

- As a customer looking to travel to Tasmania for a holiday, I want easy access to view all available travel packages offered by this resort so that it is easy to view and compare my options.
- As a customer who is interested in a specific travel package, I want to be able to view more details about the package so that I can be informed about what I'm potentially buying.
- As a customer looking to stay at the hotel in Tasmania Resort, I want to book my hotel online so that it is easier to book my holiday.
- As a customer looking to book a hotel room, I want easy access to view all available room types offered by this resort within the specified dates so that it is easy to view and compare my options.
- As a customer who is interested in a specific room type, I want to be able to view more details about the room so that I can be informed about what I'm potentially buying.
- As a customer who likes to gift friends and family souvenirs from trips, I want to be able to purchase souvenirs online incase I forget to buy them or run out of luggage space on the way back home so that I don't go home empty-handed.

#### Account management

- As a customer who is going to make bookings and/or purchases from Tasmania Resort, I want to be able to register for a new account so that I can make and track bookings/purchases.
- As a customer who is going to make bookings and/or purchases from Tasmania Resort, I want to be able to sign in to my account so that I can view my purchases and bookings.
- As a customer who is spontaneous and change travel plans from time to time, I want to be able to edit or cancel my hotel booking so that I can retain my flexible lifestyle without wasting too much money.

#### Cart and Payment

- As a customer who is browsing the website, I want to be able to add items to a cart while I continue to browse so that I don't forget what I was going to buy.
- As a customer who wants to know how much I'm spending, I want to see all the items I'm purchasing and the total cost of these items in the cart so that I can double check before paying.
- As a customer who has trouble making decisions, I want to be able to add/remove the quantity of an item in the cart so that I don't have to be hasseled by navigating through the website again.
- As a customer who is not in Tasmania, I want to be able to make payment online so that I can still purchase the item without being at the resort in person.

### As the manager of Tasmania Resort...

- As the manager who manages the product offerings, I want to be able to add a new product (merchandise/hotel room type) for sale on the website so that they can be sold online when they are launched.
- As the manager who knows when the peak travel seasons are, I want to be able to edit the details (price, description etc...) of the listings so that I can maximise profits for the resort.
- As the manager who oversees the stock level of products/hotel rooms, I want to be able to adjust the availability status of these items so that customers don't accidentally purchase something that is out of stock.
- As the manager who needs to report sales performance to upper level management, I want to be able to see past sales of products and hotel rooms so that I can discuss them with my manager.
- As the manager who wants to ensure the accuracy of product offerings on our website, I want to be able to remove a product/room type from the website so that customers are not disappointed when they can no longer buy the product or book that type of hotel room.

## Wireframes

## Screenshots of Trello Board
