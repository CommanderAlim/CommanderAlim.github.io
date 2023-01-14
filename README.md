./
├── .editorconfig
├── Gruntfile.js
├── package.json
├── README.md
|
├── grunt_tasks/                               * grunt tasks
|   ├── config/                                * grunt tasks config
│   |   ├── paths.js
│   |   └── aliases.js
│   |
|   └── task.js
|
├── screenshots/                               * responsive test screenshots
|
├── dev/                                       * site source
│   ├── images/                                * image sources
|   │
│   ├── pug/                                   * templates
|   |   ├── blocks/                            * blocks library
|   │   |   └── block.pug
|   │   ├── helpers/                           * helper mixins
|   │   ├── vendor/                            * third-party code
|   │   ├── layouts/                           * page layouts
|   │   └── pages/                             * main pages templates
|   │
|   ├── stylus/                                * stylus preprocessor styles
|   |   ├── blocks/                            * blocks library
|   │   |   └── block.styl
|   │   ├── helpers/                           * mixins and vars
|   │   ├── vendor/                            * third-party code
|   │   ├── custom.styl
|   │   ├── noscript.styl
|   │   └── screen.styl
|   │
│   ├── helpers/                               * helper files
|   |   ├── favicon.ico
|   |   └── .htaccess
|   │
│   └── data/                                  * configs and data for templates
│
└── build/                                     * built source
    ├── index.html
    ├── page.html
    |
    └── static/                                * static assets
        ├── css/                               * minified styles
        |
        ├── images/                            * minified images
        |
        └── fonts/                             * @font-face-ready webfonts
