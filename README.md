# Tour App

![Home Screen Golobe Travel Agency](/preview.jpg)

## Overview

Welcome to the repository for Tour App System, your go-to platform for exploring and booking your next travel adventure. This intuitive web interface allows users to search for flights and accommodations effortlessly.



## Technologies used in this project

<img src="https://nextjs.org/favicon.ico" width="16" height="16"> Next js v14

<img src="https://www.mongodb.com/assets/images/global/favicon.ico" width="16" height="16"> MongoDB

<img src="https://tailwindcss.com/favicons/favicon-32x32.png?v=3" width="16" height="16"> Tailwind CSS

<img src="https://redux.js.org/img/favicon/favicon.ico" width="16" height="16"> Redux

<img src="https://authjs.dev/favicon-32x32.png" width="16" height="16"> Next Auth v5

<img src="https://www.gstatic.com/mobilesdk/240501_mobilesdk/firebase_96dp.png" width="16" height="16"> Firebase Cloud Storage

<img src="https://assets.mailjet.com/lib/images/mailjetLogo/mj_logo_only_icon_color.png" width="16" height="16"> Mailjet

## Features

1. Fully Responsive
2. Used redux for state management
3. Used tailwind for styling
4. Flight and Hotel search (dummy data)
5. Filter Flight and Hotel
6. Show flight and hotel details
7. Buy a ticket or book a hotel
8. Get a ticket after buying
9. Sorting search results by best, shortest, and cheapest
10. Add to favorite
11. Login and Signup


### Generate Fake Flight and Related Data for Database

1: To upload it to the database directly after generating it, run the following command:

```bash
npm run generateAndUploadDB
```

2: To generate fake flight and related data and save it in JSON file, run the following command:

```bash
npm run generateDBFiles
```

It should create files in the `generated` directory.

## TODO

This project is still in development. All front-end pages have been developed already but many functionalities especially the backend have not been implemented yet. Here are some functionalities that are yet to develop:

- Replacing fake flight data with real flight API
- Buying tickets and Booking hotel functionality (demo).
- Add payment method form and make it functional.
- Showing histories (i.e. Hotel book, Ticket buy) and added payment methods.
- Adding hotel card to the "/favorites" page
- Download ticket functionality
- Adding admin side for management.