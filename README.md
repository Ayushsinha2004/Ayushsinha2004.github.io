# Ayushsinha2004.github.io

Personal portfolio and case studies for Ayush Sinha. Plain HTML and one stylesheet (`styles.css`), with no build step and no JavaScript.

## Pages

- `index.html`: home, intro, case-study cards, stack, selected projects
- `case-document-ai.html`: document AI for an Irish life-insurance brokerage
- `case-pos-ingest.html`: sales ingest for a 180-store fast-food franchise group in New Zealand
- `case-erp-analytics.html`: talk-to-your-ERP natural-language analytics
- `more-work.html`: shorter project notes
- `work-with-me.html`: fixed-scope offers and terms

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish on GitHub Pages

1. On GitHub, create a new **public** repository named exactly `Ayushsinha2004.github.io` under the `Ayushsinha2004` account. Don't add a README or licence there, since this folder already has one.
2. From this folder:

   ```sh
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/Ayushsinha2004/Ayushsinha2004.github.io.git
   git push -u origin main
   ```

3. In the repository, open Settings, then Pages. Under "Build and deployment" choose "Deploy from a branch", branch `main`, folder `/ (root)`. A user site named `<username>.github.io` usually has this set already.
4. After a minute or two the site is live at https://ayushsinha2004.github.io.

The empty `.nojekyll` file tells Pages to serve the files as they are, without running Jekyll.

## Editing rules

Every number and claim on the site comes from `~/resume-system/evidence/master.yaml`. Client names stay out; describe clients by country and industry.
