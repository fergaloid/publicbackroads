# Public sector backlogs and roadmaps

The source for [www.publicbackroads.xyz](https://www.publicbackroads.xyz): a list of product and service backlogs and routemaps/roadmaps opened in the public domain by public sector organisations around the world.

## Use the data

The whole list lives in one file, [`_data/links.csv`](_data/links.csv). You can view it here, download it, or get it as JSON from [www.publicbackroads.xyz/links.json](https://www.publicbackroads.xyz/links.json).

## Suggest a link

[Open a suggestion](../../issues/new?template=suggest-a-link.yml) with the link, the service and the organisation that runs it.

## How the site is put together

- `index.md` holds the introduction at the top of the page.
- `_data/links.csv` holds every entry. Each row is one link; the `section` and `country` columns decide where it appears.
- `assets/style.css` holds the look of the site.
- GitHub Pages builds the site automatically whenever a file changes.
