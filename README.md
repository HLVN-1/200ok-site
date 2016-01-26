# 200ok.us

This is a static website deployed on gh-pages, built with [hexo](https://hexo.io/).

### Installing

```
git clone git@github.com:techlahoma/200ok-site.git
cd 200ok-site
npm install
npm install -g hexo
```

### File Structure

All the copy documents are in `/source`, the theme is `/themes/200ok`, and the original front-end theme is located in `/wrapbootstrap` for reference. Run `hexo new page` to automatically generate a new page if you need more content. All of the `/source` files should be markdown. Posts aren't currently being used.

### Working locally on the site

```
hexo serve
```

Then go to http://localhost:4000

### Deploy Changes

Run

  hexo deploy

This will generate the static files and deploy to github pages.