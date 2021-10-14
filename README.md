# Video player for the site

![video-player](https://i.imgur.com/1bj2r25.png)

The video player allows you to do the following things with video:
* play and pause the specified video;
* turn the sound on and off;
* expand video to full screen.

Built on the basis of the [Playable](https://wix.github.io/playable/) library.

You can see the demo video of the player at the [link](https://savilard.github.io/player-animations/html/index.html).


## How to install

* Download the repository:
```bash
git clone https://github.com/savilard/player-animations.git
```

* Go to the folder `player-animations/html`:
```bash
cd player-animations/html
```


## How to run

Open file `index.html`


## How to choose a different video

If you want to select a different video, you can use the src argument to specify which video to play. Links must end with the file extension:
```html
<script type="text/javascript">
  createPlayer({
    elementId: 'player',
    src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4'
});
</script>
```

## Project Goal

The code is written for educational purposes on online-course for web-developers [dvmn.org](https://dvmn.org/).
