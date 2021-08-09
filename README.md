[![Netlify Status](https://api.netlify.com/api/v1/badges/c00efb75-088d-495c-a1a5-6f20ecfb44b8/deploy-status)](https://app.netlify.com/sites/cawoodstock/deploys)

# Cawoodstock

* Simple Jekyll-based static site for Cawoodstock Music and Cultural Festival
* Different years are managed in Git branches, one branch per year, eg `2018`, `2019`, ~~`2020`~~, `2021`
* There is a `holding` branch which is used in between events
* The site is deployed via Netlify

## Creating a new site
* To create a new Cawoodstock 'year' just fork a previous year into a new branch named after the year, eg `2021`
* Netlify will build and deploy a site for every branch on the GitHub repo, so the new branch will be at `2021.cawoodstock.org`
* The 'production' branch is set in Netlify, and this is what will be at the TLD cawoodstock.org
* Old sites are visible at their year-subdomain.cawoodstock.org URL
