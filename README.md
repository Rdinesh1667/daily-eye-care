# Eye Reset --- 21-Day Eye-Care Guide

A lightweight, single-file HTML app for following a gentle eye-comfort
routine and tracking habits over 21 days. It includes an embedded
YouTube follow-along video, a daily checklist, a progress calendar,
notes, and JSON backup/restore.

> **Important:** This is a wellness and eye-comfort tracker, not medical
> treatment. Eye exercises are not proven to reverse refractive errors
> or remove the need for prescribed glasses.

## Features

-   **YouTube follow-along video** --- embeds
    [2VmjCxXBW-c](https://youtu.be/2VmjCxXBW-c), starting at
    approximately **0:37**.
-   **21-day tracker** --- select a day and check off five habits.
-   **Progress calendar** --- see daily completion and overall progress.
-   **Daily notes** --- record outdoor time, comfort, symptoms, and
    observations.
-   **Automatic saving** --- stores progress in the current browser
    using `localStorage`.
-   **Backup and restore** --- export progress as a JSON file and import
    it later.
-   **Responsive layout** --- suitable for desktop and mobile browsers.
-   **Safety guidance** --- reminders about avoiding direct sun-gazing
    and pressure on the eyes.

## Getting started

### Option 1: Open the HTML file

1.  Save `eye-reset-detailed-21-day-guide.html` to your computer.
2.  Open it in a modern browser such as Chrome, Firefox, Edge, or
    Safari.
3.  Use the video at the top, then select a day and complete the
    checklist.

Some browsers or YouTube settings may prevent video playback when the
page is opened directly as a local file. If that happens, try Option 2.

### Option 2: Run a local web server

You need Python 3 installed.

1.  Open a terminal in the folder containing the HTML file.

2.  Run:

    ``` bash
    python3 -m http.server 8000
    ```

3.  Open `http://localhost:8000/eye-reset-detailed-21-day-guide.html` in
    your browser.

4.  Stop the server with `Ctrl+C` when finished.

No npm install, build step, database, or backend server is required.

## Daily habits tracked

1.  Gentle massage around the orbital bone (never press on the eyeball).
2.  Comfortable eye movements and natural blinking.
3.  Outdoor daylight time.
4.  Screen breaks and evening comfort.
5.  Relaxation or rest.

The app also includes expandable instructions, a 21-day calendar, an
optional starting and Day 21 observation log, and fields for outdoor
minutes and daily comfort notes.

## Saving and backing up progress

-   Entries are saved in browser local storage on the device and browser
    where you use the app.
-   Clearing browser data, using another browser/device, or using a
    different browser profile may make saved progress unavailable.
-   Click **Export backup (JSON)** to download a backup.
-   Click **Import backup** to restore a previously exported JSON file.
-   **Reset all progress** clears the app's saved tracking data after
    confirmation.

Export a backup periodically if you want to preserve your entries.

## YouTube video troubleshooting

The embedded player may not work if the video owner has disabled
embedding, YouTube requires a browser session, or browser privacy
settings block the player.

-   Use **Open video on YouTube** if the embedded player does not load.
-   If opening the HTML file directly causes an embed error, try the
    local web server steps above.
-   Video URL: https://youtu.be/2VmjCxXBW-c

The app cannot override restrictions set by YouTube or the video owner.

## Safety notes

-   **Never look directly at the sun**, including at sunrise or sunset.
-   Never press on your eyeballs or massage a painful or injured eye.
-   Stop an activity if it causes pain, dizziness, headache, double
    vision, or worsening symptoms.
-   Continue wearing prescribed glasses or contact lenses as directed;
    do not change a prescription based on this routine.
-   Seek urgent medical care for sudden vision loss, severe eye pain,
    new flashes or many new floaters, or a curtain/shadow over your
    vision.
-   Arrange an eye examination for persistent blur, eye strain, or
    changing vision.

## Technology

-   HTML
-   CSS
-   Vanilla JavaScript
-   Browser `localStorage`
-   YouTube embedded player

## Project files

``` text
eye-reset/
├── eye-reset-detailed-21-day-guide.html
└── README.md
```

Place `README.md` in the same folder as the HTML app.

## License

No license is specified by this project. Add a license file if you
intend to distribute or reuse the app publicly.
