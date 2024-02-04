# Post Office Near You

## Overview
We will be able to see a list of post offices our pincode.It will Map and show all the post offices available in that area.
Also a search box that can filter the postal offices by name and branch office is available.

## Features

- Get user's IP address on page load.
- Make an API request to `https://ipapi.co/${IP}/json/` to gather information about the user.
- Display the user's location on a Google Map using the latitude and longitude obtained from the API.
- Retrieve the user's time zone from the API response and display the current time in that time zone.
- Send a GET request to `https://api.postalpincode.in/pincode/${pincode}` using the pincode obtained from the API to get a list of post offices.
- Map and display all the post offices available in that area.
- Implement a search box to filter post offices by name and branch office.


## Usage

1. Open the project in a web browser.
2. The user's IP address will be displayed on page load.
3. Click the button to fetch additional information from the API.
4. The user's location will be shown on the Google Map.
5. The current time of the user's location will be displayed based on the time zone obtained from the API.
6. Use the search box to filter post offices by name and branch office.

## APIs Used

- [GeeksforGeeks - Get Client IP Address](https://www.geeksforgeeks.org/how-to-get-client-ip-address-using-javascript/)
- [ipapi - IP Location API](https://ipapi.co/)
- [Google Maps API](https://developers.google.com/maps/documentation/javascript/overview)
- [usefulangle - JavaScript Get Date Time for Timezone](https://usefulangle.com/post/382/javascript-get-date-time-for-timezone)
- [Postal PIN Code API](https://api.postalpincode.in/)

## Deployed Link

You can check the project with the help of the deployed link here

[Deployed Project](https://sidd444.github.io/Post-Office-near-you/)
