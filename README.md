# Forest Edge Estate — Owner-managed website

This starter preserves the approved estate homepage and adds a journal powered by JSON files.

## Setup (one time)
1. Create a GitHub repository and upload these files to its `main` branch.
2. In repository Settings → Pages, select **GitHub Actions** as the source.
3. Go to https://pagescms.org, sign in with GitHub, and choose the repository. Pages CMS reads `.pages.yml` and provides a friendly journal/photo editor.
4. In Pages CMS, create entries under **Estate Journal** and upload original photos. Save/publish to the repository. Each change triggers a new GitHub Pages deployment.
5. Once the site works, connect your domain in Settings → Pages and configure DNS with your domain provider.

## Notes
- The journal index is generated automatically during deployment by `scripts/build_index.py`. It does not need to be edited in the CMS.
- The journal homepage may show no entries until you publish the first story.
- The sample images on the landing page are remote illustrative photographs, not estate photographs. Replace before public launch.
- The `Request an invitation` email in `index.html` is a placeholder. Replace `YOUR_EMAIL@example.com` before launch.
- This is a starter, not a deployed website. Check the Pages CMS configuration and GitHub Pages deployment before public launch.
- Don't publish precise wildlife camera-trap coordinates or sensitive locations.
- Photos should be owned or licensed for public use.
