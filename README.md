# ElevateLabs-CyberSecurity-Internship-TASK-7
Identify and Remove Suspicious Browser extensions
Step-by-step Guide
0) Prep (2 minutes)

Update your browser to the latest version.

Sync/backup bookmarks if you rely on them.

If you’re on a school/office machine, check if it’s “Managed by your organization.” Don’t remove policy-enforced extensions—note them as Managed.

1) Open the Extensions/Add-ons Manager

Chrome (Windows/macOS/Linux): chrome://extensions → turn on Developer mode (top right).

Edge: edge://extensions.

Firefox (Desktop): Menu ☰ → Add-ons and themes → Extensions (or go to about:addons).

Firefox (Android): Menu ⋮ → Add-ons.

Chrome (Android): Standard Chrome doesn’t support extensions. If you’re on a Chromium browser with extensions (e.g., Kiwi), open its extensions page.

2) Make an Inventory

For each extension, note:

Name, ID (Chrome/Edge shows when Developer mode is on), Version

Publisher/Source (link to Chrome Web Store/AMO)

Permissions shown on the details page

Site access (all sites vs. on click/specific sites)

Allowed in Incognito/Private (on/off)

Last updated date (if shown)

Tip (Chrome): Click Details → check Permissions, Site access, View in Chrome Web Store, and Extension options.

3) Identify Red Flags (mark “Suspicious” if any apply)

You don’t recognize installing it (especially if not from the official store).

Overbroad permissions: “Read and change all your data on all websites,” access to downloads, clipboard, file system, history, proxy, native messaging.

Cloned/typo names mimicking popular add-ons (e.g., “uBlock Origin Pro 2025”).

No/low reviews, sudden publisher change, or recent flood of 1-star reviews.

Ad injections/pop-ups/redirects started after installation.

High resource use: In Chrome press Shift+Esc → Task Manager → look for an extension using high CPU/memory when idle.

Enabled in Incognito/Private without a clear need.

Sideloaded (Installed “from disk” / “Unpacked”) and you didn’t do it.

4) Decide & Act

For each suspicious item:

Disable first (safer rollback):

Chrome/Edge: toggle Off.

Firefox: click … → Disable.

Test for 5–10 minutes of normal browsing: pop-ups gone? CPU normal? Redirects stopped?

If confirmed problematic or unnecessary, Remove:

Chrome/Edge: Remove → confirm.

Firefox: Remove → confirm.

Revoke Incognito/Private access for anything you keep, unless essential.

Restrict site access (Chrome/Edge): set to On click or Specific sites instead of All sites.

5) Clean-up & Health Check

Restart browser.

Clear cookies & site data for ad-spammy sites (Settings → Privacy → Clear browsing data → Cookies & Cached files).

Run built-in checks:

Chrome: Settings → Privacy & security → Safety Check.

Edge: Privacy, search, and services → Security → Microsoft Defender SmartScreen on.

Optionally scan with a trusted AV/anti-malware tool.

If symptoms persist, consider a browser reset (keeps bookmarks, removes extensions & custom settings):



........................................................................................................................................


Quick Paths per Browser  

Chrome (Desktop)

chrome://extensions → Developer mode ON

Details → check Permissions, Site access, Allow in Incognito

Toggle Off → test → Remove if needed

Settings → Privacy & security → Safety Check → run

Firefox (Desktop)

about:addons → Extensions

Click an add-on → check Permissions, Run in Private Windows

Disable → test → Remove

about:performance to spot heavy add-ons

Edge

edge://extensions

Details → Permissions / Site access

Toggle Off / Remove

Settings → Privacy → Security → ensure protections are on

Firefox (Android)

Menu ⋮ → Add-ons

Tap each → Permissions / Allow in private browsing

Disable/Remove and restart

How malicious extensions harm users (add 3–4 lines in your report)

Data theft: content scripts read page data, capture credentials, scrape forms.

Ad/SEO injection & redirect fraud: modifies pages you visit.

Tracking & fingerprinting: persistent surveillance across sites.

Cryptomining & performance drain: hidden background workers.

Chrome: chrome://settings/reset → Restore settings to their original defaults.

Edge: edge://settings/reset.

Firefox: Help → More troubleshooting information → Refresh Firefox.



<img width="1470" height="971" alt="image" src="https://github.com/user-attachments/assets/0883253d-0304-4df7-a54f-d9dc567c8abc" />
<img width="1745" height="798" alt="image" src="https://github.com/user-attachments/assets/598baf9d-b36f-4fd6-8738-4d5493330eeb" />

