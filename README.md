# SARAN – Go Anywhere — Legal, Privacy & Data Compliance Portal

Official static website hosting the **Privacy Policy**, **Terms of Service**, **Data Sources & Disclaimer**, and **Account Deletion** portal for **SARAN – Go Anywhere** (Android Package: `com.sarandev.transitapp`), published by **Saran Mobility**.

Designed for complete compliance with **Google Play Developer Policies**, specifically:
- **Misleading Claims & Non-Government Disclaimer**
- **Government Information & Official GTFS Source Links**
- **User Data & On-Device Location Transparency**
- **Publicly Accessible Account Deletion URL**

---

## 📁 Project Structure

```text
SARAN privacy/
├── index.html            # Privacy Policy (Google Play Policy URL)
├── data-sources.html     # Transport Data Sources & Non-Government Disclaimer
├── terms.html            # Terms of Service & Limitations of Liability
├── delete-account.html   # Account & Data Deletion Request page
├── style.css             # Unified responsive stylesheet
├── saran-logo.webp       # Brand logo
├── hero-desktop.jpg      # Desktop illustration (1024 × 576, 16:9)
├── hero-tablet.jpg       # Tablet illustration (1024 × 768, 4:3)
├── hero-mobile.jpg       # Mobile illustration (576 × 1024, 9:16 portrait)
└── README.md             # Project documentation & compliance guide
```

---

## ✨ Features & Google Play Policy Alignment

- **100% Static & Fast**: Pure HTML5 and CSS3. Zero server-side tracking, zero third-party marketing cookies, lightning-fast loading speeds on desktop and mobile.
- **Independent Non-Government Disclaimer**: Clear and prominent disclosures across all pages stating that SARAN is an independently developed application and is **not affiliated with, endorsed by, or operated by the Government of India, Indian Railways, or any state transit corporation**.
- **Official Open GTFS Source Links**: Direct hyperlinks to original government open transit publications:
  - **Delhi Open Transit Data (Bus GTFS):** [https://otd.delhi.gov.in/documentation/](https://otd.delhi.gov.in/documentation/)
  - **Telangana State Road Transport Corporation (TGSRTC Bus GTFS):** [https://tgsrtc.telangana.gov.in/open-data](https://tgsrtc.telangana.gov.in/open-data)
  - **Hyderabad Metro Rail Limited (HMRL Metro GTFS):** [https://hmrl.co.in/open-data/](https://hmrl.co.in/open-data/)
- **Independent Railway Verification**: Direct links to official Indian Railways inquiry portals ([indianrail.gov.in](https://www.indianrail.gov.in/) and [NTES](https://enquiry.indianrail.gov.in/ntes/)).
- **Transparent Transit Data Categorization**: Clear differentiation between official open GTFS feeds, independently compiled regional transit data (such as Kolkata bus, tram, and river ferry services), and SARAN-generated algorithmic route calculations.
- **On-Device Location & Navigation GPS Transparency**: Explicit disclosure that navigation GPS coordinates are evaluated **locally on the user's device** and are not uploaded to servers or sold to third parties.
- **Web-Based Account Deletion**: Publicly accessible, no-login-required account deletion request portal fulfilling Google Play Data Safety requirements with documented 30-day deletion processing.

---

## 🚀 Local Preview

You can host and preview the static site locally using any lightweight static server:

### Using Python:
```powershell
python -m http.server 8000
```
Then visit:
- **Privacy Policy:** [http://localhost:8000/](http://localhost:8000/)
- **Data Sources & Disclaimer:** [http://localhost:8000/data-sources.html](http://localhost:8000/data-sources.html)
- **Terms of Service:** [http://localhost:8000/terms.html](http://localhost:8000/terms.html)
- **Delete Account:** [http://localhost:8000/delete-account.html](http://localhost:8000/delete-account.html)

### Using Node.js:
```powershell
npx serve .
```

---

## 🌐 GitHub Pages Deployment

The live site is hosted on GitHub Pages:
**Live Portal:** [https://dragrex1.github.io/saran-privacy/](https://dragrex1.github.io/saran-privacy/)

### Deployment Steps:
1. Commit all modified files:
   ```bash
   git add index.html terms.html delete-account.html data-sources.html style.css README.md
   git commit -m "feat: add data-sources page and improve Google Play compliance"
   git push origin main
   ```
2. Verify GitHub Pages is configured to serve from the `main` branch (root `/`).
3. Verify all live pages load over HTTPS.

---

## 📱 Google Play Console URLs

When completing or updating your app details in the **Google Play Console**:

| Field in Play Console | Official URL |
|---|---|
| **Privacy Policy URL** | `https://dragrex1.github.io/saran-privacy/` |
| **Account Deletion URL** | `https://dragrex1.github.io/saran-privacy/delete-account.html` |
| **Data Sources & Disclaimer URL** | `https://dragrex1.github.io/saran-privacy/data-sources.html` |
| **Terms of Service URL** *(optional)* | `https://dragrex1.github.io/saran-privacy/terms.html` |

---

## ⚠️ Important: Google Play Store Listing Requirements

Under Google Play's **Government Information and Misleading Claims** policy, updating the website alone is not enough. You **must also include** the non-government disclaimer and official data source links in the **Store Listing Description** in Google Play Console:

### Recommended Play Store Description Addendum:
```text
IMPORTANT DISCLAIMER:
SARAN – Go Anywhere is an independently developed application published by Saran Mobility. SARAN is not an official government application and is not affiliated with, endorsed by, authorized by, or operated by the Government of India, the Ministry of Railways, Indian Railways, or any state transit corporation. 

SARAN utilizes publicly published open transit data (GTFS) from official portals where available:
- Delhi Open Transit Data: https://otd.delhi.gov.in/
- TGSRTC Open Data: https://tgsrtc.telangana.gov.in/open-data
- Hyderabad Metro Rail: https://hmrl.co.in/open-data/
For official Indian Railways train inquiry, please visit: https://www.indianrail.gov.in/ and https://enquiry.indianrail.gov.in/ntes/
For complete data source disclosures and attributions, visit: https://dragrex1.github.io/saran-privacy/data-sources.html
```

---

## 📬 Contact & Publisher

- **Application:** SARAN – Go Anywhere
- **Android Package:** `com.sarandev.transitapp`
- **Publisher / Developer:** Saran Mobility
- **Developer Contact:** [bijoymandi50@gmail.com](mailto:bijoymandi50@gmail.com)
