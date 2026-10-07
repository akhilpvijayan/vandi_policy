# Vandi Legal & Policy Center 🚌

Official public legal, privacy policy, terms of service, support, and account deletion portal for the **Vandi (വണ്ടി)** mobile app (Kerala Bus Route Mapping).

This repository is designed to be hosted publicly on **GitHub Pages** to provide all required policy links for the **Google Play Store** release.

---

## 📄 Included Web Pages

| File | Page Name | Google Play Console Purpose |
|---|---|---|
| `index.html` | Portal Home | Main hub linking to all legal documents & support |
| `privacy-policy.html` | Privacy Policy | **Mandatory** Privacy Policy URL for app store listing |
| `delete-account.html` | Account Deletion | **Mandatory** Data Safety Account Deletion URL |
| `data-deletion.html` | Account Deletion (Alias) | Backup alias URL |
| `terms-and-conditions.html` | Terms & Conditions | Terms of Service, transit timetable disclaimer & rules |
| `terms.html` | Terms of Service (Alias) | Backup alias URL |
| `support.html` | Help & Support | Store listing Customer Support URL |

---

## 🚀 How to Host on GitHub Pages (Free)

### Step 1: Create a New Public Repository on GitHub
1. Log in to [GitHub.com](https://github.com).
2. Click **New Repository** (or visit https://github.com/new).
3. Repository name: `vandi-legal` (or any name you prefer).
4. Set visibility to **Public** *(required for free GitHub Pages)*.
5. Do **not** initialize with README or license.
6. Click **Create repository**.

### Step 2: Push This Directory to Your GitHub Repository
Open a terminal inside `D:\Apps\vandi-legal` and run:

```bash
git init
git add .
git commit -m "Initial commit of Vandi legal & privacy policy portal"
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/vandi-legal.git
git push -u origin main
```

*(Replace `<YOUR_GITHUB_USERNAME>` with your GitHub username).*

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** → **Pages** (in the left sidebar under "Code and automation").
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
4. Click **Save**.

Your site will be live within 1–2 minutes at:
```
https://<YOUR_GITHUB_USERNAME>.github.io/vandi-legal/
```

---

## 📋 URLs to Enter in Google Play Console

Once published, enter these exact links into your Google Play Console:

1. **Privacy Policy URL:**
   ```
   https://<YOUR_GITHUB_USERNAME>.github.io/vandi-legal/privacy-policy.html
   ```

2. **Data Safety / Account Deletion URL:**
   ```
   https://<YOUR_GITHUB_USERNAME>.github.io/vandi-legal/delete-account.html
   ```

3. **App Support / Contact URL:**
   ```
   https://<YOUR_GITHUB_USERNAME>.github.io/vandi-legal/support.html
   ```

4. **Terms & Conditions (Optional):**
   ```
   https://<YOUR_GITHUB_USERNAME>.github.io/vandi-legal/terms-and-conditions.html
   ```
