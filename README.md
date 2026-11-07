# UK Employer Directory, Student Edition

(c) PC3

Fifteen self-contained web pages: a landing page (index.html) and fourteen regional employer directories covering Scotland, Wales, Northern Ireland, the nine English regions with London split into Inner and Outer, and an Unresolved bucket for organisations whose region could not be assigned from the registered postcode.

Each regional page is a single Employer Search screen. Students search from any postcode with a distance radius, filter by company name, sector, organisation type and advanced filters (status, size, council area, address status), open organisation profiles, and export results to Excel. Searches run entirely in the browser; the pages collect no data about their users. The only outside requests are for the background map images.

## Data sources

Companies House Basic Company Data, snapshot 1 August 2026; Charity Commission for England and Wales; OSCR Scottish Charity Register; NHS ODS, Public Health Scotland and NHS open data; curated public bodies; Get Information about Schools (HE/FE). All used under the Open Government Licence v3. Registered-office addresses may differ from trading locations; the Address status field flags this. The directory shows organisations, not vacancies.

## How to publish this folder on GitHub Pages

1. Create a new repository on github.com (public, no template).
2. Upload the contents of this folder to the repository root. Five files are larger than 25 MB, so the github.com web uploader will reject them. Use GitHub Desktop (File, Add local repository, then commit and push) or the git command line instead:
   git init
   git add .
   git commit -m "UK Employer Directory, student edition"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
3. In the repository, open Settings, then Pages, and under Branch choose main and / (root), then Save.
4. After a minute or two the site is live at https://YOUR-USERNAME.github.io/YOUR-REPO/ and opens on the landing page. Share that one link with students; every regional directory is reachable from it.

Notes. Every file is under GitHub's 100 MB per-file limit (largest is the South East at 44 MB). The larger pages take a few seconds to load on a first visit because the employer data is embedded in the page. The .nojekyll file tells GitHub Pages to serve the files as they are; keep it.
