---
title: "sounder"
author: "Zeph"
description: "a small and portable music player capable of good quality audio!"
created_at: "2025-7-10"
---

# July 10: Researched parts, and added the ESP32 to KiCad

I thought of this idea a long time ago, but I decided to start today! I researched parts a bit, and I decided on:
Microcontroller - ESP32 S3 Devboard
DAC: PCM5102A
Headphone amp: MAX97220
Speaker amp: PAM8403
Speaker: A generic round 2W 8 Ohm speaker


I haven't chosen a screen yet. AliExpress charges $20+ for shipping for 8-bit ILI9341s for some reason. Also, I'll try adding two speakers for stereo sound if it fits! But it probably won't since I'm going for a size similar to an iPod.

I couldn't find the symbol for the ESP32 in the official ESP repo, so I used the symbol in https://gitlab.com/justadiode/kicad-symbols. This took me too long to find :c

<img width="1920" height="3086" alt="Screenshot 2025-07-10 at 18-46-40 Please Confirm Your Order - AliExpress" src="https://github.com/user-attachments/assets/b786cc5c-dfd1-49d3-a040-d34d82717459" />
<img width="487" height="778" alt="image" src="https://github.com/user-attachments/assets/39e9971c-c124-43a6-9da7-7b44a819d644" />

**Total time spent: 5h**
