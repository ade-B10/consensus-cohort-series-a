# Deploy Guide - Base10 · Series A Consensus Cohort & DNA

The site lives at: https://ade-b10.github.io/consensus-cohort-series-a/
Password: `Base10Automation!`

## Re-encrypting after edits

```bash
cd /Users/ade/Desktop/Urizen/consensus-cohort-series-a-deploy
# Edit source/Consensus_Cohort_Series_A.html
./update.sh
git add index.html && git commit -m "Refresh" && git push
```

GitHub Pages re-deploys in ~30s.
