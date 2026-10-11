# 🧠 SeizureGuard – Epilepsy Early Warning & Care Circle

A simple, professional healthcare website that helps people with epilepsy detect an approaching seizure from their symptoms, get safety guidance, and alert 3 trusted contacts.

## Features
- 🩺 **Symptom check**: 14 warning signs + 8 triggers with a weighted scoring dataset → Low / Moderate / High risk
- 💡 **Solutions**: immediate safety steps and trigger-specific advice
- 👥 **My Contacts**: register 3 close contacts (name, phone, relation) + medical note
- 🚨 **Alert Center**: pre-filled SMS / WhatsApp / Call with GPS location, per-contact "sent" status and alert log
- 🩹 **First-aid guide** for helpers, 📋 **history** of checks
- 🌗 Responsive, colourful UI with dark mode

## Tech
HTML, CSS and vanilla JavaScript only. Data is saved in the browser's `localStorage`. No installation needed.

## Run locally
1. Download or clone this repo
2. Double-click `index.html` (opens in your browser)

## Limitations
- Alerts open the user's SMS/WhatsApp app; fully automatic sending needs a backend + SMS API (e.g. Twilio).
- This is a screening aid, **not a medical diagnosis**. Consult a neurologist. In an emergency call 112 (India).

## Future scope
Medicine reminders, seizure diary charts, Hindi language, automatic SMS via Twilio, user login.
