# Setup your GitHub profile README

1. Create a **public** repository named exactly the same as your GitHub username (for example, `octocat` for `github.com/octocat`). GitHub displays the repository's README on your profile.
2. Upload `README.md`, the `assets/` folder, and `.github/workflows/generate-snake.yml` while preserving the folder structure.
3. In `README.md`, replace every `YOUR_GITHUB_USERNAME` with your exact GitHub username. Keep the `assets/` paths unchanged unless you move those files.
4. Push the files to the repository's `main` branch. Open **Actions** on GitHub and check that **Generate contribution snake** finishes successfully. It creates/updates the `output` branch used by the animated SVG.
5. If the workflow cannot publish the `output` branch, open **Settings → Actions → General → Workflow permissions** and enable read/write permissions for workflows, then rerun the workflow.
6. Replace or remove any section that no longer reflects what you're currently learning. Add links to actual project repositories when they're ready.

## Notes

- The GitHub stats, language card, streak card, technology icons, and typing animation are rendered by external services, so they may occasionally load slowly or be unavailable.
- GitHub stats cards primarily reflect public repository activity; language percentages should not be read as a proficiency ranking.
- The README currently avoids invented email addresses, social links, credentials, and completed-project claims.
