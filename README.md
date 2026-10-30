# EASyPLUS Classic

A browser-based **fictional EAS-style broadcast simulator** for video production. It does not transmit real alerts or connect to public warning systems.

## Run it locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Open this repository's **Settings**.
2. Select **Pages** in the left sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then click **Save**.
5. Wait a minute or two for the published site link to appear on the Pages settings screen.

## Use
- The home page is the control console.
- Click **Open Broadcast Screen** to open the overlay in another browser tab.
- In OBS, add a **Browser Source** using the published site URL followed by `?overlay=1`.
- Keep the control console and overlay open in the same browser profile. This version uses browser-local storage and does not synchronize across different devices or browsers.

## Safety
For video-production simulation only. Do not present simulated alerts as real emergency warnings.
