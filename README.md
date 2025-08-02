# 🌟 Fantasy Image Gallery 🌟

## A Mystical Collection with a Dynamic Theme

Welcome to the Fantasy Image Gallery! This project showcases a collection of captivating fantasy-themed images, brought to life with an interactive dark and light mode toggle. Experience the magical visuals in your preferred ambiance.

---

## ✨ Live Demo

Explore the gallery live on Azure:

🔗 **[CLICK HERE TO GO TO THE GALLERY](https://myfantasygallerygkm.z30.web.core.windows.net/)**

---

## 🖼️ Features

* **Responsive Image Gallery:** A beautiful, responsive grid layout for displaying fantasy artwork.
* **Dark/Light Mode Toggle:** Seamlessly switch between a warm, mystical light theme and a deep, enchanting dark theme.
* **Persistent Theme Preference:** Your chosen theme is saved and remembered for future visits using Local Storage.
* **Pure Front-End:** Built entirely with HTML, CSS, and JavaScript, making it lightweight and fast.
* **Azure Static Website Hosting:** Deployed efficiently on Azure Blob Storage, leveraging its static website hosting capabilities.

---

## 🚀 Technologies Used

* **HTML5:** For the core structure of the web page.
* **CSS3:** For styling the gallery, creating the fantasy aesthetic, and implementing the theme switch visuals.
* **JavaScript (ES6+):** For dynamic image loading, managing the dark/light mode toggle, and persisting user preferences.
* **Azure Blob Storage:** Used for hosting the static website files.

---

## 🛠️ How to Run Locally

To get a local copy up and running, follow these simple steps.

1.  **Clone the Repository (or download the files):**
    If this were a Git repository, you would clone it:
    ```bash
    git clone [FANTASY](https://github.com/gkmfrombs/fantasy-gallery) 
    ```
    Alternatively, if you downloaded the project files as a ZIP:
    Unzip the `fantasy-gallery.zip` file to your desired location.

2.  **Navigate to the Project Directory:**
    Open your file explorer or terminal and go into the `fantasy-gallery` folder.

3.  **Open `index.html`:**
    Simply double-click `index.html` in your file explorer. It will open in your default web browser.

---

## ☁️ Azure Deployment Notes

This project is deployed as a static website on Azure Blob Storage.

### Key Azure Services Used:

* **Resource Group:** `fantasyGalleryRG` (or `myStaticWebsiteRG` if you reused the previous one) - A logical container for Azure resources.
* **Storage Account:** `myfantasygallery123` (or your chosen unique name) - Stores all the website assets (HTML, CSS, JS, images).
* **Static Website Hosting:** A feature enabled on the Storage Account to serve web content directly from the `$web` container.

### Deployment Steps Summary:

1.  **Create a Resource Group** in the Azure Portal.
2.  **Create a Storage Account** within that Resource Group.
3.  **Enable Static Website Hosting** in the Storage Account settings, setting `index.html` as the index document. This generates the primary endpoint URL.
4.  **Upload all project files** (`index.html`, `script.js`, `css/style.css`, and all files in `images/`) to the `$web` container, preserving the folder structure (e.g., `css/style.css` goes into a `css` folder within `$web`, `images/image1.jpg` goes into an `images` folder within `$web`). Azure Storage Explorer is recommended for easier folder uploads.

---

## 🔮 Future Enhancements

* **Image Lightbox/Modal:** Implement a feature to view larger versions of images when clicked.
* **Search/Filter Functionality:** Add a search bar or filter options based on image categories (e.g., "Creatures," "Landscapes").
* **Preloader:** A simple loading animation while images are being fetched.
* **Azure Static Web Apps:** Migrate to Azure Static Web Apps for integrated CI/CD directly from a Git repository (e.g., GitHub), simplifying deployment and offering more features like custom domains out-of-the-box.
* **Custom Domain:** Connect a custom domain name (e.g., `www.yourfantasygallery.com`) to the deployed site.
* **Accessibility Improvements:** Enhance keyboard navigation and ARIA attributes for better accessibility.

---

## 🧑‍💻 Author

[Guddu Mishra ] 

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
*(If you wish to include a license. You might need to create a `LICENSE` file in your root directory if you want a formal license.)*

---

**Thank you for visiting the Fantasy Image Gallery!**
