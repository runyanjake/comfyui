# To Get Playlist Art
I have a folder of playlists on my Spotify account that I call my "To Get" series.  
Whenever I add a song to any playlist, I also add it to the latest in the series.  
When I have a month's worth of songs or break 80-100 in the playlist, I'll typically roll another.  

A great thing about doing this is that by looking back I can see slices of my music listening history.

I used to draw the playlist arts myself, but I'm not the best artist, and like the challenge of getting generative AI to do it for me.

This image gen pipeline makes use of a basic ComfyUI setup in which I can describe a general setting or vibe to ChatGPT, drop it in to a prompt, and generate away.

## Setup
1. Install ComfyUI, clone this repo or copy the workflow.json.
2. Download a flux.1 model, I'm using `flux1-dev-fp8`. Load the checkpoint in ComfyUI.
3. Run ComfyUI, and load the workflow.json by dragging it into the UI.

## Workflow
1. Modify the prompt sections to include a description of the background. Use ChatGPT to generate such a prompt. Best ChatGPT prompts start with the phrase `create a prompt for the flux.1 image generation model to create a scene depicting ...`.
2. Change other things about the prompt, e.g. text description, and text value.

