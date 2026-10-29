# Publishing the GitHub profile README

The README.md in this folder renders on Mark's public GitHub profile page
(https://github.com/marksong0917) once it lives in the special profile repo.

## Steps

1. On GitHub, create a new repository:
   - Owner: `marksong0917`
   - Repository name: exactly `marksong0917` (must match the username — GitHub
     shows a hint that this is a special profile repo)
   - Visibility: **Public**
   - Do not add a README, .gitignore, or licence during creation (this folder
     already has the README ready).
2. Add **README.md only** to the repo root (PUBLISH.md stays local — see Notes):
   - Easiest: use the repo's "uploading an existing file" link and upload README.md.
   - Or via git: `git remote add origin https://github.com/marksong0917/marksong0917.git`,
     copy README.md into a fresh clone of the repo, commit, and push.
3. Open https://github.com/marksong0917 and confirm the README renders under
   the profile header: name, banner image, Foxuma section, selected work.

## Notes

- Only README.md belongs on the profile. PUBLISH.md is internal — do not push it.
- The banner image is https://marksong0917.github.io/og.png (served from the
  portfolio site), so no image file needs to live in this repo.
- To update the profile later: edit README.md here, commit, push again.
