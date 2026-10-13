# Location Onboarding Kit

An independent proposal by Shorouk for onboarding multi-location brands onto Google Business Profile with less back-and-forth.

**Live page:** https://shorouk9.github.io/location-onboarding-kit/

## What it does

1. **Collect:** a branch template that follows Google's bulk upload columns, a "who owns what" contact list for the client, and a ready-to-send information request email.
2. **Check:** upload the client's .xlsx or .csv. Every location is checked against Google's rules (names, addresses, PO boxes, duplicates, phone or website, hours format, categories, coordinates, signage, on-site contact) and marked Ready, Needs a look or Blocked. It also says whether the chain meets the 10-location minimum for bulk verification.
3. **Fix:** a fix list grouped by issue with the affected store codes, ready to email; an issues CSV; and a clean bulk upload file.
4. **Verify:** a verification tracker per location, exportable as a CSV for Zoho CRM or Zoho Projects.

Everything runs in the browser; uploaded files are never sent anywhere. Example data is fictional. Not affiliated with Google or Local Knowledge.

A single self-contained `index.html`, hosted on GitHub Pages.
