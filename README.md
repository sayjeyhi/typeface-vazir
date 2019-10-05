# Easy to use vazir typeface

> 😄 use me with npm install

Typeface package for Vazir font with [typography.js](https://github.com/KyleAMathews/typography.js)

```bash
npm i -S typeface-vazir
```
Fonts will be copied to node_modules/typeface-vazir/dist directory
and you could add them easily to your project :
```javascript
import 'typeface-vazir';
```
and use `font-family: 'Vazir'` in your styling.


we used to do this with : 
```css
/* font converted using font-converter.net. thank you! */
@font-face {
    font-family: 'Vazir';
    src: url('./dist/Vazir-Thin-FD.woff') format('woff'), url('./dist/Vazir-Thin-FD.eot') format('eot'), url('./dist/Vazir-Thin-FD.ttf') format('truetype');
    font-weight: 300
}
```

### todo :
Make better decision between font weights currently 300,400,600,800 are supported
