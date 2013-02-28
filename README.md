maxmind-ipgeolocate-google-maps-with-directions
===============================================

A mash-up I created using MaxMind IP Geolocation and Google Maps to deliver automatic driving directions and maps from the visitor's approximate location to a destination of your choosing. 

## Pre-requisites:
  - A Google Maps API key.
  - Agreement to the MaxMind Terms of Service.


## Installation
  1. Upload demo.html to your webserver.
  2. Replace the API key Portion in between <!--<REPLACE WITH YOUR API KEY HERE>--> with your own Google Maps API key.
  3. Replace the destination address in between <!--<REPLACE WITH YOUR CUSTOM ADDRESS HERE>--> with your custom destination.
  4. Save your changes and that's it, you're done.

## Options
See available MaxMind params at http://dev.maxmind.com/ and all things Google Maps at https://developers.google.com/maps/

## History
I built this out during the construction of an auto-body dealership client's website.

## Customization
This script was originally designed using Google Maps v2, it can be adapted to work with v3 with little or no customization. A similar API exists for other driving direction services, such as Bing Maps, OpenStreetMaps, MapQuest, and many many others.
In principal, the steps which result in the return of a latitude and longitude based on an IP-address are universal and can be adapted in any number of ways to suite your needs.
