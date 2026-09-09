
# ⚡ MK HTML Cloud Studio (Permanent & Secure)

MK HTML Cloud Studio is a fast, lightweight, browser-based editor that allows users to write, preview, and host HTML code snippets permanently. Powered by GitHub Pages, it provides an instant environment to generate shareable links for static web code without complex deployment pipelines.

## 🚀 Features

- **Live HTML Preview:** Render your markup instantly in the browser.
- **Permanent Link Generation:** Generate a static, shareable URL for your code.
- **Local Storage / History:** Automatically tracks and saves your recent work locally.
- **No Setup Required:** Zero dependencies, zero configurations—just open and build.

## 🛠️ How to Use

1. **Open the Studio:** Navigate to your live deployment URL.
2. **Write or Paste Code:** Input your HTML, CSS, or JavaScript directly into the workspace.
3. **Generate Link:** Click the **Generate Link** button to create a permanent, unique URL for your webpage.
4. **Access History:** Review or reload past snippets using the **📁 History** panel.

## 📂 File Structure

```text
├── index.html       # The main entry point and UI for the Cloud Studio
├── README.md        # Project documentation
└── [assets/js/css]  # Accompanying script and style dependencies (if applicable)
```

## ⚙️ Local Development & Deployment

### Running Locally
Since this is a fully static client-side application, you can run it locally without an application server:
1. Clone the repository:
   ```bash
   git clone https://github.com
   ```
2. Open the exact `index.html` file (using lowercase letters) directly in any modern web browser.

### Deploying to GitHub Pages
To host your own version of this studio permanently:
1. Push the code to your GitHub repository.
2. Navigate to **Settings** -> **Pages**.
3. Under **Build and deployment**, set the source to **Deploy from a branch**.
4. Select the `main` (or `master`) branch and the `/ (root)` folder, then click **Save**.

## 🔒 Security & Performance
- All links are generated securely on the client side.
- Hosted entirely on enterprise-grade GitHub Pages infrastructure for 99.9% uptime.

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
