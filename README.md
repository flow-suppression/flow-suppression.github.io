# Flow Suppression website

Deployment configuration for [Flow Suppression](https://flow-suppression.github.io/).
The application source and API documentation are in
[flow-suppression/flow-suppression](https://github.com/flow-suppression/flow-suppression).

The workflow builds application commit
[`244c8e584018a612f5541c44ba499745ea55ab03`](https://github.com/flow-suppression/flow-suppression/commit/244c8e584018a612f5541c44ba499745ea55ab03),
runs its production checks, and publishes only the `dist-browser` output.
Changes to the application repository do not automatically change this version.

## Deployment

1. In this repository's **Settings → Pages**, select **GitHub Actions** as the source.
2. Open **Actions → Deploy website → Run workflow** and select `main`.
3. Wait for the build and deployment jobs to succeed, then open
   **https://flow-suppression.github.io/**.

Pushes to this repository's `main` branch also trigger deployment. To publish a
different application version, update the commit reference in
[the workflow](.github/workflows/pages.yml).
