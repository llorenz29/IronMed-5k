# IronMed 5K

Fundraising site for the IronMed 5K, Georgetown University School of Medicine's annual race benefiting the HOYA Clinic.

It is a static site with no build step: `index.html` plus `hero.jpg`, served by GitHub Pages from the `main` branch.

## Updating for a new year

Everything that changes year to year is in the `SITE` block near the bottom of `index.html`:

- `edition`: race number (28 for 2027)
- `date`, `dateShort`, `dateNote`: race date text; set `dateNote` to `""` once the date is final
- `raceStart`: countdown target, e.g. `2027-04-17T09:00:00-04:00`; set to `""` to hide the countdown
- `links.donate`, `links.register`: swap for the current year's campaign and registration
- `sponsors`, `pastSponsors`: sponsor names and links
- `logo`: optional data URI for the official logo

Edit, commit to `main`, and the live site updates in about a minute.
