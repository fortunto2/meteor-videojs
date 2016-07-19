meteor-videojs
==============
v5.10.7
A meteor package for videoJS

  `meteor add lifefilm:videojs`

to use with react

  `npm install react-videojs --save`

in jsx

```

  import Video from 'react-videojs';

  <Video
    src="http://www.w3schools.com/html/mov_bbb.mp4"
    type="video/mp4"
    onPlay={this.handlePlay}
    width="640px"
    height="360px"
    controls
    data-setup='{ "aspectRatio":"640:360", "playbackRates": [1, 1.5, 2] }'
  />

```
