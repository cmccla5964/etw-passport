# Chicago food passport site

One static page (`index.html`) served by GitHub Pages.

- **Rename:** find and replace "A Chicago food passport" in `index.html`.
- **Forms:** set `SITE.formEndpoint` in the script at the bottom of `index.html` (Formspree or FormSubmit). Each submission includes `kind` (restaurant or passport) and `ref`.
- **Contact line:** set `SITE.contactEmail`; the footer stays hidden while it's empty.
- **Outreach tracking:** add `?r=CODE` to the link in each email (for example `?r=r07`). The code arrives with any sign-up from that link.
