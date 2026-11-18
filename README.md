# Why Video Upscaling Is Not Image Upscaling, Repeated 300 Times

Measured: per-frame upscaling is not a video upscaler. The frame-to-frame stability metric I published was gameable — nearest-neighbour won it while having the worst fidelity. Three metrics, 40 frames, 2x and 4x.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-video-upscaling-limits/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
