# Summit-Events-App-As-Depencency

This repository is a starting point for creating aditional features for the Summit Events App
that live outside the packaged version of the Summit Events App. This repository will first install the package
for the Summit Events App in a scratch org then set up the scratch org to correctly
run the app (including sample data). You can the interact with the package with your own 
code.

## Development

To work on this project in a scratch org:

1. [Set up CumulusCI](https://cumulusci.readthedocs.io/en/latest/tutorial.html)
2. Run `cci flow run dev_org --org dev` to deploy this project.
3. Run `cci org browser dev` to open the org in your browser.
