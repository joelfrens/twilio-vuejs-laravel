### A web app using Twilio Vuejs and Laravel

## This is an experimental package and should be used at your own risk!!!

# Setup

The app is built using the following Frameworks
- Laravel 7
- VueJs 
- Twilio PHP SDK https://github.com/twilio/twilio-php

Set the following environment variables in your Laravel .env file
```
TWILIO_APP_ID=YOUR TWILIO APP ID
TWILIO_APP_TOKEN=YOUR TWILIO TOKEN
TWILIO_APP_TWIML=YOUR TWILIO TWIML ID
```

To get your Twilio Id and Twilio token, create a Twilio account and go here https://www.twilio.com/console

To get your Twiml Id, Create a Twiml app here https://www.twilio.com/console/voice/twiml/apps

# Testing

```
php artisan test
```
