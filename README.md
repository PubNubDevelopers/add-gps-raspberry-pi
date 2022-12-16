# Add GPS to Your Raspberry Pi Project with Google Maps and PubNub

:warning: **This tutorial is out of date**: While some information may not be completely up to date, this article still contains some useful insights into into setting up and retrieving GPS coordinates using a Raspberry Pi and GPS module all in real time with PubNub. You can learn more about how PubNub powers [thousands of customers worldwide](https://www.pubnub.com/customers/) in our [PubNub for Developers](https://www.pubnub.com/developers/) resources. Have suggestions or questions about the content of this post? Reach out to devrel@pubnub.com. :warning:

This repository contains the source code for the [tutorial](https://www.pubnub.com/blog/raspberry-pi-gps-lte-google-maps-api/) that instructs developers how to add GPS capabilities to a Raspberry Pi (RPi) with a GPS Module Breakout written in Python, which is used as the GPS receiver to obtain information. This hardware will act as the GPS device to retrieve GPS coordinates. To power the functionality of GPS, you'll use PubNub's Geolocation APIs via the [PubNub Python SDK](https://www.pubnub.com/docs/sdks/python).

## Environment Setup

Please follow the environment set up in the [written tutorial](https://www.pubnub.com/blog/raspberry-pi-gps-lte-google-maps-api/) on PubNub's website, as it details how to set up the hardware for this tutorial, as well as the configuration of the software and code to power this application.

## PubNub Account & Functions
* You’ll need free API keys from PubNub to be able to see the GPS information update in real time. To get these keys:
* Sign up for a [PubNub account](https://dashboard.pubnub.com/signup/). 
* Go to your PubNub Dashboard.
* Click Create New App and give your app a name.
* Click Create.
* Click your new app to open its settings, then click its keyset.
* Enable Presence and Message Persistence.
* Save the changes.
* Copy the Publish and Subscribe keys to a text editor for the next steps.

## Build & Run
After following the [written tutorial](https://www.pubnub.com/blog/raspberry-pi-gps-lte-google-maps-api/) and replacing your Google Maps API key and PubNub Publish/Subscribe keys, save your work and double-click the HTML file to open it in your default web browser. You'll be able to visually see the GPS information retrieved by your Raspberry Pi and GPS module in real time.

## Links
- PubNub Account: https://admin.pubnub.com/#/login
- Python SDK: https://www.pubnub.com/docs/sdks/python
- Tutorial Link: https://www.pubnub.com/blog/raspberry-pi-gps-lte-google-maps-api/

## License
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
