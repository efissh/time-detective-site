# Time Detective public site

Independent static website for Time Detective by Mona Apps.

The site uses only HTML and CSS. It has no build step, cookies, analytics,
advertising, tracking scripts, or external runtime dependencies.

## Pages

- `/` — marketing homepage
- `/support/` — support contact and FAQ
- `/privacy/` — privacy policy

## Preview locally

From this directory:

```bash
python3 -m http.server 8000
```

Then open <http://127.0.0.1:8000/>.

## Publish with GitHub Pages

The GitHub CLI was not available when this site was prepared, so the public
repository and Pages setting still need to be created manually:

1. Create a new **public** GitHub repository named `time-detective-site`.
2. Add this repository as `origin` and push the `main` branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**,
   branch `main`, folder `/ (root)`, then save.
5. Wait for the Pages deployment to finish, then verify all three paths:
   `https://<github-user>.github.io/time-detective-site/`,
   `/support/`, and `/privacy/`.

No credentials, Apple IDs, private addresses, phone numbers, DSA information,
or application secrets belong in this repository.
