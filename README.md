
# Hugo commands
https://gohugo.io/getting-started/quick-start/

# Directory structure
```
├── archetypes/
├── config.yaml
├── content/
│   ├── _index.en.md
│   ├── _index.ja.md
│   └── posts/
│       ├── my-first-post.en.md
│       └── my-first-post.ja.md
├── data/
├── layouts/
├── netlify.toml
├── public/
├── resources/
├── static/
│   └── images/
│       └── top-header.png
└── themes/
    └── ananke/
```

**config.yml**  
Configuration file to define something allowed by hugo and the theme library such as blog title, theme, language, etc

**content**  
The blog article files written by Markdown.
`content/_index.xx.md` are index page and `contesnt/posts/xx.md` are each blog article.

**static**
The directory to place the static files such as images.

**themes**
The directory theme library placed.
The default setting up by the library are in the directory such as css.

# Ref
## Theme
github: https://github.com/theNewDynamic/gohugo-theme-ananke  
demo: https://gohugo-ananke-theme-demo.netlify.app/

## Multi-language support 
https://dev.classmethod.jp/articles/hugo-multilingual-mode/
