Hey here is the link for southwest docker hub and a snipet

https://hub.docker.com/r/swadavid/swahack

```
docker pull swadavid/swahack

Southwest Airlines sample data for TAMUhack 2020

to start preloaded MongoDB run docker run -p 27017:27017 swadavid/swahack

This DB does not have a user or password, just connect on mongodb://localhost:27017 all data is in the flight-data database in the flights collection

The quickest way to get started browsing our data is to use Mongo Compas (https://www.mongodb.com/products/compass), just download and click the green "connect" button while the container is running

The sample data provided is mock flight schedule data departing from Dallas Lovefield (DAL) to various destinations over 3 days. Each entry is a JSON object with the following structure

{ "originationAirportCode": "DAL", "destinationAirportCode": "AUS", "departureTime": "2020-01-25T06:00:00.000-06:00", "arrivalTime": "2020-01-25T07:00:00.000-06:00", "departureDate": "2020-01-25", "marketingCarrier": "WN", "operatingCarrier": "WN", "marketingFlightNumber": "1878", "operatingFlightNumber": "1878", "numberOfStops": 0, "connectionAirportCode": "", "connectionMarketingCarrier": "", "connectionOperatingCarrier": "", "connectionMarketingFlightNumber": "", "connectionOperatingFlightNumber": "", "scheduledArrivalDayIsDifferentFromDepartureDay": false, "flightDuration": "01:00", "dollarPrice": 281 }

The same data in a JSON Array format can be found on our slack channel.
```
