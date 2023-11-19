# sergiopujalte.com

[![sergiopujalte.com](/assets/media/logo.png)](https://sergiopujalte.com/)


## STEPS


### Repositories


#### Main

- Icons
  - [General Settings](https://gitlab.com/sergiopujalte/sergiopujalte.com/edit) ⏩ `Project avatar`
  - [Profile](https://gitlab.com/-/profile) ⏩ `Public avatar`


### Hosting


#### If Netlify

- [Profile Avatar](https://app.netlify.com/user/settings#profile) ⏩ `Edit settings` ⏩ `Avatar`


### Local

- Design
  - GENERAL
    - `config.yml`
    - `data/*.{yml,md}`
  - IMG + LOGO + FAVICON
    - `assets/media/` folder ⏩ [Compress image tool](https://compressor.io/)
      - `fondo.jpg`
      - `logo.svg`
      - `logo.png`
      - `icon.png`
      - `favicon.ico` ⏩ [Favicon converter tool](https://favicon.io/favicon-converter/)
    - Gitlab, Github, Netlify and Cloudflare Pages update icon (project and account)
  - FONTS
    - Fonts that not be in Google Fonts:
      - .otf/.ttf files in `assets/fonts` + rename
      - You need the `sansoul_tools` project in `../_tools` folder
      - Run `do fonts` comand
      - `Family` + `Style` + `Weight` must match in `config.yml ⏩ params.fonts` + `_fonts.scss` (and disable `params.fonts.google` if appropriate)
  - If Multilanguaje and Multihosting, add `cp ./public/[es|en]/404.html ./public/` in `netlify.toml ⏩ build.command`
  - Try in Safari and Firefox
  - Check in [W3 Validator](https://validator.w3.org/)
  - Check in [PageSpeed Insights](https://pagespeed.web.dev/)


### After client validate web


#### Domain

- If Netlify
  - [`Domain Management / settings`](https://app.netlify.com/sites/sergiopujalte/settings/domain)
  - `Add custom domain`
  - `Verify DNS configuration`


#### [Google Search Console](https://search.google.com/search-console)

- Add property
- Verify versions ⏩ `data/config.yml`
  - `google_analytics`
  - `google_site_verification`
  - `google_file_verification`
  - DNS:
    From: `@`
    DNS Record: `TXT`
    To: `google-site-verification=[google_site_verification]`
- Link with Analytics
- Add sitemap.xml


##### Delivery

Send to all collaborators next:

```
*ENTREGA WEB sergiopujalte.com:* https://seacomoseo.com/entrega/
```
