## Description
This module contains a basic setup for exposing the postcode.tech API, which takes a postcode and housenumber and returns a full address:

- Street
- City
- Municipality
- Province
- Lat
- Lng

## Typical usage scenario
First go to https://postcode.tech/ and create an account. Once signed up you can create an application in your dashboard which will generate an API Token for you. Put this token in the constant APIKey.

Then add the microflow ACT_Postcode_Simple or ACT_Postcode_Full to any flow where you want to recieve an address for a postcode and housenumber combination. The Full microflow will returns all the values and the Simple will only return a city and streetname.

You can add the SNIP_Postcode_Test snippet to any page where you can test your setup quickly and easily.

## Features and limitations

- Return a full address based on dutch postcode + housenumber
- API limited to 10.000 calls per day
- Completely free