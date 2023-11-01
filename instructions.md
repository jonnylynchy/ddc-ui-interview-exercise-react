# DDC UI Interview Exercise

Welcome. We're glad you're here.

Take the time to read through these instructions.
Talk through your solution and ask questions.

We're here to help you!

## Basic Goal

The goal of this exercise is to request data from a
series of endpoints in order to render a list of vehicles.

The base url for all requests is:
https://api.coxauto-interview.com/api

Steps:

1. Make a GET request to `/datasetId` to retrieve a datasetId.
2. Make a GET request to `/{datasetId}/vehicles` to retrieve a list of vehicle ids.
3. For each `vehicleId` in the list, make a GET request to `/{datasetId}/vehicles/{vehicleid}`
   to retrieve the vehicle information.
4. Display each vehicle's `year`, `make` and `model` in a list.

To preview endpoint responses, feel free to view the Swagger UI:
http://api.coxauto-interview.com/swagger/index.html

## Optional Stretch Goals (in no particular order)

- Use your favorite UI libary or CSS framework to enhance the UI.
- Make a GET request to `/{datasetId}/dealers/{dealerid}`
  to retrieve and display the dealer information.
- Sort by any field(s) (`year`, `make`, `model`, `dealerId`).
- Create sub components.
- Optimize your solution.
