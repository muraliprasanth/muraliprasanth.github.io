# Future issue prevention: portfolio

Written 2026-11-17. Update it when a limit or a risk changes.

| Limit or risk | Detail | What happens | Prevention |
|---|---|---|---|
| Public repository | Every commit ever pushed stays readable | Something committed once cannot be taken back by a later commit | Never commit a phone number, a home address or an employer's internal project names |
| Served by GitHub Pages as plain files | `.nojekyll` is present, so every file in the repo has a public address, this one included | A stray file is published | Commit only what should be public |
| GitHub Pages limits | 1 GB per site and about 100 GB of traffic a month | GitHub may ask to reduce use | One page and one photo: far below |
| Photo | `assets/photo.jpg` | A camera file can carry location data | Re-encode before replacing it |
| Content goes stale | Based on the resume | Old role or skills shown | Update with every resume change |
