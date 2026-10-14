# sleep

A haunted Windows 95 browser experience: distressed paper, a pixelated horned portrait, cascading errors, and a synchronized devil jumpscare.

Live website: https://sleep-system-error.fuzzygleam16.chatgpt.site

## Run locally

From this folder, start a static web server:

```sh
python -m http.server 8000
```

Then open http://localhost:8000. Use an HTTP server rather than opening index.html directly so the audio files can preload.

## Experience

1. Click **Sleep** to open the warning and start the eerie guitar scrape.
2. Choose **Sleep anyway** for the 3–2–1 countdown.
3. Click **OK** on the portrait error to trigger cascading errors and screams.
4. Click **LEAVE** on the final dialog for the devil jumpscare and synchronized sting.
5. The experience ends with **THIS DOES NOT BELONG TO YOU.**

Use **SOUND: ON/OFF** to mute or enable audio. **Escape** or **ESC / WAKE UP** resets the sequence. Sound begins after user interaction. All cues use the requested 1.7× master-volume increase. Reduced-motion preferences disable the lunge animation.

## Files

- `index.html` — page and Windows-style interface
- `style.css` — monochrome paper, window treatments, and reveal effects
- `app.js` — interaction sequence and Web Audio playback
- `portrait.png` — generated grayscale devil portrait
- `audio/tension.mp3` — supplied eerie guitar scrape
- `audio/screams.mp3` — supplied vintage scream effects
- `audio/jumpscare.mp3` — supplied jumpscare sting
- `VT323.ttf` and `FONT-LICENSE.txt` — terminal font and its license

## Asset credits

Portrait generated for this project. Audio supplied by the project owner; embedded metadata credits Epidemic Sound. The audio files retain their original metadata. VT323 is distributed with its included font license. No blanket license is granted for the supplied audio or other assets.
