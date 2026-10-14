# Interactive Economics Graphs

A static website containing nine interactive economics visualisations for university teaching. All graphs are provided as standalone HTML pages and can be hosted through GitHub Pages without a server or programming setup.

## Publish with GitHub Pages

1. Sign in to [GitHub](https://github.com/) (or create a free account).
2. Select **+ → New repository**. Enter **`economics-graphs`**, select **Public**, and create the repository. You can leave **Add a README file** unchecked.
3. On the empty repository page, click **uploading an existing file**. Alternatively, if your repository already has files, use **Add file → Upload files**.
4. **Extract the downloaded ZIP first.** Open the extracted `economics-graphs-github-pages` folder and drag **its contents** (`index.html`, `graphs`, `README.md` and `.nojekyll`) into GitHub's upload area. Do not upload the ZIP itself and do not put everything in an extra outer folder.
5. Enter a commit message such as **Add interactive economics website**, then click **Commit changes** (or the equivalent commit button).
6. In the repository, navigate to **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch** as the **Source**, then select **`main`** and **`/(root)`** and click **Save**.
8. Once the site is deployed, choose **Visit site** under **Settings → Pages**, or open `https://YOUR-USERNAME.github.io/economics-graphs/` (replace `YOUR-USERNAME` with your account name).

GitHub's own instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Website files

```text
economics-graphs-github-pages/
├── index.html                            ← homepage
├── .nojekyll                             ← disables Jekyll processing
├── README.md                             ← these instructions
└── graphs/
    ├── budget-function-grapher.html
    ├── labour-leisure-budget-constraints.html
    ├── labour-leisure-budget-constraints-24hr.html
    ├── labour-leisure-budget-constraints-24hr-indifference.html
    ├── construct-indifference-curves.html
    ├── indifference-budget-graph.html
    ├── income-substitution-effect.html
    ├── utility-marginal-utility.html
    └── utility-constraint-indifference-3d.html
```

## Direct links and updating graphs

Every page has a direct link such as:

`https://YOUR-USERNAME.github.io/economics-graphs/graphs/income-substitution-effect.html`

To revise a graph, open the repository's `graphs` folder, select the relevant `.html` file, and use the pencil icon to edit it. Alternatively, upload a replacement file with exactly the same name. Keeping the name and location unchanged keeps its public link unchanged.

To add another graph, upload another standalone `.html` file into `graphs`, and add a link to it in `index.html`.

## Notes

- The nine graph pages are copied unmodified from the source files provided for this site. Only their filenames have been simplified for readable URLs.
- The 3D graph embeds Plotly and is therefore a larger HTML file (approximately 4.9 MB). Its first load may be slower than the others.
- GitHub Pages is publicly accessible. Do not include private student data or confidential materials.
- If the site gives a 404 error, check that `index.html` is at the *repository root*, that **Pages** is set to `main` + `/(root)`, and that the site is fully deployed. If a specific graph gives a 404 error, check its exact spelling and the `graphs/` path.
- GitHub may take several minutes to publish changes.
