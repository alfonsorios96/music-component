[![Build Status](https://travis-ci.org/jusolete/music-component.svg?branch=master)](https://travis-ci.org/jusolete/music-component)

# \<music-component\>

## Install bower
npm i bower

## Run bower install

```
$ bower install
```

## Properties
```javascript
|     Properties    | value (default) |                              description                              |
|:-----------------:|-----------------|:---------------------------------------------------------------------:|
|       paused      |      false      |                defines wether the song is paused or not               |
|      songUrl      |        ""       |                  determines the direction of the song                 |
|    songDuration   |        0        |           its set to be the duration of the song in seconds           |
|    startingTime   |        0        |       determines the starting position of the song (in seconds)       |
| songProgress      |        0        |                     current progresss of the song                     |
|       volume      |        0        |               determines the volume of the audio player               |
|   searchArgument  |        ""       |            search String (used with search-song component)            |
|     hiddenList    |       true      |              hide the list of songs(song-list component)              |
|      songName     |        ""       |                    name of the song to be displayed                   |
|   listRequestUrl  |        ""       |         url of the songs list (used with song-list component)         |
|      trackUrl     |        ""       | specific song request direction (combination of songUrl and songName) |
| invisibleControls |      false      |               determines the visibility of the controls               |
```


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
