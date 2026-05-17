# Department of Defence PNG Recruitment Portal

This folder is ready for upload to GitHub Pages.

## Files included

- `index.html` — Home page
- `vacancies_by_divisions.html` — Position vacancies by division
- `application-form.html` — Online application form connected to Google Apps Script
- `success.html` — Submission confirmation page
- `.nojekyll` — Keeps GitHub Pages from applying Jekyll processing
- `logo.png` — Temporary placeholder logo. Replace with the official Department logo before publishing if required.
- `background.jpg` — Temporary background image. Replace with the official background image before publishing if required.

## How to upload to GitHub

1. Open your repository, for example `dodrecruitment/vacancies`.
2. Click **Add file**.
3. Click **Upload files**.
4. Upload all files from this folder into the root of the repository.
5. Click **Commit changes**.

## Enable GitHub Pages

1. Go to **Settings**.
2. Click **Pages**.
3. Under **Build and deployment**, select:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
4. Click **Save**.

Your site should be available at:

```text
https://dodrecruitment.github.io/vacancies/
```

## Important

The application form currently uses this Google Apps Script endpoint inside `application-form.html`:

```text
https://script.google.com/macros/s/AKfycbwP1GOzSJwqvuNCAUtOJyFrE_AHsGLKYNAs3L71YssTQif7uXHy_I_kC8Pz1C5Vfq4/exec
```

Confirm this is the correct deployed Apps Script web app URL before publishing.
