# Sprout Video Downloader

A browser extension that enables you to download videos from the Sprout Video platform. Perfect for accessing corporate training, marketing materials, and other business content offline.

![sprout video downloader](https://github-production-user-asset-6210df.s3.amazonaws.com/45643901/477032621-100e6f5d-d076-4012-b5ae-3e90ded22f2b.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250813%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250813T044028Z&X-Amz-Expires=300&X-Amz-Signature=f78e354a510b1cc1930804686cd172b3c31953e35df02447511105b4d9e54d4d&X-Amz-SignedHeaders=host)


## 🔗 Links

- 🎁 Get it [here](https://serp.ly/sprout-video-downloader)
- ❓ Common issues [here](https://github.com/orgs/serpapps/discussions/categories/faq)
- 🐛 Report bugs [here](https://github.com/serpapps/sprout-video-downloader/issues)
- 🆕 Request features [here](https://github.com/serpapps/sprout-video-downloader/issues)

## Resources

- 💬 [Community](https://serp.ly/@serp/community)
- 💌 [Newsletter](https://serp.ly/@serp/email)
- 🛒 [Shop](https://serp.ly/@serp/store)
- 🎓 [Courses](https://serp.ly/@serp/courses)

## Downloading Sprout Videos

Sprout Video is built with security as a top priority, making downloads exceptionally complex. They utilize modern streaming protocols like HLS (HTTP Live Streaming), which breaks a single video into hundreds of small, individually encrypted `.ts` (transport stream) segments. You cannot simply download one video file. 

A successful download requires a multi-step process that this extension automates: first, it fetches and parses the `.m3u8` manifest file to get the list of all video segments. Then, it must download each and every encrypted segment, and finally, decrypt and stitch them together in the correct order to reassemble the original, complete video into a single MP4 file. This overcomes significant technical hurdles designed to prevent downloads.


## Features



<!-- ## Screenshots -->


<!-- ## Videos -->



## Permissions Justifications


