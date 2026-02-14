Nice addition 👍 — that’s helpful for reviewers who might have Drive access issues.
Here’s your **final, polished single-file `README.md`** with the GitHub fallback link added cleanly:

---

```md
# 📘 Project Setup & Run Instructions

This assignment can be reviewed and run in **two different ways**:

- ✅ **Full Project Setup** (recommended – shows final output instantly)  
- ✅ **Theme-Only Setup** (manual setup to verify architecture & coding skills)

📥 Primary download link (Google Drive):  
👉 https://drive.google.com/drive/folders/1Srl-3SJeaOm0JZiwM2f9wgkWt78y6p42?usp=sharing  

> **Note:** If you are not able to download files from Google Drive, you can download the project from the GitHub repository:  
> 👉 https://github.com/satyakeeray/ot-machine-test  

Inside the drive / repository, you will find two folders:

- **Complete Project**  
- **Theme**

---

## ✅ Option 1: Run the Complete Project (Recommended)

This option includes:

- Full WordPress setup  
- Theme  
- Required plugins  
- Media files  
- Database (.sql file)  
- Preconfigured pages and content  

### 🔧 Steps

1. Download and extract the **Complete Project** folder.
2. Copy the extracted WordPress project into your local server directory:

   - **XAMPP** → `htdocs/`  
   - **MAMP** → `htdocs/`  
   - **LocalWP** → Site folder  

3. Create a new database in **phpMyAdmin**.
4. Import the database file:

```

db_my_service.sql

```

5. Update database credentials in:

```

wp-config.php

```

6. Open the site URL in your browser.

✅ After setup, the website will load with the **expected output** (homepage, ACF blocks, services grid, contact form, admin leads panel, etc.).

---

## ✅ Option 2: Run Only the Theme (Manual Setup)

This option demonstrates the **theme structure, ACF block system, and dynamic rendering**.

### 🔧 Steps (Follow This Order)

### 1️⃣ Install & Activate ACF Pro

This theme has a **hard dependency on ACF Pro**.  
The theme will not work correctly without this plugin.

---

### 2️⃣ Import ACF JSON Field Files

Go to:

```

WP Admin → Custom Fields → Tools → Import

```

Import:

```

acf-export-2026-02-14.json

```

Verify that all blocks and field groups are registered.

---

### 3️⃣ Install the Theme

Extract and copy the theme folder into:

```

wp-content/themes/

```

Activate the theme:

```

WP Admin → Appearance → Themes

```

---

### 4️⃣ Create a New Page

Go to:

```

WP Admin → Pages → Add New

```

---

### 5️⃣ Add Required Custom Blocks & Fill Field Values

Add the following blocks and fill in required values:

- **Hero Block**  
  Search: `SR Hero Section`

- **Services Block**  
  Search: `SR Services Grid`

- **Why Choose Us Block**  
  Search: `SR Why Choose Us`

- **Contact Form Block**  
  Search: `SR Lead Form`

---

### 6️⃣ Publish the Page

Publish the page.  
(Optional) Set as homepage:

```

WP Admin → Settings → Reading → Homepage

```

---

### 7️⃣ Flush Permalinks (If Required)

If URLs don’t work correctly:

```

WP Admin → Settings → Permalinks → Select "Post name" → Save Changes

```

---

## ⚠️ Dependency Note

- This theme **requires ACF Pro**.
- Theme activation and block rendering will fail without it.
- This dependency is intentional to prevent runtime errors.

---

## 🧪 What You Can Verify

- ACF block-based page building  
- Dynamic services rendering  
- AJAX lead form  
- Leads stored in custom database table  
- Admin dashboard with filters & pagination  
- Status update (New → Contacted)  
- SVG support  
- Clean theme architecture  

---

## 🎯 Review Recommendation

- Quick output verification → **Option 1 (Complete Project Setup)**  
- Architecture & code review → **Option 2 (Theme-Only Setup)**  
```

---

If you want, I can also add:

* 📸 Screenshot placeholders
* 🧾 Test credentials
* 🧰 Environment requirements (PHP, WordPress versions)
