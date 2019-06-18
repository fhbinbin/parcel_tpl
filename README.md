# parcel_tpl
A simple template for multi-page project by Parcel 

##  Usage

### Install
```bash
$   npm install parcel-bundler --global
$   cd parcel-demo
$   npm install
#   if you use yarn , you can also run `yarn`
```

### Develope
```bash
$   npm run dev
#   or `yarn dev`
```

### Build
```bash
$   npm run build
#   or `yarn build`
```
Your codes are all in `./build` directory.

##  License
MIT is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT)


##  PostCSS（postcss-modules autoprefixer）
PostCSS 是一个用插件转换 CSS 的工具，比如 autoprefixer, cssnext, 和 CSS Modules。 您可以使用以下名称之一创建配置文件，从而使 Parcel 使用 PostCSS 配置 ： .postcssrc (JSON), .postcssrc.js, 或者 postcss.config.js. 然后，创建一个 .postcssrc 文件：
  {
    "modules": true,
    "plugins": {
        "autoprefixer": {
        "grid": true
        }
    }
   }

## original author;
gaoerli（高二丽）


##参考配置地址  
https://github.com/gaoerli/parcel-demo