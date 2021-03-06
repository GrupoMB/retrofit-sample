### Retrofit Sample Project

this project create for [Retrofit Tutorial](https://www.youtube.com/playlist?list=PL-0EQDLPE23N3WkenBrZzTLfnOIAIybKm), fake Twitter client with these feature :

*	user can post new tweet
*	user can edit or delete tweet
*	custom gson converter
*	custom error handling
*	sign up / sign in with email address
*	refresh token when access token expired
*	update user profile
*	upload image user
*	search in tweets by feel

### how can use from this project

1- the backend deploy with `Node.js`, install [Node.js](nodejs.org) then clone [this repo](https://github.com/atahani/rest-api-sample) and checkout related branch, remember install `Node.js Module` via `npm`

```
$ git clone https://github.com/atahani/rest-api-sample
$ cd rest-api-sample
$ git branch -a | grep -v HEAD | perl -ne 'chomp($_); s|^\*?\s*||; if (m|(.+)/(.+)| && not $d{$2}) {print qq(git branch --track $2 $1/$2\n)} else {$d{$_}=1}' | csh -xfs
$ git checkout simple_rest_api
$ npm install
$ node server.js
```

2 - repo contain different branches in multiple steps, so you should clone this repo and checkout related branch

```
$ git clone https://github.com/atahani/retrofit-sample
$ cd retrofit-sample
$ git branch -a | grep -v HEAD | perl -ne 'chomp($_); s|^\*?\s*||; if (m|(.+)/(.+)| && not $d{$2}) {print qq(git branch --track $2 $1/$2\n)} else {$d{$_}=1}' | csh -xfs
$ git checkout 01_configure_project
```

3- set the `REST_API_BASE_URL`, `CLIENT_ID` and `CLIENT_KEY` values inside `ClientConfigs.java` class

NOTE: this application just create to demonstrate how we can use from [Retrofit](square.github.io/retrofit/) to talk with REST API

### for more information see the slide and videos

* [Youtube Playlist link](https://www.youtube.com/playlist?list=PL-0EQDLPE23N3WkenBrZzTLfnOIAIybKm)
* [Slides on Google Slide](https://goo.gl/lzwXys) 
