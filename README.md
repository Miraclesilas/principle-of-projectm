# Principles of Project Management — CBT Practice App

A professional, static, browser-based CBT practice application for **Principles of Project Management**, designed for educational use.

## Features

- Student registration and login modal
- Local browser profile storage using `localStorage`
- 120-question database covering the course broadly
- Objective, subjective and theory sections
- Mixed examination mode
- Random question selection
- Randomized objective options
- Configurable number of questions
- Optional 30/60/90-minute timer
- Automatic scoring and percentage generation
- Section-by-section performance report
- Answer review
- Local result history
- Responsive UI for phones, tablets and desktop
- GitHub Pages compatible; no build step required

## Important note about static authentication

This is an educational static web application. Registration/login data is stored in the user's browser using `localStorage`; it is **not secure server-side authentication** and should not be used for sensitive credentials or official examination records. For a production examination platform, replace this layer with a secure backend and hashed/password-managed authentication.

## GitHub Pages deployment

1. Put `index.html`, `styles.css`, and `app.js` in the repository root.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the default branch and `/ (root)`.
5. Save and wait for GitHub Pages to publish.

The application has no external runtime dependency beyond the Google Fonts CDN; it will still function if the font request is unavailable.

## Attribution

Built by **Miracle Silas** — Department of Public Administration, Uyo.

Created for educational purposes.
