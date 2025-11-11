# Stellenbosch Community Crime Watch

A free **Progressive Web App (PWA)** for the Stellenbosch community to **report crimes, mark hotspots, and illegal activities**, and **help each other stay safe**. The app works offline, is mobile-friendly, and can be installed on phones like a native app.

---

## **Features**

- **Submit Reports:** Crime, community hotspots, illegal drugs, and illegal alcohol locations.
- **Flag & Verify:** Help ensure reports are accurate by flagging false reports and verifying true ones.
- **Voting System:** Upvote 👍 or downvote 👎 reports to highlight the most important community concerns.
- **Dynamic Heatmap:** Visual map of reports, weighted by votes to show high-risk areas.
- **Neighborhood Search:** Quickly find reports in specific areas.
- **Photo Uploads:** Optional image uploads for context.
- **Offline & Installable:** Works offline after first load, can be added to phone home screens.
- **Email Notifications:** Optional alerts to Stellenbosch SAPS for crime reports using EmailJS.

---

## **Legend on Map**

| Marker Type             | Color       |
|-------------------------|------------|
| Crime report            | Red        |
| Hotspot                 | Orange     |
| Illegal drugs           | Purple     |
| Illegal alcohol         | Brown      |

- Heatmap intensity increases with community votes.
- Filters available: show/hide verified, flagged, or specific types.

---

## **How to Use**

1. Open the app in your browser or install it on your mobile device.
2. Submit a new report:
   - Select type (Crime, Hotspot, Illegal).
   - Fill in **Title, Description, Neighborhood**.
   - Optionally upload a photo.
   - Enter **latitude & longitude** or **mark directly on map**.
3. Interact with existing reports:
   - **Flag** if incorrect.
   - **Verify** if accurate.
   - **Upvote/Downvote** to influence the heatmap.
4. Use the **Neighborhood Search** to zoom into specific areas.
5. Toggle the **Heatmap** and filters to focus on relevant data.

---

## **Deployment**

Hosted on GitHub Pages:

[https://YOUR_USERNAME.github.io/stellenbosch-crime-watch/](https://YOUR_USERNAME.github.io/stellenbosch-crime-watch/)

**Mobile PWA Tips:**

- Add to Home Screen for quick access.
- Works offline after first load.
- Ensure location permissions are enabled for map interaction.

---

## **Setup / Development**

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/stellenbosch-crime-watch.git
