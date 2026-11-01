# Personal academic website (Quarto)

## Edit in RStudio

1. Install RStudio and Quarto (https://quarto.org/docs/get-started/).
2. Open this folder as an RStudio Project (File > New Project > Existing Directory), or open `index.qmd` directly.
3. Edit the `.qmd` files to change the text, and `styles.css` to change the colors or layout.
4. Use **Render** in RStudio or run `quarto preview` in the terminal to see your changes.
5. Replace `images/headshot.jpg` to update your headshot.

## Publish free with GitHub Pages

1. Create a public GitHub repository named `YOURUSERNAME.github.io` (replace YOURUSERNAME with your actual GitHub username).
2. Upload/push all files from this folder to the repository's `main` branch, including `.github/workflows/publish.yml`.
3. In repository Settings > Pages > Build and deployment, choose **GitHub Actions** as the source.
4. The included GitHub Actions workflow builds and deploys the site whenever you push to `main`.
5. Your site will appear at `https://YOURUSERNAME.github.io` after the first successful deployment. It may take a few minutes.

Before publishing, replace the placeholder name, bio, email, research, publications, and CV content. For a custom domain, additional DNS configuration is needed.
