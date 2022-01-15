# webpage

Static website is built with [hugo](https://gohugo.io/).  

To edit/view locally:

```
git clone https://github.com/berkeley-ds4e/webpage
hugo server
```

Point your browser at localhost:1313 as directed to view the local site.

# To build for deployment:

```
hugo
```

Builds site in the `publishDir` of `conf.toml` (currently the `docs/` foloder)
Copy `docs/*` to the deployment folder.

## Credits 

Build on [Now-UI Kit](https://demos.creative-tim.com/now-ui-kit/) by Creative Tim using Bootstrap 4 framework; distributed under [MIT](https://spdx.org/licenses/MIT.html) License
