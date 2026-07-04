# Dieta Juli

Personal meal plan tracking app — built as an installable PWA for iPhone.

---

## What is this?

A progressive web app (PWA) built from scratch to consult my weekly meal plan quickly and without friction. The plan comes from my nutritionist **David Gracia** and is adapted to my lifestyle: I work from home, cook only on certain days, and prioritize batch preparation.

This project is part of a broader personal organization system covering five areas: **finances, nutrition, training, studies and entrepreneurship (Lumo)**.

---

## Features

- **Weekly menu** — 7 days with all meals, portions and exact grams
- **Day navigation** — swipe between days with arrows
- **Day badges** — see at a glance whether you cook today or it's a pre-prepped day
- **Active warnings** — alerts to confirm with the nutritionist (oat drink, prawns)
- **Organization** — real weekly routine: when to cook, how to batch prep, weighing tips
- **Shopping list** — interactive checkboxes, by category, tailored to Mercadona and Gadis Arteixo
- **Works offline** — installable on iPhone from Safari

---

## How to install on iPhone

1. Open **Safari** and go to: `https://jsazevedoja.github.io/dieta-juli/dieta-juli.html`
2. Tap the share icon (square with arrow ↑)
3. Select **"Add to Home Screen"**
4. Confirm — it appears as an app on your screen

---

## How to update the content

When the meal plan changes or adjustments are needed:

1. Go to the repository on GitHub: `github.com/jsazevedoja/dieta-juli`
2. Open `dieta-juli.html`
3. Click the **pencil** to edit
4. Replace the content with the new version
5. Click **"Commit changes"**
6. Wait **1–2 minutes** — the app updates automatically

To see the changes on iPhone: close the app completely (swipe up) and reopen it.

---

## How to add or update the favicon

1. Create a **512×512px** image (PNG)
2. Upload it to the repository as `favicon.png`
3. In the `<head>` of the HTML, add before `<title>`:
```html
<link rel="icon" type="image/png" href="favicon.png">
<link rel="apple-touch-icon" href="favicon.png">
```
4. Commit and done

---

## Project structure

```
dieta-juli/
├── dieta-juli.html   # Full app (HTML + CSS + JS in one file)
├── favicon.png       # App icon
└── README.md         # This file
```

---

## Personal context

I'm Brazilian living in Arteixo, Galicia (Spain). I work full time Monday to Friday from home. I have a nutritionist and a personal trainer — the detailed plans come from them, I handle execution and organization.

My cooking routine: **Monday, Wednesday and Friday** I cook for myself and Jesús (lunch). Dinners I always make alone. On Tuesdays, Thursdays, Saturdays and Sundays I eat what was prepped in advance.

This repository is part of a larger project called **Lumo** — a company in progress building SaaS digital products for small businesses, where the programming studies I'm doing from scratch directly feed into development.

---

## Tech

HTML · CSS · Vanilla JavaScript — no frameworks, no external dependencies. A single file that works in any browser and installs as a native app on iOS.

---

*Last plan update: July 2026 — David Gracia (nutritionist)*
