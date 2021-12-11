# Kong
A simple hexo theme base on [hexo-theme-butterfly](https://github.com/jerryc127/hexo-theme-butterfly) and [typography](https://github.com/Rapiz1/typography)

## Getting Started

### Download

```
git clone https://github.com/Elitedj/hexo-theme-kong.git themes/kong
mv themes/kong/_config.yml _config.kong.yml
```

If you don't have pug and stylus render

```
npm install  hexo-renderer-pug hexo-renderer-stylus --save
```

### Configuration
Set theme in the hexo work folder root config file `_config.yml`

```
theme: kong

highlight:
    enable: false
    line_number: true
    auto_detect: false
    tab_replace: ''
    wrap: true
    hljs: false
prismjs:
    enable: true
    preprocess: true
    line_number: true
    tab_replace: ''
```

## Tips
This is my first front-end project, if you find some bugs, ~~maybe features~~.

## License
GPL-3.0