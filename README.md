# Research Lab website — GitHub Pages

A responsive, static academic-laboratory website built with plain HTML and CSS. No build tools, JavaScript framework, or server are required.

## Files

- `index.html` — all website sections and content
- `style.css` — layout, colors, typography and responsive design
- `assets/cv.pdf` — add your CV here (the download link is already prepared)

## 1. Personalize before publishing

Open `index.html` and search/replace these placeholders:

- `RESEARCH LAB` — your laboratory or research group name
- `[PI name]`, `[Position / Department]`, `[Names, roles and research interests]`
- `your.email@university.edu`
- `[Department / Institution]`, `[City, Country]`
- publication titles, authors, journal names, years and DOI/article links
- ORCID, Google Scholar and GitHub links (replace `href="#"`)

The research/project descriptions are starter text based on computational materials science, TiO2, MXenes, heterostructures and photocatalysis. Edit them to reflect the lab's actual work.

## 2. Add the CV

Create an `assets` folder if it does not exist and place your PDF in it named exactly:

`cv.pdf`

The CV button links to `assets/cv.pdf`. Only publish a CV you are comfortable making publicly accessible.

## 3. Add gallery images

Upload image files into `assets/`, for example:

- `anatase.jpg`
- `mxene.jpg`
- `simulation.jpg`

In `index.html`, replace a gallery placeholder such as:

`<div class="gallery-art gallery-a"><span>TiO₂</span></div>`

with:

`<img class="gallery-photo" src="assets/anatase.jpg" alt="Anatase TiO2 crystal structure">`

Then add this rule to `style.css`:

`.gallery-photo { width: 100%; height: 230px; object-fit: cover; display: block; }`

Use images that you own or have permission to publish.

## 4. Publish with GitHub Pages

1. Sign in at https://github.com/.
2. Create a **Public** repository named exactly `YOUR-GITHUB-USERNAME.github.io` (replace with your GitHub username).
3. Upload `index.html`, `style.css` and the `assets` folder to the repository root. Keep the same folder structure.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then click **Save**.
7. Wait for the Pages deployment to finish. Your site should appear at `https://YOUR-GITHUB-USERNAME.github.io/`.

GitHub's official guide: https://docs.github.com/en/pages/quickstart

## 5. Update later

Edit `index.html` or `style.css` on GitHub (pencil icon → commit changes), or upload replacement files. Each commit to the publishing branch triggers a new deployment.

## Important

Everything in a published GitHub Pages website is publicly accessible. Do not upload passwords, private data, unpublished confidential research, or personal information you do not want public.
