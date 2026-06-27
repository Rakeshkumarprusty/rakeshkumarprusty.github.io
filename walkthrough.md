# Developer Website Walkthrough & Deployment Guide

This document summarizes the files created for your Developer compliance website and outlines step-by-step instructions on how to publish it live for free so you can submit it to BillDesk.

---

## 1. Created Code Files

We built a lightweight, premium, compliance-ready website using standard static files. You can find them in your workspace:

* [styles.css](file:///mnt/ntfsdrive/Anti%20Gravity%20Projects/Developer%20Page/styles.css) — Custom stylesheet featuring slate/indigo dark-mode, glassmorphism cards, responsive breakpoints, and smooth scroll styles.
* [script.js](file:///mnt/ntfsdrive/Anti%20Gravity%20Projects/Developer%20Page/script.js) — Scroll detectors, year counters, mobile menu animations, and contact form event handlers.
* [index.html](file:///mnt/ntfsdrive/Anti%20Gravity%20Projects/Developer%20Page/index.html) — Landing portfolio showing your skills, bio, service menu, and rates ($50/hour consultation).
* [privacy.html](file:///mnt/ntfsdrive/Anti%20Gravity%20Projects/Developer%20Page/privacy.html) — Regulatory Privacy Policy with details of data collection, storage, and a designated Grievance Redressal Officer table.
* [terms.html](file:///mnt/ntfsdrive/Anti%20Gravity%20Projects/Developer%20Page/terms.html) — Service agreement containing intellectual property rules, hourly billing structures, and Bangalore, Karnataka legal jurisdiction.
* [refund.html](file:///mnt/ntfsdrive/Anti%20Gravity%20Projects/Developer%20Page/refund.html) — Policy declaring milestone boundaries, non-refundable hourly metrics, and payment gateway return timelines (5-7 business days).
* [contact.html](file:///mnt/ntfsdrive/Anti%20Gravity%20Projects/Developer%20Page/contact.html) — Contact page with feedback forms, physical address, and grievance redressal channels.

---

## 2. Local Preview & Verification

To verify that the pages are fully functional, responsive, and looking premium, a local HTTP server has been started in the background.

* **Local Preview Link:** Open [http://localhost:8000](http://localhost:8000) in your web browser.
* **Verification Checklist:**
  * Try resizing your browser window to test the mobile layout.
  * Check the hamburger menu in mobile mode.
  * Verify that all links in the footer (`Privacy Policy`, `Terms & Conditions`, `Refund & Cancellation`, `Grievance Redressal`) direct to their corresponding pages.
  * Test filling out the contact form and observe the animated success state when clicking "Send Message."

---

## 3. How to Host for Free on GitHub Pages

Follow these step-by-step instructions to get your website online at a secure HTTPS address (e.g., `https://yourusername.github.io/`):

### Step A: Set up your GitHub Repository
1. Log in to (or create) your account on [GitHub](https://github.com/).
2. In the top-right corner, click the **`+`** icon and select **New repository**.
3. Configure the repository:
   * **Repository name:** Enter `rakeshprusty` (or any name you prefer). If you want the site to be hosted directly at your main domain (e.g. `https://username.github.io/`), name the repository exactly `your-github-username.github.io`.
   * **Public/Private:** Select **Public** (required for free GitHub Pages).
   * **Initialize repository:** Leave all checkboxes (README, .gitignore, license) unchecked.
4. Click **Create repository**.

### Step B: Upload Files Using the Web Interface (Easiest)
1. On your new repository page, click the link that says **"uploading an existing file"** near the top.
2. Drag and drop all **7 files** from your local `/mnt/ntfsdrive/Anti Gravity Projects/Developer Page/` folder:
   * `index.html`
   * `privacy.html`
   * `terms.html`
   * `refund.html`
   * `contact.html`
   * `styles.css`
   * `script.js`
3. Wait for the files to finish loading.
4. At the bottom, add a commit message (e.g. `Initial commit of compliance website`) and click **Commit changes**.

*Alternatively, if you prefer the Git CLI, you can initialize a git repository locally in your workspace, add the remote, commit, and push.*

### Step C: Activate GitHub Pages
1. In your GitHub repository page, click on the **Settings** tab (the gear icon at the top of the repository menu).
2. On the left sidebar under the "Code and automation" section, click on **Pages**.
3. Under **Build and deployment** -> **Branch**:
   * Change the dropdown from `None` to **`main`** (or `master`).
   * Leave the folder dropdown set to **`/ (root)`**.
4. Click the **Save** button.

### Step D: Access Your Live Website
* After clicking save, GitHub will start a deployment task in the background.
* Wait about 1–2 minutes, then refresh the **Settings > Pages** page.
* You will see a box at the top saying: **"Your site is live at..."** with a clickable link (e.g., `https://username.github.io/rakeshprusty/`).
* Copy this URL and submit it as your Developer site inside the BillDesk verification form!
