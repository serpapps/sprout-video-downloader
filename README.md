# SproutVideo Downloader (Browser Extension) | How to Download SproutVideo Videos

> Browser extension that downloads SproutVideo videos as MP4 from sproutvideo.com, vids.io links and SproutVideo players embedded on any website, including password-protected videos.

SproutVideo Downloader is a browser extension for saving SproutVideo-hosted videos you can watch. It finds SproutVideo players on direct pages, vids.io links and embeds on course sites, portals and docs, and saves them as MP4.

- Download SproutVideo players on sproutvideo.com, vids.io and embedded pages
- Password-protected videos: enter the password in the popup
- Pick the right player when a page has several embeds
- Choose from the qualities the player exposes (source, UHD, HD, SD)
- Authenticated HLS streams are assembled into MP4 in the browser; no ffmpeg needed

<a href="https://www.youtube.com/watch?v=f7cQfQC-vBk" target="_blank">
<img src="https://raw.githubusercontent.com/devinschumacher/uploads/refs/heads/main/images/how-to-download-sprout-videos-for-free-chrome-extension-method.jpg" width="700px">
</a>

## Links

- :rocket: Get it here: [SproutVideo Downloader](https://serp.ly/sprout-video-downloader?via=github)
- :new: Latest release: [GitHub Releases](https://github.com/serpapps/sprout-video-downloader/releases/latest)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :beetle: Report bugs: [GitHub Issues](https://github.com/serpapps/sprout-video-downloader/issues)
- :bulb: Request features: [Feature Requests](https://github.com/serpapps/sprout-video-downloader/issues)

## Why SproutVideo Downloader

SproutVideo is used for private business, course and portal video, often embedded on other websites,
password-protected, and streamed through signed HLS URLs. That rules out right-click saving and most
online download tools.

SproutVideo Downloader detects SproutVideo players on the page you have open, lets you unlock
password-protected players, and assembles the stream into one MP4 inside your browser.

## Features

- **Everywhere SproutVideo plays**: direct pages, vids.io links and embeds on third-party sites
- **On-player button**: a download button appears on detected players
- **Password-protected videos**: unlock with the correct password in the popup
- **Multiple embeds**: choose the right video when a page has several players
- **Quality selection**: formats and qualities the player exposes, highest first
- **Direct MP4 or HLS**: direct MP4 sources download directly; authenticated HLS is assembled into MP4
- **Progress, speed and status**: longer downloads stay visible without freezing the page
- **No ffmpeg**: no separate conversion software
- **Private by design**: detection, stream handling and MP4 generation run on your device

## Supported Browsers

| Browser | Supported |
|---|---|
| Google Chrome | ✅ |
| Microsoft Edge | ✅ |
| Brave | ✅ |
| Opera | ✅ |
| Naver Whale | ✅ |
| Yandex Browser | ✅ |
| Firefox, Safari, mobile browsers | ❌ Not supported |

Works on Windows, macOS and Linux desktops. Every release ships one ZIP per browser
(for example `sprout-downloader-chrome.zip`).

## How to Download SproutVideo Videos (Step-by-Step)

1. Install the extension (see [Installation Instructions](#installation-instructions)) and sign in with your email.
2. Open the page with the SproutVideo player and let the video load.
3. Click the download button on the player, or click the extension icon. Enter the password if the video is protected.
4. Pick the video (if the page has several) and a quality. Keep the tab open while the MP4 is saved.

## Supported Formats

- **Output:** MP4
- **Sources:** direct MP4 and authenticated HLS from SproutVideo players
- **Qualities:** whatever the player exposes, for example source, UHD, HD or SD

## Who It's For

- **Students and clients** saving training videos embedded in portals
- **Businesses** backing up their own SproutVideo library
- **Teams** keeping internal videos available offline

## Troubleshooting

**The downloader does not find the video**  
Make sure the player has fully loaded before opening the popup. For lazy-loaded embeds, refresh and wait for the player to start.

**A protected video fails**  
Enter the exact SproutVideo password in the popup's password section.

## Free Trial & Pricing

You get **3 free downloads a week** with no credit card. A **subscription** gives unlimited downloads, with updates included.

- Sign in with your email and a one-time code; no password to create.
- Your free downloads reset every week. In current versions only finished downloads count; a failed or cancelled download does not use one.
- See current plans on the [product page](https://serp.ly/sprout-video-downloader?via=github).

## Installation Instructions

1. Download the ZIP for your browser from the [latest release](https://github.com/serpapps/sprout-video-downloader/releases/latest) (for example `sprout-downloader-chrome.zip`).
2. Unzip it. You get a folder that contains `manifest.json`.
3. Open your browser's extensions page: `chrome://extensions` (Chrome), `edge://extensions` (Edge), `brave://extensions` (Brave), `opera://extensions` (Opera), `whale://extensions` (Whale) or `browser://extensions` (Yandex).
4. Turn on **Developer mode**.
5. Click **Load unpacked** and select the unzipped folder.
6. Pin the extension, click its icon, and sign in with your email and the one-time code we send you.

Prefer a guided setup? The [product page](https://serp.ly/sprout-video-downloader?via=github) walks you through the same steps.
When a newer version is published, the extension shows an update notice; download the new ZIP from
[GitHub Releases](https://github.com/serpapps/sprout-video-downloader/releases/latest) and load it the same way.

## FAQ

### How do I download a SproutVideo video?

Open a page with a SproutVideo player, let the video load, then click the in-player download button or the extension icon. Select the quality you want and keep the tab open while the MP4 is saved.

### Does it work on embedded SproutVideo players?

Yes. It detects SproutVideo embeds on third-party sites, private portals, docs pages and course platforms, as well as sproutvideo.com and vids.io links.

### Can it download password-protected SproutVideo videos?

Yes. If the video uses a SproutVideo password, the popup has a password section so you can unlock the player and continue.

### Can it detect more than one video on a page?

Yes. When a page has several SproutVideo embeds, the popup lists them so you can choose the right one.

### What quality options are available?

The formats the player data and HLS manifests expose, sorted highest first, for example source, UHD, HD or SD.

### Do I need ffmpeg or desktop software?

No. Authenticated stream handling, HLS processing and MP4 saving all run in the extension.

### Which browsers are supported?

Chrome, Edge, Brave, Opera, Whale and Yandex on Windows, macOS and Linux. Firefox, Safari and mobile browsers are not supported.

### Is there a free trial?

Yes. You get **3 free downloads a week** with no credit card. A **subscription** gives unlimited downloads, with updates included.

## Notes

- Only download content you own or have permission to save.
- The extension works with videos your own account can already watch in the browser. It does not unlock paid, private or locked content.
- Quality depends on what the source player serves; the extension cannot make a video sharper than the original.
- Site updates can affect detection. If something stops working, [open an issue](https://github.com/serpapps/sprout-video-downloader/issues) and include the page type (not private links).

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## Related

- [Vimeo Video Downloader](https://github.com/serpapps/vimeo-video-downloader)
- [Loom Video Downloader](https://github.com/serpapps/loom-video-downloader)

## About SproutVideo

SproutVideo is a video hosting platform for businesses, with privacy controls, password protection
and embeddable players used on websites, course platforms and client portals. SproutVideo Downloader
saves the videos you are allowed to watch.
