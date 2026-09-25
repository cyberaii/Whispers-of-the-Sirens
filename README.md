# 🎀 Whispers of the Sirens

A small interactive music website that turns your mood into a random six-song playlist from a collection of Spotify tracks.

> *choose your mood, and let the jukebox decide.*

## About

**Whispers of the Sirens** is a beginner-friendly web development project built with **HTML, CSS, and JavaScript**.

The idea is simple: choose a mood, and the website randomly selects six tracks from a collection of Spotify songs. Each track is displayed using Spotify's embedded player so you can listen directly from the page.

The project focuses on practicing:

* JavaScript arrays and objects
* DOM manipulation
* Event listeners
* Randomization and array shuffling
* Dynamic HTML generation
* CSS styling and responsive layouts
* Embedding external content with `<iframe>`
* Git and GitHub version control

## Features

🎀 Six different moods
* ☀️ Sunny
* 🌙 Cozy
* 💔 Heartbreak
* 🔥 Hype
* 🧠 Focus
* 📼 Nostalgic
  Randomly selects six songs
  huffle/reroll for a different set of songs
  Spotify embedded players
  Responsive layout for smaller screens
  Green, pink, light yellow, and light blue color palette
  Mood-specific playlist names and descriptions

## Built With

* **HTML5** — page structure
* **CSS3** — styling, layout, colors, and responsive design
* **JavaScript** — mood selection, randomization, DOM manipulation, and Spotify embeds
* **Spotify Embed Player** — music playback
* **Git & GitHub** — version control and project hosting

The project is intentionally kept simple as a single-page website.

## How It Works

The website stores a collection of Spotify track IDs in a JavaScript array.

When a user selects a mood:

1. The selected mood is identified.
2. The track collection is shuffled.
3. Six tracks are randomly selected.
4. A playlist name is randomly chosen for the mood.
5. Six Spotify embedded players are generated dynamically.
6. The selected songs appear on the page.

Clicking **"shuffle a different six :3"** repeats the process and generates another set of tracks.

## Spotify Tracks

The project uses Spotify track links supplied for the project and converts their track IDs into Spotify embedded players.

This website **does not directly connect to a user's private Spotify account** or automatically retrieve their current Liked Songs.

Instead, the project uses a static collection of Spotify track IDs that were provided to the website.

## Running Locally

Clone the repository:

```bash
git clone https://github.com/cyberaii/Whispers-of-the-Sirens.git
```

Move into the project folder:

```bash
cd Whispers-of-the-Sirens
```

Then open `index.html` in your browser.

You can also use the **Live Server** extension in VS Code for easier development.

## Future Improvements

Possible improvements for future versions:

* Connect directly to Spotify using OAuth
* Automatically retrieve a user's actual Liked Songs
* Categorize songs based on mood
* Add animated backgrounds and transitions
* Allow users to save favorite generated playlists
* Improve the mobile experience
* Add song search and filtering
* Add mood intensity controls
* Store generated playlists locally
* Deploy the project as a live website

## What I Learned

This project helped me practice turning a simple idea into an interactive web application.

Some of the main concepts I worked with were **JavaScript objects and arrays, functions, event listeners, DOM manipulation, randomization, CSS layouts, and external embeds**.

It also gave me hands-on experience using **Git and GitHub** to track and publish my work.

## Author

**Jilian Rai Tusaneza**

BS Computer Science Student

GitHub: [@cyberaii](https://github.com/cyberaii)

