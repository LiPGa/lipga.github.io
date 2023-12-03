---
title: Vocal Elimination
subtitle: 🎵 Vocal Elimination based on MatLab
summary: 🎵 Vocal Elimination based on MatLab
tags:
- MatLab
- Digital Signal Processing
- Discrete Fourier Transform
- Media
date: "2019-04-02T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  placement: 2

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

## Introdcution
- Remove the voices of human from a stereo song and get pure music (the sound of the instrument).
- Audio format: mp3/wav
- Tool: MATLAB
- Keywords: sampling, FFT, filter, channel mixer, inversion and etc.

## Background
- Vocal elimination is a technique that eliminates the vocals of stereo songs.
- Vocal elimination is a simple DSP application.

## Principles
- Features of Stereo music: In stereo music, the instrument sound in the left and right channels is different in stereo music, especially the various instruments in the song are placed in the left and right channels; while the human voice is generally the same in both channels.
In this course design, we mainly apply this property to achieve the effect of vocal elimination.
- Features of vocal: The sound image position of human voice is in the center of the entire sound field (balanced distribution of left and right channels); the sound frequency is concentrated in the middle and high frequency parts.
We know that the instrument sound in the left and right channels is different in stereo music, especially the various instruments in the song are placed in the left and right channels, but the vocals in the two channels is exactly the same. Then, you can use this property to eliminate vocals.

