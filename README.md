# connect-fonts-vampiroone

Vampiro One fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-vampiroone");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/vampiroone-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* vampiroone-regular

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/vampiroone-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin
* en

5. Set your CSS up to use the new font by using the "Vampiro One" font-family.
```
    body {
      font-family: 'Vampiro One', 'sans-serif', 'serif';
    }
```

## Font Info
Vampiro One

* Description: Vampiro is a low contrast script font. It was inspired by the 20th C. Italian tradition of monoline scripts. Vampiro is best used for display purposes at medium to large sizes.
* Copyright: Copyright (c) 2012, Sorkin Type Co (www.sorkintype.com)with Reserved Font Name 'Vampiro'.
* Trademark: Vampiro is a trademark of Sorkin Type Co.
* Designer: Riccardo De Franceschi
* Designer URL: www.sorkintype.com 
* Vendor: Sorkin Type Co.
* Vendor URL: www.sorkintype.com

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-vampiroone
* Repo: https://github.com/shane-tomlinson/connect-fonts-vampiroone

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 1.1 of the SIL Open Font License

  http://scripts.sil.org/OFL

