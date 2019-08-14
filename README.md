# silent-disco
A simple web-based silent disco provider.

This simple webpage can serve as a silent disco for a party. It serves up a HTML5 audio element and a configurable amount of "channels". Each channel represents an evenly spaced time offset in the audio.

The idea is to use a long audio file with e.g. an entire "silent disco playlist" in it.

This way, many users can fire up the page on their phones, play the audio and select channels. The same channel should put multiple users more or less in sync because it is based on globally absolute time (Unix timestamps).

Requirements:

- A webserver. For quick testing, thttpd is great:
thttpd -D -p 8080

Modify the HTML to use your audio file and number of channels of choice.

