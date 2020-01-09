# Pulsar Summit Website

[![Netlify Status](https://api.netlify.com/api/v1/badges/f0231f93-4800-4877-aeff-c7402b8d1d63/deploy-status)](https://app.netlify.com/sites/pulsar-summit/deploys)

The website is built based on [DevFest 2019](https://github.com/GDGToulouse/site-devfest-2019) and hugo template [devfest-theme-hugo](https://github.com/GDGToulouse/devfest-theme-hugo).

## Requirement

* [Hugo](https://gohugo.io/getting-started/installing/)
* [NodeJS](https://nodejs.org/en/)
* [Yarn](https://yarnpkg.com/lang/en/docs/install).

## Run Local site

### Build the theme

> Only run this step if you are making changes to `themes/pulsar-summit`.

1. go into the theme folder.

    ```bash
    cd themes/pulsar-summit
    ```

2. install the dependencies with yarn

    ```bash
    yarn
    ```

3. build the theme css and js

    ```bash
    npm run build     
    ```

### Build the website

> If you are in `themes/pulsar-summit`, go back to the root directory of this repository.

```bash
hugo server -D
```

More information [here](https://gohugo.io/commands/hugo_server/)
