# YAML2CV

## Customize the CV
1. Go to `assets/cv.yml` and edit the file so that it fit your life and not mine :)
2. Change the image in `static/profile.jpg`
3. If you want to use the logo in the footer leave the settings true in the YAML file and change the svg in `components/LhCvFooter.vue` to your logo.
4. Change the colors in `assets/scss/_settings.scss` mainly the `$c-primary` color.
5. In the same file you can change the font but than you have to add the Google Font in the `nuxt.config.js` file.

## Run localy
1. Install all dependencies `npm install` - you only have to do this once
2. Run `npm run dev` and go to localhost:3000

## Generate CV - tested in Chrome Version 71.0.3578.98 on MacOs
1. Open the print dialog
2. Click on `More settings`
3. And select
    1. Paper size: A4
    2. Margins: None
    3. Scale: 100
    4. Options: (true) Background graphics
4. Select `Save as PDF` as print destination
5. And that's it :)

## Use it on production server

### Run on a server
1. `npm run build`
2. `npm run start`

### Generate static HTML
1. `npm run generate`
2. copy the files from the dist folder


For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).