# FarabiLabs.com Website CMS

Visit the live website here: https://farabilabs.com

This site uses the following software and services:

- CMS: Hugo (see [here](https://gohugo.io))
- Template: Hextra template (see [here](https://imfing.github.io/hextra/) and [here](https://themes.gohugo.io/themes/hextra/))
- Hosting: Netlify (see [here](https://docs.netlify.com/integrations/frameworks/hugo/))

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone https://github.com/imfing/hextra-starter-template.git

# Change directory
cd hextra-starter-template

# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.

