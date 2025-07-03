# pico-sdk-builds

Simple rakefile that builds pico-sdk in four flavours with one call of 'rake'.

Boards:

* pico
* pico2

Configs:

* Debug
* Release

So that your pico-sdk projects can pull in one of these instead of duplicating.

I locate mine in ~/src/pico

where i have

* pico-sdk
* pico-sdk-builds
* picotool

Picotool is built and refered to by this rake file.

TODO: locate via an env variable.
