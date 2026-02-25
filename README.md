# obs-stopwatch-with-millis

Simple stopwatch providing milliseconds for use as an OBS browser source.

## Features

- Displays elapsed time in `HH:MM:SS.mmm` format
- Start / Stop and Reset controls
- Transparent background — suitable for use as an OBS overlay
- Updates every 10 ms for smooth millisecond display

## Usage in OBS

1. In OBS, add a **Browser** source to your scene.
2. Check **Local file** and browse to `index.html`, **or** paste the full path as a `file://` URL.
3. Set the width and height to match your desired overlay size (e.g. 600 × 120).
4. Click **OK**.

The stopwatch will appear in your scene. Use the **Start / Stop** and **Reset** buttons to control it, either directly in the browser source preview or via an OBS browser interaction window (*Right-click source → Interact*).

## Standalone use

Open `index.html` in any modern web browser to use the stopwatch without OBS.
