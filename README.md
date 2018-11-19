# hud - a heads up display for the home
Have a MS Surface Pro 4 laying around most of the day. Gonna mount it on a wall and use this hud as a home interface.

## Design
The main screen will show three things:
* weather (open weathermap api: https://openweathermap.org/api)
* shopping list (not sure what app/datasource i want to use for this. Might build out CRUD w/react and use firebase to sync with our other devices.)
* google calendar (calendar api: https://developers.google.com/calendar/)

## Status
* Did initial mockup and setup data pull from openweathermap.
* Currently: Formatting temps, decidiing on icon sets for various weather conditions.
* Next Up: Dig into why openweathermap's temps differ from weather.com's.