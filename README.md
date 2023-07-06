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

> The summary of the data is ...

- How could you use this data in an application?

> I could imagine integrating this API into an app that ...

- What did you like about the documentation?

> The documentation was ...

- What did you find challenging about the documentation?

> I found the documentation ...

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...

- In your own words, summarize the request-response cycle.

> The request-response cycle ...

- In your own words, describe what an API is.

> An API is ...

- In your own words, describe the purpose of Postman.

> Postman is an application that ...
