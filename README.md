# Infobip Forms API - Customer Feedback Demo

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2F<YOUR_USERNAME>%2F<YOUR_REPO_NAME>)

This repository contains a front-end demonstration of a customer feedback journey. It showcases how a user can be guided from an initial email capture through a multi-step feedback form, with data passed between pages using URL parameters.

The final form is designed to collect data and, in a real-world scenario, submit it to an endpoint like the Infobip Forms API.

---

## 🚀 Demo Flow

The user experience is split into three distinct steps:

1.  **📧 Landing Page (`index.html`)**
    * A simple page to capture the user's email address.
    * This simulates the starting point of a user journey.

2.  ** simulated-email (`email.html`)**
    * This page simulates the look and feel of an email asking for a satisfaction rating.
    * When the user clicks a rating (1-5), their choice and their email address are passed to the final form.

3.  **📝 Feedback Form (`form.html`)**
    * A multi-step questionnaire that receives the `email` and `rating` from the previous step.
    * The first question is dynamically customized based on the rating score (e.g., "Tell us a bit more about why you chose 4.").
    * The form collects additional feedback and prepares a final data object for submission.

---

## 💻 Technologies Used

This is a simple static website built with fundamental web technologies:

* **HTML5**
* **Tailwind CSS** (loaded via CDN)
* **Vanilla JavaScript (ES6)** for interactivity and state management.

No build tools or frameworks are required to run this project.

---

## 🛠️ Running Locally

To run this demo on your local machine:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)<YOUR_USERNAME>/<YOUR_REPO_NAME>.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd <YOUR_REPO_NAME>
    ```
3.  **Open the main file in your browser:**
    * Simply open the `index.html` file in your favorite web browser.

---

## 🌐 Deployment

This static site can be deployed for free on several platforms:

* **Vercel:** Recommended for its simplicity. Just connect your GitHub repository and it deploys automatically.
* **Netlify:** Another excellent, easy-to-use option with a similar workflow to Vercel.
* **GitHub Pages:** A solid choice, though it requires enabling it in the repository settings.

---

## 📂 File Structure

The repository contains the following core files:
