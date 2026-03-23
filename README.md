# SproutVideo Downloader (Browser Extension)

> Download supported SproutVideo-hosted videos as MP4 files from embedded players and direct pages.

SproutVideo Downloader is a browser extension built for users who need offline access to business videos, training content, and embedded media served through SproutVideo. It detects supported direct-file and streaming playback flows, surfaces available quality options when present, and exports the final result as MP4 for later playback.

- Save supported SproutVideo videos from embeds and direct pages
- Handle direct MP4 and supported HLS-backed workflows
- Export MP4 files for easier offline viewing and review
- Keep a browser-first workflow for business and training content
- Avoid manual stream extraction from embedded players

## Links

- :rocket: Get it here: [SproutVideo Downloader](https://serp.ly/sprout-video-downloader)
- :new: Latest release: [GitHub Releases](https://github.com/serpapps/sprout-video-downloader/releases/latest)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :beetle: Report bugs: [GitHub Issues](https://github.com/serpapps/sprout-video-downloader/issues)
- :bulb: Request features: [Feature Requests](https://github.com/serpapps/sprout-video-downloader/issues)

## Preview

![SproutVideo Downloader workflow preview](assets/workflow-preview.webp)

## Table of Contents

- [Why SproutVideo Downloader](#why-sproutvideo-downloader)
- [Features](#features)
- [How It Works](#how-it-works)
- [Step-by-Step Tutorial: How to Download Videos from SproutVideo](#step-by-step-tutorial-how-to-download-videos-from-sproutvideo)
- [Supported Formats](#supported-formats)
- [Who It's For](#who-its-for)
- [Common Use Cases](#common-use-cases)
- [Troubleshooting](#troubleshooting)
- [Trial & Access](#trial--access)
- [Installation Instructions](#installation-instructions)
- [FAQ](#faq)
- [License](#license)
- [Notes](#notes)
- [About SproutVideo](#about-sproutvideo)

## Why SproutVideo Downloader

SproutVideo is commonly embedded inside corporate training portals, marketing pages, and product education flows. That means the media source is often hidden behind an iframe or streaming layer rather than presented as a simple download link. Generic download tools can miss the actual file or fail on embedded HLS playback.

SproutVideo Downloader is built for that embedded workflow. Open the page, let the extension detect the supported media source, choose the quality you want, and export the result as MP4 without leaving the browser.

## Features

- Detects supported SproutVideo embeds on any website (sproutvideo.com, vids.io, or third-party)
- Handles direct MP4 and supported HLS-backed playback flows
- Overlay download button appears directly on detected SproutVideo players
- Password-protected video support with in-extension password entry
- Multi-video page support for pages with several SproutVideo embeds
- Lists available quality variants when present (source, UHD, HD, SD)
- Real-time progress tracking with download speed and file size
- Exports MP4 files for simpler offline review
- Handles authenticated HLS streams with policy-signed URLs
- Cross-browser support for Chrome, Edge, Brave, Opera, Firefox, Whale, and Yandex

## How It Works

1. Install the extension from the latest release.
2. Open a page containing a SproutVideo player and start playback.
3. Let the extension detect the active media source.
4. Open the popup or use the overlay download button on the player.
5. Enter the video password if the content is password-protected.
6. Choose the quality or stream option you want.
7. Save the final MP4 file locally.

## Step-by-Step Tutorial: How to Download Videos from SproutVideo

1. Install SproutVideo Downloader from the latest GitHub release.
2. Open the training page, course page, or embed that contains the SproutVideo player.
3. Let the player load fully and start playback.
4. Click the overlay download button on the player or open the extension popup.
5. Enter the video password if the content is password-protected.
6. Review the quality options shown by the extension.
7. Choose the resolution you want if multiple options are available.
8. Start the download and wait for the MP4 export to finish.
9. Open the saved file from your Downloads folder.

## Supported Formats

- Input: supported SproutVideo direct-file downloads (source, UHD, HD, SD)
- Input: supported SproutVideo authenticated HLS streams
- Output: MP4

Saved files use MP4 so they are easier to replay on standard media players, transfer between devices, or archive for later access.

## Who It's For

- Teams saving business or training videos for offline review
- Users working with embedded SproutVideo players on third-party sites
- People who need a browser alternative to manual media extraction
- Users archiving content they already have access to in the browser
- Content creators who need to download their own SproutVideo-hosted content

## Common Use Cases

- Save an embedded SproutVideo training lesson
- Export a supported business video as MP4
- Keep marketing or education content available offline
- Avoid manually tracing through iframe and player requests
- Download password-protected SproutVideo content for offline access

## Troubleshooting

**The extension does not detect the video**
Start playback first and wait for the player to initialize the active media source.

**The player is inside an embed**
The extension scans iframes automatically. Try refreshing the page if the embed loaded after the extension.

**Only one quality appears**
Some players expose only one usable stream or one available resolution.

**The video is password-protected**
Enter the correct password in the extension prompt. The video will unlock for download once verified.

**The download stopped or failed partway through**
Check whether your internet connection dropped during the export. Retry the download from the popup.

## Trial & Access

- Includes **3 free downloads** so you can test the workflow first
- Email sign-in uses secure one-time password verification
- No credit card required for the trial
- Unlimited downloads are available with a paid license

Start here: [https://serp.ly/sprout-video-downloader](https://serp.ly/sprout-video-downloader)

## Installation Instructions

1. Open the latest release page: [GitHub Releases](https://github.com/serpapps/sprout-video-downloader/releases/latest)
2. Download the correct build for your browser.
3. Install the extension.
4. Open a SproutVideo page or embed and start playback.
5. Use the popup to detect and download the media.

## FAQ

**Can it download SproutVideo embeds?**
Yes. It supports embedded playback flows and direct-page players on any website.

**Can I download password-protected videos?**
Yes. If a video is password-protected, the extension will prompt you to enter the password.

**Does it work only on public pages?**
It works on content you can already access in your browser session.

**Do I need extra software?**
No. The workflow stays inside the browser extension.

**Where are videos saved?**
They are saved to your default Downloads location as MP4 files.

**What browsers are supported?**
Chrome, Edge, Brave, Opera, Firefox, Whale, and Yandex.

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## Notes

- Only download content you own or have explicit permission to save
- An internet connection is required for downloads
- SproutVideo embed must be loaded on the page before detection works
- Quality depends on what the video owner has enabled
- Password-protected videos require the correct password

## About SproutVideo

SproutVideo is widely used for hosting business, training, and marketing video content across direct pages and embeds. SproutVideo Downloader is built to make supported downloads easier for users who already have access to that content in the browser.
