# 📘 Project Setup & Run Instructions

This assignment can be reviewed and run in **two different ways**:

- ✅ **Full Project Setup** (Recommended – shows final output instantly)  
- ✅ **Theme-Only Setup** (Manual setup to verify theme architecture & coding skills)

You can download the project files from the Google Drive link below:

👉 https://drive.google.com/drive/folders/1Srl-3SJeaOm0JZiwM2f9wgkWt78y6p42?usp=sharing  

Inside the drive, there are two folders:

- **Complete Project**  
- **Theme**

> **Note:** If you are not able to download files from Google Drive, you can download the same project from GitHub:  
> 👉 https://github.com/satyakeeray/ot-machine-test  

---

## ✅ Option 1: Run the Complete Project (Recommended)

This option provides a fully working setup with expected output.  
It includes:

- Complete WordPress setup  
- Theme  
- Required plugins  
- Media files  
- Database file (`.sql`)  
- Preconfigured pages and content  

### 🔧 Setup Steps

1. Download and extract the **Complete Project** folder.
2. Copy the extracted WordPress project into your local server directory:

   - **XAMPP** → `htdocs/`  
   - **MAMP** → `htdocs/`  
   - **LocalWP** → Site folder  

3. Create a new database using **phpMyAdmin**.
4. Import the provided database file: db_my_service.sql
5. Update your database credentials in: wp-config.php
6. Open the site URL in your browser.

✅ After completing these steps, the website will load with the **expected output** (homepage layout, ACF blocks, services section, contact form, admin panel, etc.).

---

## ✅ Option 2: Run Only the Theme (Manual Setup)

This option is intended to review the **theme structure, ACF block implementation, and dynamic rendering**.

### 🔧 Setup Steps (Follow This Order)

### 1️⃣ Install and Activate ACF Pro

This theme has a **hard dependency on ACF Pro**.  
The theme will not function correctly without this plugin.

---

### 2️⃣ Import ACF JSON Field Files

Go to: WP Admin → Custom Fields → Tools → Import

Import the file: acf-export-2026-02-14.json

After import, verify that all ACF field groups and custom blocks are registered.

---

### 3️⃣ Install and Activate the Theme

- Extract the theme folder.
- Copy it into: wp-content/themes/
- Activate the theme from: WP Admin → Appearance → Themes


---

### 4️⃣ Create a New Page

Go to: WP Admin → Pages → Add New


---

### 5️⃣ Add Required Custom Blocks & Fill Field Values

Add the following blocks and provide values for all required fields:

- **Hero Block**  
  Search with text: `SR Hero Section`

- **Services Block**  
  Search with text: `SR Services Grid`

- **Why Choose Us Block**  
  Search with text: `SR Why Choose Us`

- **Contact Form Block**  
  Search with text: `SR Lead Form`

---

### 6️⃣ Save / Publish the Page

Publish the page.

(Optional) Set this page as the homepage: WP Admin → Settings → Reading → Homepage


---

### 7️⃣ Refresh URLs / Flush Permalinks (If Required)

If page URLs or routing do not work correctly, refresh permalink settings:

WP Admin → Settings → Permalinks
Choose "Post name" → Save Changes


---

## 📌 Support

If you face any issues while setting up or running the project,  
please feel free to reach out for clarification or support.

Thank you for reviewing the assignment!
