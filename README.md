# Wheels' Fullstack Developer Take-home Project

## Introduction

Hey there! Thanks for your interest in joining our team. The purpose of this project is to test your ability to combine multiple tools and APIs together to build easy to use applications.
Overall the project should take no more than **2 hours**. If you believe you'll be spending more than 2 hours on this project then find an approach that takes advantage of the different frameworks and libraries that are available to you.

## Task

Your task is to build both a backend and frontend that fetch bike-share public location data from the APIs listed below and display the locations of those bikes on a map on the frontend.

#### Backend

Use any language, framework and/or tool that you are comfortable with to create a backend that fetches data from the APIs listed below, concatenates the results and returns it to the frontend. Keep in mind here that all the backend is doing is exposing an endpoint where it makes 4 HTTP requests, concatenates and returns the results.

- https://lax-gbfs.getwheelsapp.com/free_bike_status.json
- https://san-gbfs.getwheelsapp.com/free_bike_status.json
- https://cle-gbfs.getwheelsapp.com/free_bike_status.json
- https://dfw-gbfs.getwheelsapp.com/free_bike_status.json

#### Frontend

Use any language, framework and/or tool that you are comfortable with to create a frontend that makes an HTTP request to your backend to retrieve bike locations and adds those points to a map. The frontend should be very simple, where the only thing required is a map shown with all the bike locations displayed in the map.

Here are some map libraries you can use:

- https://leafletjs.com/
- https://docs.mapbox.com/mapbox-gl-js/example/simple-map/
- https://developers.google.com/maps/documentation/javascript/tutorial

**NOTE**: Some of these require to have an access token. You can create a free account on those platforms to get an access token to use. Consider using best practices when thinking of commiting access tokens to git.

## Submitting

You'll be creating a new Github repository and commiting your project in there. That is the repository we'll be looking at when we evaluate the work that was done. Make sure to commit your code often so we can cleanly see the progress of your work. Even though this test is **not** timed and you can take as little or as long as you need, we encourage you to try and complete it within 2 hours.
