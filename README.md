This repository holds the source code and content of the FOSDEM website (as of https://fosdem.org/).

FOSDEM is the Free and Open source Software Developers' European Meeting,
an event that is organized by the community for the community, as a non-for-profit.

Thousands of Open Source contributors from around the world meet every year in Brussels (Belgium)
to enjoy over 400 sessions and many occasions to chat and exchange.

Our website uses the nanoc static site generator, and we did implement a lot of custom
code to support our workflow as painlessly as possible.
Maybe some bits of those will be an inspiration or of help.

# System software dependencies

Some Ruby gems rely on software written in C. Install this via apt, yum, pacman or
whatever system package manager you use. Do this before you attempt to
run `bundle install` (otherwise it will fail).

## Ubuntu 14.04, 16.04
sudo apt-get install libmagickwand-dev imagemagick
