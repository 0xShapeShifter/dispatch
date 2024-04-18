# [DISPATCH]

— is a— super clean template for a subscription-based development studio.

## Features
- Ready-to-go web-template made with [Astro](https://astro.build);
- Distinctive typography — [Monaspace Neon](https://monaspace.githubnext.com/);
- Sustainable code and design;
- Comes with the `site.js` — a single source of truth to update content, and don't waste any time jumping between files;
- Includes 7 sections: main, subscription description, services, about, FAQ, benefits, contact;

![Cover](/public/images/cover.webp)

## Scores
- [100 Performance according to PageInsights](https://pagespeed.web.dev/analysis/https-dispatch-omega-vercel-app/t6h6euey6v?form_factor=desktop);
- [A+ DigitalBeacon Carbon FootPrint Score](https://digitalbeacon.co/report/dispatch-omega-vercel-app);
- [A+ 95 Website Carbon Calculator Score](https://www.websitecarbon.com/website/dispatch-omega-vercel-app/);

## Structure
```plaintext
/
├── public/
│   ├── css/
│   │   └── global.css
│   ├── favicon.svg
│   ├── fonts/
│   │   └── MonaspaceNeonVarVF.ttf
│   └── images/
│       ├── article.webp
│       └── cover.webp
├── src/
│   ├── components/
│   │   ├── About.astro
│   │   ├── Benefits.astro
│   │   ├── Contact.astro
│   │   ├── FAQ.astro
│   │   ├── Header.astro
│   │   ├── Navigation.astro
│   │   ├── Package.astro
│   │   ├── SectionTitle.astro
│   │   ├── Services.astro
│   │   └── Subscription.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│   │   └── index.astro
│   └── site.js
└── package.json
```
## Customization and Development
To change the contents of the websise, update the `src/site.js` file — it's the easiest way. 

In case you want to change styles, colors, fonts — have a look at `public/global.css` file.

![FAQ Preview](/public/images/article.webp)