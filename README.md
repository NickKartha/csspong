# [CSS Pong](http://reddit.com/r/csspong)

A playable game of pong powered only by CSS!  
It was designed to be hosted on a subreddit, so you can play it at [reddit.com/r/csspong](http://reddit.com/r/csspong)  

I tried to explain how it works over [there](https://www.reddit.com/r/csspong/comments/5cyqcd/how_it_works/)

## Note from Nikhil

I have no idea how to run this. I found this project only adheres to the reddit header format and doesn't work properly when run just like that. This may be due to dependencies and environments that I may have not known needed to be set up.

## Development

I used webpack to be able to use sass/scss and also iterate faster.  
You should be able to do `npm install` then `npm start` to make it run locally.  
The "build" for a subreddit consists of _structure.md_ that goes in the sidebar and _css/pong.css_. (`npm run build` or `./build.sh`)
