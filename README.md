# TauschRausch Sticker
This repo contains code and data to generate Stickers for the TauschRausch Project.
The sickers are layouted using HTML and CSS and rendered to pdf with phantomjs.
Colors for the Stickers are extracted from the Flyers located in `in/flyer`.

## Build it!
You can grab a coppy of the coplied PDF on the Gitlab Builds Page for this repo,
or build it yourself by executing
```
git clone https://gitlab.com/TauschRausch/sticker
cd sticker
make
```
(This needs Gnu-Make, npm and python and the python module `ìmageio` to be installed)

## Print it!
The current stickers are designed to be printed on 42*9.8cm paper. This leads to a sheet of
10 Stickers. The format was choosen, because it is very cost effective.

## License
Everything in this repo (except for the Flyers) is licensed under GPLv3.
Feel free to fork and build your own Stickers with the same technology.