# homebridge-spotify-switches

The Spotify APP is perfect for remote controling your TV or any other player. This plugin is ment to be helpfull to automate Spotify action.

With this plugin you can add switches to:

1. Choose a song to play whenever a switch is pressed
2. Choose a playlist to play whenever a switch is pressed
3. Set the volume

## Setup

1. `sudo npm install -g homebridge`, See the [Homebridge](https://github.com/nfarina/homebridge) project site for more information, and to configure Homebridge
2. `sudo npm install -g homebridge-spotify-switches`
3. Configure the platform...

Add the following accessory definition to `~/.homebridge/config.json`:

```
"platforms": [
  {
    "name": "SpotifyPlatform"
  }
]
```

## Usage

You have to configure the switches by going to http://<homebrifge-ip>:8080. You will be asked to authorize the plugin to access your Spotify account and after that you can add and remove switches.

## Issues

Any issues or help getting setup please use the [github page](https://github.com/JSRossiter/homebridge-spotify/issues).
