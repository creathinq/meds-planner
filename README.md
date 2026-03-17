# Meds Planner & Tracker

A simple, web-based, client-side, zero-backend, privacy-focused generator for custom printable medication planner and tracker tables.

## Features
* **Privacy-First:** All data is stored locally in your browser. No accounts, no tracking, no cloud.
* **Offline Support:** Full PWA support allows the app to work without an internet connection once installed.
* **Print-Optimized:** Custom CSS ensures generated tables look perfect on paper (optimized for Landscape mode).
* **Responsive Design:** Easy to use on phones and desktops. While the preview table might require scrolling on small screens, it is designed specifically to be printed and displayed (e.g., on a fridge), and tick a checkbox with a pen.
* **Multilingual:** Supports English, Slovak, Portuguese, German, Italian, French, and Spanish.

## How to Use
1. **Setup:** Enter the patient's name (optional) and start date. Set the period (number of days). 
    * *Tip: If a large table won't fit on one A4 page, try creating multiple smaller tables for different weeks.*
2. **Add Meds:** Enter medication names and dosages. You can leave fields empty if you prefer to write them by hand after printing.
3. **Select Times:** Toggle the dosage times you wish to have (Morning, Lunch, Evening) for each medication.
4. **Generate & Print:** Click **Generate Table** to preview, then **Print** to open the system dialog. Use **Reset** to clear the form.

## Technical Details
* **No Backend:** Pure client-side logic; your data never leaves your device.
* **Vanilla Stack:** Built with standard HTML5, CSS3, and Vanilla JavaScript.
* **Zero Dependencies:** No external frameworks or tracking scripts.
* **License:** MIT License.
