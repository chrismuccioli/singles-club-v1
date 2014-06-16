# Singles Club

http://singlesclub.fm

## Running locally

1. Go to the `singles-club` folder
2. Run `jekyll serve --watch`
3. Go to `localhost:4000` in your browser

### Note about `_config.yml`
Be sure that the correct `url` is set for each environment.

For local development, use:

    url: "http://localhost:4000"

For gh-pages, use:

    url: "http://chrismuccioli.github.io/singles-club"

And for production, use:

    url: "http://singlesclub.fm"

## Running Sass

1. Go to the `css` folder
2. Run `sass --watch .:. --style compressed`

As you make changes, to `.sass` files, the minified css will be updated.

## Uploading site to FTP

1. Switch the `url` in `_config.yml` to the production url.
2. Run `jekyll serve` to compile the site.
3. Upload all files from `singles-club/_site` to the root of your site.

---

## Using the grid system
TK

