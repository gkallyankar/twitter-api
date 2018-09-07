# Twitter API POC

Twitter API to post and fetch latest tweets against particular #tag.

### Nodejs: Server setup
```
1. git clone https://github.com/gkallyankar/twitter-api.git
2. cd twitter-api
3. npm i
4. npm start 
```

### Angular 6: Client setup
```
1. cd client
2. npm i
3. npm start
```

### Technology Stack:
1. Nodejs (ExpressJs): Server side
2. Angular 6: Client side
3. twit npm package to interact with twitter rest api.

### Features:
1. Listing of all tweets against #nowplaying over twitter.
2. Infinite scroll.
3. Post tweet by providing video link and comment.(It will post this tweet with #nowplaying)
4. Showing video links from tweets(Issue to show youtube video from shorlinks genereted by twitter)

### To Get Experience 
Add Your 
1. consumer_key
2. consumer_secret
3. access_token
4. access_token_secret 
In the twitter.config.js file
