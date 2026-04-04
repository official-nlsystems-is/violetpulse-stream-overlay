# Twitch Overlay Project

This repository contains a custom Twitch overlay created as a client commission.

The project was built for a fixed streaming setup and includes several overlay scenes as well as webcam frame variations for different use cases. It is intended for OBS Studio or any other streaming software that supports browser sources.

## Project Contents

The repository is split into two main parts:

### `frames/`
This folder contains standalone webcam frame files.

- `webcam169.html` — 16:9 webcam frame
- `webcam43.html` — 4:3 webcam frame

### `overlays/`
This folder contains the main overlay scenes.

- `background.html` — background overlay
- `starting-soon.html` — starting soon screen
- `brb.html` — be right back screen
- `justchatting.html` — just chatting layout

### `overlays/images/`
This folder contains the visual assets used by the overlay, including:

- background artwork
- social media icons
- additional design assets

### Other files
- `script.js` — shared script used by the overlay setup

## What this project is made for

This overlay was created for a custom stream layout with a dark, polished style.  
It is not a responsive website and it is not meant to behave like one. The files are built for fixed placement inside streaming scenes.

That means it works best when used exactly as intended inside a properly sized OBS canvas.

## Main features

This project includes:

- webcam frame layouts in multiple formats
- full overlay scene files for different stream states
- a just chatting layout with camera, chat, and social elements
- custom styling and integrated design assets
- fixed positioning for clean scene building in OBS

## Setup

1. Download or clone the repository.
2. Open OBS Studio or your preferred streaming software.
3. Add the HTML file you want to use as a browser source.
4. Set the browser source size to match your scene setup, usually `1920x1080` unless you are intentionally using another format.
5. Keep the folder structure unchanged so that all linked assets continue to load correctly.
6. If needed, edit the HTML files directly to adjust displayed names, placements, or other visual details.

## Important notes

- This project uses a fixed layout.
- It is designed for browser source usage in streaming software.
- It is not interactive.
- It should be used with the original folder structure kept intact.
- Changing dimensions too heavily may affect spacing, alignment, and proportions.

## Customization

Small edits can be made directly in the source files if adjustments are needed.

This includes things such as:

- names or labels
- social links
- text content
- positioning
- colors
- styling details

Basic HTML, CSS, and simple browser-source knowledge are recommended before editing the files.

## Requirements

To use this project properly, you will need:

- OBS Studio or similar software with browser source support
- an internet connection for any externally loaded fonts
- the included asset files in their original paths

## Copyright and Usage

This project is protected work.

No person, company, platform, service, third party, or system has any right to use this project or any part of it without prior official written permission from the creator.

This applies to all forms of use, including but not limited to:

- personal use
- commercial use
- redistribution
- reuploading
- republishing
- modification
- resale
- reuse of code
- reuse of design elements
- reuse of assets
- storage in datasets
- analysis for training purposes
- AI training
- machine learning
- style imitation
- partial extraction of any component

Access to this repository, its files, its preview, or its delivery does not grant any license, ownership, permission, or right of use of any kind.

No part of this project may be copied, edited, shared, published, reproduced, extracted, trained on, referenced for reuse, or used in any way unless official written rights of use have been granted in advance by the creator.

All rights remain fully reserved by the creator.

## Project Information

Custom Twitch overlay commission  
Created in Germany — 2025