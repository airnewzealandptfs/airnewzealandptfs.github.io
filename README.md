# Air New Zealand PTFS

An independent community landing page for Air New Zealand PTFS, a fan community in Project Flight. The static site is designed for the organization website at <https://airnewzealandptfs.github.io/>.

The homepage uses `ptfs-air-new-zealand.jpg`, a community-provided Project Flight screenshot, as its hero background.

## Run locally

Open `index.html` in a browser, or start a local server with Python:

```bash
python3 -m http.server 4173
```

Then visit <http://localhost:4173/>.

## Publish at airnewzealandptfs.github.io

GitHub Pages uses the repository name to determine the organization-site URL. The source must be in a repository named **`airnewzealandptfs.github.io`** owned by the **`airnewzealandptfs`** organization.

1. Create that repository in the organization, or move/rename the repository containing these site files to that exact name.
2. Push the site files to its `main` branch.
3. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source.
4. The included Pages workflow deploys the site on pushes to `main`. Once the workflow succeeds, it will be available at <https://airnewzealandptfs.github.io/>.

The workflow is in `.github/workflows/pages.yml`. No build command or custom domain is required.

## About

This is an independent fan/community project and is not affiliated with Air New Zealand, Roblox, or the creators of Project Flight.
