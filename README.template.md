# 🪐11ty_starter
A free, new-user-friendly website starter project designed to walk you through creating, editing, and publishing any web project; from a personal blog, to a company website!

Read more at [https://get11ty-starter.com](https://get11ty-starter.com)!

## What is 11ty_starter?
### For new users
_11ty_starter_ is a free, new-user-friendly website starter designed to walk you through creating and publishing a fast, secure web project using modern tools and technology. 11ty_starter makes it easy to "get up to zero" and start building your site.

### For experienced developers
_11ty_starter_ is a modern, opinionated, bare-bones Jamstack starter using Eleventy to get "up to zero" on a project quickly and easily.
Why you might choose _11ty_starter_ as your Jamstack starter:
* Powered by Eleventy, which [rocks](https://11ty.rocks)!
* No CSS frameworks or libraries; use whatever you like best
* GitHub Action replaces the 11ty_starter name throughout the site with your project's name!
* Custom generated project-specific [readme file](https://github.com/achanda101/11ty_starter/blob/master/README.11ty_starter.md) to help you take the next steps and launch your project!
* Sass for CSS
* Webpack for Javascript
* Browsersync to preview your work

 ## Get started: Use This Template!
<details open>
 <summary>Right from this README</summary>
 
 ###  Create a new project using 11ty_starter and add it to your GitHub account!
 [Click here to use this template](https://github.com/achanda101/11ty_starter/generate)
 </details>

<details>
 <summary>With GitHub CLI (https://cli.github.com)</summary>

 ### Get started from your command line
 ```sh
  gh repo create example.com --template achanda101/11ty_starter
 ```
</details>

# Get to Know 11ty_starter
Ready to go deeper? Here's how 11ty_starter is laid out:

```sh
example.com                 # → Root of your 11ty_starter-based project
├── src/                    # → Source directory
│   ├── assets/             # → Site assets
│   │   ├── fonts/
│   │   ├── images/
│   │   ├── scripts/
│   │   ├── styles/
│   │   └── views/
│   ├── config/             # → Eleventy configuration
│   │   ├── collections.js  # → Add and configure collections (https://www.11ty.dev/docs/collections/)
│   │   ├── filters.js      # → Add and configure filters (https://www.11ty.dev/docs/filters/)
│   │   ├── passthroughs.js # → Add and configure passthroughs (https://www.11ty.dev/docs/copy/)
│   │   ├── plugins.js      # → Add and configure plugins (https://www.11ty.dev/docs/plugins/)
│   │   └── watchtargets.js # → Add and configure watch targets (https://www.11ty.dev/docs/watch-serve/)
│   ├── data                # → Customize site data (https://www.11ty.dev/docs/data/)
│   │   └── navigation.json # → Site navigation configuration
│   └── pages               # → Add "pages" collection items here
│       ├── index.md        # → Default index page
│       └── pages.json      # → Shared pages attributes
├── .eleventy.js            # → Core Eleventy config file
├── netlify.toml            # → Netlify deployment and plugin configuration (optional)
├── README.template.md      # → 11ty_starter readme
└── README.md               # → Your project's readme (automatically generated when this template is used)
```

## Eleventy Configuration
Eleventy configuration is abstracted from the typical `.eleventy.js` file and moved to `/src/config/` for easy organization and configuration of collections, filters, passthroughs, etc.
## Install project dependencies
```bash
npm i
```

## Run the project locally
```bash
npm run start
```

## Build for production
```bash
npm run production
```
