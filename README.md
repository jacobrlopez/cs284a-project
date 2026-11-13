# Learning Cloth — CS 284A Project Proposal

A static proposal webpage based on the team's [planning document](https://docs.google.com/document/d/1EMtGea4CURWFREFOiE7UB0PRp5ph2ShSBJfKQ3r0riI/edit). No packages, JavaScript, or build step are required.

## Preview and edit

Open `index.html` in a browser. Edit the proposal in `index.html` and its appearance in `styles.css`, then refresh. Alternatively, run `python3 -m http.server 8000` from this folder and visit `http://localhost:8000` (Ctrl+C stops the server).

The refined proposal adds a proposed mass–spring baseline, graph-based learned dynamics, residual velocity correction, trajectory split, metrics, and improvement target to the original planning document. These are planning choices for team review, not completed experiments. MPM/FEM remain literature topics and optional implementation extensions. The computing platform, hardware, software, and starting-code section is intentionally incomplete for the teammates to fill in. The site itself still has no dependencies.

## Publish with GitHub Pages

This checkout already points to `git@github.com:jacobrlopez/cs284a-project-proposal.git`.

1. On GitHub, create the repository `cs284a-project-proposal` under `jacobrlopez` if it does not already exist. For the simplest setup on GitHub Free, make it **Public**. If creating it now, leave the README, license, and .gitignore options unchecked because this folder already contains the files.
2. From this project folder, commit and push:

   ```sh
   git add index.html styles.css assets .nojekyll README.md
   git commit -m "Add Learning Cloth project proposal"
   git push -u origin main
   ```

   The remote uses SSH, so GitHub SSH authentication must be set up. If you prefer HTTPS, use `git remote set-url origin https://github.com/jacobrlopez/cs284a-project-proposal.git` before pushing, and authenticate using GitHub's supported sign-in flow. If GitHub reports that the remote contains work you do not have locally, reconcile that history before pushing; do not force-push.

3. Open the repository on GitHub and go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch** as the source.
5. Select **main** and **/(root)**, then click **Save**.
6. Allow up to 10 minutes for publishing. The Pages settings will show the published URL. If deployment fails, inspect the repository's **Actions** tab.

The expected project URL after deployment is:

**https://jacobrlopez.github.io/cs284a-project-proposal/**

The exact root URL **https://jacobrlopez.github.io/** requires a repository named **jacobrlopez.github.io**. Use that repository instead if you want this proposal to occupy your account's homepage. The project URL above lets you keep the homepage available for a portfolio or links to other class projects. The page uses relative asset links and works with either URL.

For future updates, edit the files, commit, and push to `main`; GitHub Pages will republish automatically.

Official instructions: [Create a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [configure a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Logo sources

- `assets/uc-berkeley.svg`: [UC Berkeley Brand](https://brand.berkeley.edu/wp-content/themes/gallantry/dist/imgs/logo-uc-berkeley.svg), with the white fill changed to Berkeley Blue (`#003262`) for the white page background.
- `assets/cs184-284a.png`: [CS 184/284A Fall 2026 course site](https://cs184.eecs.berkeley.edu/fa26/assets/images/logo.png), used unchanged.
