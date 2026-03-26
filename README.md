# Tiger Time

Tiger Time is a static productivity web app built for a hackathon. It combines a study-focused timer experience with music, motivational quotes, a lightweight to-do list, a mini calendar, and an alternate "Brainrot Mode" for a more chaotic study vibe.

## Features

- Pomodoro timer for study and break sessions
- Built-in music player with bundled audio tracks
- Motivational quote generator
- Slide-out to-do list
- Mini calendar panel
- Theme toggle on the main page
- Alternate Brainrot Mode with video background and meme-style presentation

## Project Structure

```text
.
|-- index.html              # Main Tiger Time experience
|-- styles.css              # Main page styling
|-- script.js               # Main page behavior
|-- brainrot-timer.html     # Alternate timer experience
|-- brainrot-style.css      # Brainrot Mode styling
|-- audio/                  # Music and timer sound effects
|-- img/                    # Icons, images, and background video
|-- fonts/                  # Local font assets
```

## Run Locally

This project does not require a build step or package installation.

1. Clone or download the repository.
2. Open `index.html` in a browser.

For best results, serve it with a simple local static server so media assets load consistently. Examples:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Demo Video

[![Watch the demo](https://img.youtube.com/vi/qURAf3fxYKg/maxresdefault.jpg)](https://youtu.be/qURAf3fxYKg)

[Watch the demo on YouTube](https://youtu.be/qURAf3fxYKg)

GitHub README files do not support inline YouTube playback, so the standard approach is a clickable thumbnail that opens the video.

## Pages

### Main Mode

The main page in `index.html` includes:

- clock display
- music player
- motivational quotes
- pomodoro modal
- calendar popout
- sign-in/sign-up mockup
- task list sidebar

### Brainrot Mode

The alternate page in `brainrot-timer.html` includes:

- meme-inspired UI
- looping background video
- adjustable pomodoro duration
- motivational pop-up quotes
- themed visuals for a more playful study session

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Font Awesome
- Iconify

## Notes

- This is a frontend-only project with no backend or persistent data storage.
- Task list entries, timer state, and UI changes reset on refresh.
- Some text rendering in the current source files shows encoding issues that may need cleanup later.

## License

No license is currently defined in this repository.
