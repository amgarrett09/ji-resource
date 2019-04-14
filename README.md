# ji-resource

JI Resource is an online learning app about Just Intonation and the connections between physics and music.

Work in progress.

## Design goals

The objective of the app is to provide an online learning platform where users can explore questions like: "Why are there twelve tones in an octave?" "Why do certain chords on my guitar or piano sound out-of-tune even if the instrument is tuned correctly?" "What are some of the other possibilities for musical tuning?"

JI Resource will provided lessons with periodic quizzes to help users internalize the information. Ideally, lessons will contain both visuals and audio to help convey the material.

Eventually, I want to incorporate authentication to allow the app to track the users' progress, but this will come after the basic functions of the app are already working fairly smoothly.

## Technologies used

I'm building the app with Vue and Nuxt.js, mainly because I like the syntax of Vue and Nuxt takes away a lot of the headaches and tedium of bulding a server-rendered Vue app from scratch. Right now I'm using the CSS framework Bulma to speed up crafting the design of the site a bit.

The server is using express.


## Build Setup

``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```
