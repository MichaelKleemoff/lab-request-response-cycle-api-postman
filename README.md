# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL

> https://api.chess.com/pub/
> Chess.com Published-Data API

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this website is all current public data such as player data, game data and club/tournament information of chess players using the Chess.com app.

- What is the URL of the documentation?

> https://www.chess.com/news/view/published-data-api#pubapi-endpoint-player

- What is the full URL of one endpoint?

> https://api.chess.com/pub/player/mikek

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
	"player_id": 1497520,
	"@id": "https://api.chess.com/pub/player/mikek",
	"url": "https://www.chess.com/member/MikeK",
	"name": "Mike King",
	"username": "mikek",
	"followers": 0,
	"country": "https://api.chess.com/pub/country/NZ",
	"location": "Gisborne",
	"last_online": 1242971367,
	"joined": 1221038731,
	"status": "basic",
	"is_streamer": false,
	"verified": false
}
```

- What status code did you get back?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`
> application/json; charset=utf-8

> `Content-Length`
> 1.22 KB

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> https://api.chess.com/pub/player/mikek returns the profile summary of one of the chess players in JSON format. It includes basic info about the user such as the username, actual name, id, location, status, no. of followers, when joined, last online.

- How could you use this data in an application?

> I could create a nicely styled app where their name and other facts show. Also, info such as where they are located could use a map app and some animation for instance, to improve the user experience. I could use the obvious chess motives, since this is a chess app.

- What did you like about the documentation?

> The documentation was simple to use, with good indentation, links and examples of how to use the API.

- What did you find challenging about the documentation?

> I found the documentation was straight-forward and easy to understand. I didn't find it challenging especially in light of the reading.

- Did the quality of the documentation impact your decision to use it?

> No, I mostly picked it because I like chess and it didn't use authentication nor CORS.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes, I initially chose the Google Maps API, but it was too involved and an authentication token was required, so I switched to the current Chess.com API.

- In your own words, summarize the request-response cycle.

> The request-response cycle is where a developer can work with JSON formatted data in order to build apps. A request is made according to the specific API protocol and a response is given with useful information such as the desired key/value pairs and various other meta data. Also, things like the status and response headers are useful.

- In your own words, describe what an API is.

> An API is an application programming interface where programs can successfully communicate and interact with other programs when they are run.

- In your own words, describe the purpose of Postman.

> Postman is an application that simplifies working with data for a developer in a JSON format that is located in the cloud on some database.
