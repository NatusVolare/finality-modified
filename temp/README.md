# finality (modified fork)

This repository is a personal fork of the "Finality" Jellyfin theme originally created by Ted Hinklater (see the original project at https://github.com/tedhinklater/finality). Full credit goes to the original author and contributors — thank you for the great work.

Why this fork exists
- This fork contains personal visual and layout adjustments made for my own Jellyfin instance and viewing preferences. The changes are primarily CSS-only and intended to tweak colors, spacing, and layout to favor fullscreen (F11) viewing and ultrawide screens.
- The goal is to preserve the look-and-feel and functionality of the original Finality theme while making a few personal modifications (listed below) for convenience and preference.

Notable modifications in this fork
- Color and contrast adjustments (black & white defaults and a coloured variant).
- Layout tweaks to keep key content visible in fullscreen without vertical scrolling.
- Additional ultrawide fixes and small responsive improvements.
- Player styling refinements and minor UI tweaks for personal preference.
- Guidance for integrating the Featured Content Bar and recommended display settings.

Compatibility & attribution
- This fork is derived from the original Finality theme. Please refer to the upstream repository for the original license and attributions: https://github.com/tedhinklater/finality

768p :heavy_check_mark: 1080p :heavy_check_mark: 1440p :heavy_check_mark: 4k :heavy_check_mark: Mobile :heavy_check_mark: TV Mode :soon:

Also: Turn it up to 11 with the new [Featured Content Bar](https://github.com/tedhinklater/Jellyfin-Featured-Content-Bar) 
![bar](https://github.com/user-attachments/assets/f2c45f47-3530-4525-9f89-fe4e96c7676f)

# This theme is optimized for Fullscreen! 
The main goal was to have everything on one screen without having to scroll up/down.
Care has been taken to make it work in windowed mode, but it's mainly for fullscreen view (press ```F11```)

![Screenshot 2024-12-17 014557](https://github.com/user-attachments/assets/827ef13c-fa97-494c-9a02-11530907659d)

For the black & white version, paste this into your Custom CSS Box

```css
@import url("https://cdn.jsdelivr.net/gh/Jeffrey214/finality-modified@main/finality.css");

```

or, import the colour version with

```css

@import url("https://cdn.jsdelivr.net/gh/Jeffrey214/finality-modified@main/Finality-Coloured.css");

```

![Screenshot 2024-12-11 064413](https://github.com/user-attachments/assets/657fb2df-40dd-42ee-b4d1-5b1691010b4d)
![Screenshot 2024-11-19 110303](https://i.imgur.com/S5Pgjip.png)
![Screenshot 2024-12-11 065050](https://github.com/user-attachments/assets/957fed52-2749-46f5-bd7c-8d75565d52f2)
![finality episodes](https://github.com/user-attachments/assets/139e219c-a431-467f-b393-184cf7e045d8)
![unknown_2024 12 17-01 33_1](https://github.com/user-attachments/assets/e8e6f142-f4c1-48fe-9784-b725fe19cea3)

Ultrawide users, import a version above, and also this fix: 

```css

@import url("https://cdn.jsdelivr.net/gh/Jeffrey214/finality-modified@main/UltrawideFix.css");

```

# Player 
![Screenshot 2024-11-09 040750](https://github.com/user-attachments/assets/8569475b-c90d-4a42-8f5e-aea786a78105)

# Mobile
![mobile](https://github.com/tedhinklater/finality/assets/66086488/a0fb2aec-2794-4d68-b96c-9a144844729a)

Under "Display" make sure you enable backdrops and use the Dark theme

![darkbackdrops](https://github.com/user-attachments/assets/b69b1143-22c1-48df-b8e5-5aaa1869a97f)
