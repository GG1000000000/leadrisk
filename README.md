# Home Lead Risk Lookup

Free lookup of lead paint risk for any US ZIP code or street address: https://leadrisk.spirochaetelabs.com

Static page, no build step. `index.html` calls two read-only database functions
(`zip_know_risk`, `lookup_address_v2`) with a public key; `sources.json` maps each
record source to the public GIS service it was harvested from.

Method and data: Ritter, GeoHealth 2026, doi:10.1029/2026GH002053 and doi:10.1029/2026GH002142;
dataset doi:10.5281/zenodo.21685187.

Spirochaete Research Labs. No analytics, no ads, nothing sold.
