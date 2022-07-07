# T3A2-A - Tasmania Resort

## Purpose

Our client Tasmania Resort, came from humble beginnings and has now grown into a successful and diverse business, offering services to people who are looking for a one-stop shop travel solution for Tasmania.

In order to keep up with their ever-growing customer demand and tap into the online market, Tasmania Resort has approached us to design and build a full-stack web application to bring their business online. As such, the purpose of this website is to provide an online platform as a digital solution to enable the delivery of their offerings to customers everywhere.

The website will offer everything a customer could need for the trip such as researching the tourist destinations to plan their trip and get inspiration, purchasing local products and food, and booking accommodation and tour packages. It will also feature an easy to use online payment system to allow customers to make purchases from anywhere, anytime.

Additionally, administrative functions such as product and order management can be provisioned to staff accounts to provide a fully integrated solution for the resort.

## Functionality / features

### Functionality

<details>
  <summary> User management </summary>

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

</details>

<!-- Booking room online -->
<details>
  <summary> Booking room online </summary>

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

</details>

<!-- Sell souvenirs online. -->
<details>
  <summary> Online souvenirs shopping </summary>

1. This application allows users to buy souvenirs online.

2. It will display all the items on the webpage and each item will have the product details page/pop-up.

3. It will have a cart page to organize the purchase of products.

<!-- Online Checkout. -->

4. It will have the payment function to organize the payment.

If we have time :

1. It will have the webhook to ensure the payment is successful.

</details>

<!-- Choose your food. -->
<details>
  <summary> Food services </summary>

1. This application allows the user to choose or order their food when they are in the hotel.

2. It should display menu to show customer witch kind of dishes is available.

3. It will have the payment function to organize the payment.

If we have time :

4. It will have the webhook to ensure the payment is successful.

5. It should give the staff or chef a message to show when and what the customer ordered. And chef could use the application to ensure the food is finished prepared and sent to the correct customer.

</details>

<details>
  <summary> Booking the nearby tour </summary>

1. This application could show the available tour nearby.

2. Each tour lane will have its own number limit and start/end time. Customers could book anyone they are interested in.

3. Online checkout and webhook confirmation

If we have more time:

1. Use API check the upcoming weather.

</details>

### Features

<details>
  <summary> Online shopping </summary>

- Display the whole items and each item have its own details page.
- Staff could Update/Delete the items and change the quantity.
- Cart to let customers organize their purchases.
- Users could check out online.

</details>

<details>
  <summary>  Display filter / search </summary>

- Booking page will have the time and price filler.
- All shopping pages will have a search bar to search the items or services.

</details>

<details>
  <summary>  Signup and Signin </summary>

- User could sign up by using a unique email.
- User could log in by using email/username + password.
- User could change and update their password.
- User could upload their profile picture to the cloud and use them.
- User could leave feedback and they will display with the item/services.
- If we have more time, the User could use a google account to log in.

</details>

<details>
  <summary>  Role Control </summary>

- Every user will have their own role. For example Customer, staff (admin, chef, front desk if we got time).
- Staff account should be able to add, access, update and delete the item showing on the application.
- Customer account could only access.

</details>

<details>
  <summary>  Cloud save pictures </summary>

- User uploads the picture to the could use them as profile pictures.
- Staff cloud use upload to change the display picture for each item. This picture should save in the cloud as well.

</details>

<details>
  <summary> Payment and webhook. </summary>

- Application should let the user have the online payment. (PayPal, Strip...)
- Should have the webhook to track whether the payment is successful or not.

</details>

<details>
  <summary> Display/ download the schedule for user/staff. </summary>

- Customer should display their purchase history and the schedule for the purchases.
- Staff should display their message for the purchases. Like, confirm room booking, food order and tour booking.
- If we have time we could format them to pdf and be able to download them.

</details>

1. Send messages through the application
   - If we have time we could build an application chat feature.
   - It allows customers could leave messages to staff and get askers.
   - It allows staff to talk with each other and have group chat areas.

## Target Audience

This website is aimed at people who are looking for a one-stop shop travel solution for Tasmania with service offerings including accommodation, food, tours and shopping. The website is also for staff members at Tasmania Resort to perform operational tasks such as the management of product listings etc...

## Tech stack

### Front-end

- HTML, CSS, Javascript, React, Axios, Material-UI

### Back-end

- Node.js, Express.js

### Database

- MongoDB, mongoose, AWS S3

### Testing

- Jest

### Deployment

- Heroku

## Dataflow Diagram

![Level 0 and level 1](src/dataflow_1.jpeg)
![Level 2 logic 1 2 3 4](src/dataflow_2.jpeg)
![Level 2 logic 7](src/dataflow_5.jpeg)

## Application Architechture Diagram

![Architechture Diagram](./src/App-Architecture-Diagram/Tasmania-Resort-Architecture-Diagram.drawio.png)

## User Stories

### As a customer...

<details>
  <summary> Accommodation, food, local products & tour packages </summary>

- As a customer looking to stay at the hotel in Tasmania Resort, I want to book my hotel online so that it is easier to book my holiday.
- As a customer looking to book a hotel room, I want easy access to view all available room types offered by this resort given the specified dates so that it is easy to view and compare my options.
- As a customer who is interested in a specific room type, I want to be able to view more details about the room so that I can be informed about what I'm potentially buying.
- As a customer who likes to gift friends and family souvenirs from trips, I want to be able to purchase souvenirs online incase I forget to buy them or run out of luggage space on the way back home so that I don't go home empty-handed.
- As a customer looking to purchase some souvenirs, I want easy access to view all available souvenirs offered so that it is easy to view and compare my options.
- As a customer who is interested in a specific souvenir, I want to be able to view more details about the product so that I can be informed about what I'm potentially buying.
- As a customer looking to travel to Tasmania for a holiday, I want easy access to view all available tour packages offered by this resort so that it is easy to view and compare my options.
- As a customer who is interested in a specific tour package, I want to be able to view more details about the package so that I can be informed about what I'm potentially buying.
- As a customer who wants to dine at the resort, I want to be able to order food online so I can beat the rush at the restaurant.
- As a customer looking to order some food, I want easy access to view all available food offered so that it is easy to view and compare my options.
- As a customer who is interested in a particular dish, I want to be able to view more details about the dish so that I can be informed about what I'm potentially ordering.
- As a customer looking to book a room/make a purchase, I want to be able to search for what I need so that only items matching my search criteria are shown to me.

</details>

<details>
  <summary> Account management </summary>

- As a customer who is going to make bookings and/or purchases, I want to be able to register for a new account so that I can make and track bookings/purchases.
- As a customer who is going to make bookings and/or purchases, I want to be able to sign in to my account so that I can view my purchases and bookings.
- As a customer who has an account, I want to be able to change my password whenever required so that I can retrieve my account even if I forget the current password.
- As a customer who has an account, I want to be able to upload a picture to use as my profile picture so that I can make my account more tailored to me.

</details>

<details>
  <summary> Cart and Payment </summary>

- As a customer who has never bought from/stayed at Tasmania Resort before, I want to see reviews from previous customers to help guide me make a better decision.
- As a customer who is browsing the website, I want to be able to add items to a cart while I continue to browse so that I don't forget what I was going to buy.
- As a customer who wants to know how much I'm spending, I want to see all the items I'm purchasing and the total cost of these items in the cart so that I can double check before paying.
- As a customer who has trouble making decisions, I want to be able to add/remove the quantity of an item in the cart so that I don't have to be hassled by navigating through the website again.
- As a customer who is making a purchase/booking, I want to be able to make payment online so that I can still purchase the item without being at the resort in person.

</details>

<details>
  <summary> After purchase/booking </summary>

- As a customer who is spontaneous and changes travel plans from time to time, I want to be able to edit or cancel my hotel booking so that I can retain my flexible lifestyle without wasting too much money.
- As a customer who has made a purchase/booking, I want to be able to check the status of my order (i.e. Order/booking pending, order/booking confirmed etc...) so that I can manage my expectations.
- As a customer who has made a purchase/booking, I want to be able to leave comments on purchases that I've made or hotel rooms that I stayed in so that I can express my opinion and share my experience.

</details>

### As the manager of Tasmania Resort...

- As the manager who needs to delegate tasks, I want to be able to assign administration access to staff accounts so that they can perform administrative tasks such as editing product details.
- As the manager who manages the product offerings, I want to be able to add a new product (merchandise/hotel room type) for sale on the website so that they can be sold online when they are launched.
- As the manager who oversees the sales process, when a customer makes a purchase/books a room, I need to be able to confirm the sale before it is processed to ensure we don't overbook the hotel or oversell products.
- As the manager who knows when the peak travel seasons are, I want to be able to edit the details (price, description etc...) of the listings so that I can maximise profits for the resort.
- As the manager who needs to report sales performance to upper level management, I want to be able to see past sales of products and hotel rooms so that I can discuss them with my manager.
- As the manager who needs to ensure the accuracy of product offerings on our website, I want to be able to remove a product/room type from the website so that customers are not disappointed when they can no longer buy the product or book that type of hotel room.

### User stories for extra features if time allows

- As a customer who has questions regarding a product, I want to be able to live chat with a staff member so that my issue can be resolved as soon as possible.
- As a customer who has visited the resort many times, I want to be a part of a rewards program so that I can receive discounts for being a loyal customer.

## Wireframes

<details>
  <summary>Home Page</summary>

- #### Home Page (no need login)
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Home-Component/Home-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Home-Component/Home-Component-T&M-Version.png)

</details>

<details>
  <summary>Products Page</summary>

- #### Our Villas Page (no need login)
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Products-Components/Resort-Lists/ResortProducts-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Products-Components/Resort-Lists/ResortProducts-Component-T&M-Version.png)

- #### Our Specialties Page (no need login)
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Products-Components/Specialty-Lists/SpecialtyProducts-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Products-Components/Specialty-Lists/SpecialtyProducts-Component-T&M-Version.png)

- #### Our Restaurant Page (no need login)
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Products-Components/Food-Lists/FoodProducts-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Products-Components/Food-Lists/FoodProducts-Component-T&M-Version.png)

- #### Our Travel Page (no need login)
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Products-Components/Travel-Lists/TravelProducts-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Products-Components/Travel-Lists/TravelProducts-Component-T&M-Version.png)

</details>

<details>
  <summary>Each Product Page</summary>

- #### Each Villa Page (no need login)
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Product-Component/Each-Villa/EachVilla-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Product-Component/Each-Villa/EachVilla-Component-T&M-Version.png)

- #### Each Specialty Page (no need login)
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Product-Component/Each-Specialty/Each-Specialty-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Product-Component/Each-Specialty/Each-Specialty-Component-T&M-Version.png)

- #### Each Food Page (no need login)
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Product-Component/Each-Food/Food-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Product-Component/Each-Food/Food-Component-T&M-Version.png)

- #### Each Travel Page (no need login)
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Product-Component/Each-Travel/TravelProduct-Components-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Product-Component/Each-Travel/TravelProduct-Component-T&M-Version.png)

</details>

<details>
  <summary>Signin and Signup Page</summary>

- #### User signin and signup Page
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Signin-Signup-Component/Auth-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Signin-Signup-Component/Auth-Component-T&M-Version.png)

</details>

<details>
  <summary>Checkout Page</summary>

- #### After Signin, user can checkout
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Checkout-Component/CheckOut-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Checkout-Component/CheckOut-Component-T&M-Version.png)

</details>

<details>
  <summary>Client Profile Page</summary>

- #### Client Profile
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Client-Profile-Component/Client-Profile-Component-Desktop-Version.png)
- Tablet and Mobile Version
  ![Tablet & Mobile Version](./src/Tasmania-Resort-Wireframes/Client-Profile-Component/Client-Profile-Component-T&M-Version.png)

</details>

<details>
  <summary>Admin Profile Page</summary>

- #### Admin Profile
- Desktop Version
  ![Desktop Version](./src/Tasmania-Resort-Wireframes/Admin-Component/Admin-Account-Component-Desktop-Version.png)
- Tablet Version
  ![Tablet Version](./src/Tasmania-Resort-Wireframes/Admin-Component/Admin-Account-Component-Tablet-Version.png)
- Mobile Version
  ![Mobile Version](./src/Tasmania-Resort-Wireframes/Admin-Component/Admin-Account-Component-Mobile-Version.png)

</details>

## Screenshots of Trello Board
