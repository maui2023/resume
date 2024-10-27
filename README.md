
# My Resume

Welcome to the GitHub repository for my personal resume website! This project is a fully responsive HTML, CSS, and JavaScript resume that is deployed through GitHub Pages for easy access and distribution. You can view it [here](https://maui2023.github.io/resume/).

![Resume Screenshot](https://maui2023.github.io/resume/images/screenshot.png)

## 🚀 Features

- **Responsive Design:** Built with HTML, CSS, and JavaScript to adapt across devices.
- **PDF Generation:** Quickly generate a downloadable PDF version of the resume.
- **Continuous Deployment with GitHub Pages:** Every change pushed to `main` branch triggers an automatic deployment to GitHub Pages.

## 📄 View Resume

To view the resume online, visit: [https://maui2023.github.io/resume/](https://maui2023.github.io/resume/)

## 📄 Download PDF

1. **Auto-Generated PDF:** Click on the "Download PDF" button on the site to generate and download a PDF of the resume.
2. **Manual Download:** Alternatively, you can download the PDF from the repository in the `pdf/` folder.

## 🛠️ Technologies Used

- **HTML + CSS + JavaScript:** For structuring and styling the resume.
- **GitHub Pages:** For automated deployment, configured to deploy from the `main` branch.
- **JS PDF Library (optional):** If a library like `jsPDF` is used, it enables PDF generation directly from the browser.

## 📥 Installation & Development

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/maui2023/resume.git
   ```
2. **Navigate to the Directory:**
   ```bash
   cd resume
   ```
3. **Open the Resume Locally:**
   Open `index.html` in your browser to view the resume locally.

## 🚀 GitHub Pages Deployment

This project is automatically deployed to GitHub Pages every time there is a push to the `main` branch. Make sure your GitHub Pages is configured to deploy from the `main` branch under your repository's settings.

1. **Navigate to Repository Settings > Pages.**
2. **Select `main` as the source branch** and confirm.
3. Access the website at `https://<your-github-username>.github.io/resume/`.

## 📌 Custom Domain Setup (Optional)

If you have a custom domain, configure it in the repository settings under Pages and add a `CNAME` file to the root of the repository.

## 💡 How PDF Generation Works

The PDF generation can be handled using JavaScript, with libraries like `jsPDF` or custom JavaScript to convert HTML content to PDF format. This feature allows users to download the resume directly from the site.

To integrate PDF generation, see the following sample code snippet (assuming you're using `jsPDF`):

```javascript
// Generate PDF
function generatePDF() {
    const doc = new jsPDF();
    doc.fromHTML(document.body, 10, 10, {
        'width': 180
    });
    doc.save('My_Resume.pdf');
}
```

> **Note:** Include a "Download PDF" button that triggers `generatePDF()`.

## 🤝 Contributions

If you'd like to suggest improvements, feel free to fork the repository and open a pull request. All contributions are welcome!

## 📧 Contact

For any questions, feel free to reach out.

---

Thank you for checking out my resume!
