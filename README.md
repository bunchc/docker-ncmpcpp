Docker ncmpcpp
==============

[Docker](https://docs.docker.com/installation/) containerized version of [ncmpcpp](http://ncmpcpp.rybczak.net/screenshots.php) (NCurses Music Player Client (Plus Plus)) a MPD console client.

Can be used together with any MPD server (like [Mopidy](https://www.mopidy.com/)); meant to be used together with [wernight/mopidy](https://registry.hub.docker.com/u/wernight/mopidy/) Docker image.


Usage
-----

    $ docker run --rm -it wernight/ncmpcpp [--help]

Note: It runs as user with random UID `71723` to avoid running as `root`.


### Basic keyboard shortcuts

  * `q` - Quit
  * `1` - Help
  * `3` - Browse
      * `Enter` - Enter directory / Add item to playlist and play
      * `Space` - Add item to playlist
      * `Backspace` - Parent directory
  * `4` - Search
      * `Enter` to edit field
      * `y` - Search
      * `4` - Reset
  * `5` - Library
  * `s` - Stop
  * `P` - Pause
  * `<` / `>` - Previous / Next track
  * `Backspace` - Play current track from the beginning
  * `b` / `f` - Seek backward / forward


Feedbacks
---------

Having more issues? [Report a bug on GitHub](https://github.com/wernight/docker-ncmpcpp/issues).
