# demostream

Streaming service for great demoscene examples (c64, amiga, zx spectrum, etc)

### Try it live here -> [demostream.cyanpencil.xyz](http://demostream.cyanpencil.xyz)


# Instructions
- Put your demos in the `videos/` folder. Accepted formats are `mp4`, `webm` and `mkv`.  Your demos will be played at random to the nginx server which will serve them through `hls` (http live streaming) on port 8080.

- Change `run.sh` if you use `docker` instead of `podman`

- run `docker build -t demostream .`

- then execute `./run.sh`


# Credits

[Oldschool PC fonts](https://int10h.org/oldschool-pc-fonts/fontlist/) - for the IBM VGA fonts used in the frontend

[ffmpeg](https://www.ffmpeg.org) - complex but wonderful tool 

Sebastian Ramirez - for the initial version of the Dockerfile
