# Base10 · Series A Consensus Cohort & DNA (Password-Protected GitHub Pages)

Consensus Series A cohort + DNA + methodology. Reference for B10 1-to-10s prioritization. Internal.

Live URL: https://ade-b10.github.io/consensus-cohort-series-a/
Password: `Base10Automation!`

## What's here

- `index.html` - encrypted page (committed to GitHub)
- `source/Consensus_Cohort_Series_A.html` - unencrypted source (gitignored)
- `update.sh` - re-encrypt + push helper
- `.staticrypt.json` - salt (DO NOT change; password hash depends on it)

## Update workflow

1. Edit the source HTML at `source/Consensus_Cohort_Series_A.html`
2. `./update.sh` (re-encrypts using the committed salt)
3. `git add index.html && git commit -m "Refresh" && git push`

GitHub Pages auto-deploys in ~30 seconds.
