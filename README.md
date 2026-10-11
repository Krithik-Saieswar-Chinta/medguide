# MedGuide

A medicine usage guide that searches the official US FDA drug label database (openFDA) for thousands of medicines.

## Features
- Single `index.html` file, no dependencies or API key
- Search by brand or generic name (supports partial names)
- Shows the official label sections: uses, dosage and how often, warnings, interactions, side effects, overdose, storage
- Light and dark mode, mobile friendly

## Run it
Open `index.html` in any web browser.

## Publish with GitHub Pages
1. Push this repository to GitHub.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Limitations
- Needs an internet connection to search.
- Limited to medicines in the US FDA label database. Local brand names from other countries may need the generic name instead.
- Label text is technical and follows US labelling.
- Photo recognition is not included: a photo can be attached for reference, and the name is typed manually.

## Disclaimer
This project is for educational purposes and shows information from official drug labels. It is not medical advice and is not a substitute for a doctor, pharmacist or the leaflet in the medicine package. Verify all content before relying on it.

## Data source
Drug label data: [openFDA](https://open.fda.gov/apis/drug/label/) (US Food and Drug Administration). This project is not affiliated with or endorsed by the FDA.
