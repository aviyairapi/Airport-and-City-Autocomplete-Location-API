# Airport and City Autocomplete Location API
Data on airports, railway and bus stations, seaports and heliports located in any city in the world. Use the API as a database or integrate it to build an autocomplete feature for your platform.

<div id="header" align="center">
  <img src="https://media.giphy.com/media/LRZc4dV2kf787nbOB3/giphy.gif" width="100"/>
</div>

[Aviyair’s Airport and City Autocomplete Location API](https://aviyair.com/airport-and-city-autocomplete-location-api/) allows building an autocomplete feature that returns complete names and details of airports, cities, railway and bus stations and heliports based on the letters given. This way, your clients can enter certain letters and the API returns all relevant items that include these letters. This is a must-have feature for all aviation or travel-related platforms as it provides a convenient and user-friendly experience.

The Airport and City Autocomplete Location API data is accessible via GET requests and in JSON format. The structure of the API allows developers to use any programming language like VueJS, Angular, JAVA, PHP, Javascript, JQuery, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala which makes an efficient integration process.

--------

## Main Endpoint and Filters with Description

**GET** ` https://data.aviyair.com/data/v1/autocomplete
?key=[APIKEY]&city=avl`

| Request Parameter  | Description |
| ------------- | ------------- |
| city | Requested letters. The output includes all items with the requested letters in it, either at the front or middle |

------

## 200 OK Response Example

```
https://data.aviyair.com/data/v1/autocomplete
?key=[APIKEY]&city=avl

{
"GMT":"1",
"codeIataAirport":"QYU",
"codeIataCity":"GVX",
"codeIcaoAirport":"null",
"codeIso2Country":"SE",
"latitudeAirport":60.6746161,
"longitudeAirport":17.1418309,
"nameAirport":"Gavle C Railway Station",
"nameCountry":"Sweden",
"phone":"null,
"timezone":"Europe/Stockholm"
}
],

"GMT":"3",
"codeIataAirport":"IAR",
"codeIataCity":"IAR",
"codeIcaoAirport":"UUDL",
"codeIso2Country":"RU",
"latitudeAirport":57.61667,
"longitudeAirport":39.88333,
"nameAirport":"Yaroslavl",
"nameCountry":"Russia",
"phone":"null,
"timezone":"Europe/Moscow"
}
```

-------


## Full Documentation

Please visit our [website](https://aviyair.com/documentation/).

------

## Most Popular Use Cases

These are the most common use cases for the Airport and City Autocomplete Location API  but there are no limitations regarding how the API can be useful for you. If you have any concerns about the Terms and Conditions for the real-time flight delay data, you may visit the hyperlink below or contact us to ask about it.

-	Building an autocomplete feature for flight booking, searching, flight tracking, online travel agency and other similar aviation platforms where the API returns users all relevant city and airport information based on what they type in the search box.
-	Applications that rely on location-based services, such as mobility as a service/ride-hailing or navigation tools can integrate the city and airport autocomplete data. This way, users can easily find their desired destination by the suggested cities and airports based on their current location.
-	E-commerce platforms can integrate the API so the users can easily select city information or the nearest airport or city information for shipping, especially with B2B-oriented platforms.
-	Travel-related websites, apps, blogs can build an autocomplete feature which is useful when users wish to select articles to read about a popular destination, or local attractions, events and accommodation options in the destination.

---------

## License

[Terms and Conditions of Use](https://aviyair.com/terms-and-conditions/) apply. If you have any questions or concerns about your use case of the Airport and City Autocomplete Location API, please [contact us](https://aviyair.com/contact-aviyair/). 

--------

## How to Access

The API key to access Airport and City Autocomplete Location data is possible by creating an API subscription. The subscriptions do not require any commitments. It is possible to cancel anytime or make changes to your subscription level.

[View the prices and get an API key here.](https://aviyair.com/pricing-subscription-plans/)
