# Systems Ten — Digital Agency Website

Systems Ten delivers AI automation, web development, UI/UX design, and growth marketing. This repository contains the static website representing the agency's presence and services.

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/AnasSajjadHaider/SystemsTen)

## 🚀 Live Preview & Deployment

You can deploy this website live to **Render** in just one click using the button above. 

Alternatively, to deploy manually:
1. Go to your [Render Dashboard](https://dashboard.render.com/).
2. Click **New +** and select **Static Site**.
3. Connect this GitHub repository (`AnasSajjadHaider/SystemsTen`).
4. Set the following configuration:
   - **Build Command**: (leave blank)
   - **Publish Directory**: `.` (root directory)
5. Click **Create Static Site**.

---

## 🛠️ Features & Pages

* **Home Page (`index.html`)**: General overview of Systems Ten, services grid, bento layout, customer reviews, and a contact form.
* **Services Page (`landing-page.html`)**: Deep dive into the 14 service offerings across 4 main categories.
* **About Page (`the-observer.html`)**: Inside look at the agency, our telemetry feed, and our process.
* **Redirect Page (`timer.html`)**: Direct utility helper redirect.

---

## 💻 Local Development

To run the site locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/AnasSajjadHaider/SystemsTen.git
   cd SystemsTen
   ```
2. Start a local server. For example, using Python:
   ```bash
   python -m http.server 8000
   ```
3. Open [http://localhost:8000](http://localhost:8000) in your browser.
