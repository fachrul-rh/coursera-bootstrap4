# coursera-bootstrap4
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)

## cara menjalankan project
unduh semua dependencies
  ```
  npm install
  ```
 jalankan project di lokal
 ```
 npm run start
 ```
 ```
 grunt
 ```
 build project
 ```
 npm run build
 ```
 ```
 grunt build
 ```
  

### _NOTE_
_cara install/gunakan less_<br/>

>```
> npm install -g less
>```
>masuk ke file css<br/>
>```
>cd css
>```
>lalu gunakan perintah
> ```
> lessc styles.less styles.css
> ```
<b>lessc</b> : _perintah untuk compile file .less_ <br/>
<b>styles.less</b> : _ambil file .less_ <br/>
<b>styles.css</b> : _hasil compile file .less menjadi .css_ <br/>
<hr/>

_cara install/gunakan scss_<br>

>```
> npm install node-sass --save-dev
>```
>tambahkan scripts pada package.json
> ```
> "scss": "node-sass -o css/ css/"
> ```
> compile file .scss dengan .css
> ```
> npm run scss
> ```

### Penting!
<b> Jangan lupa menginstall module dibawah ini NPM secara global</b>
```
npm -g install copyfiles@2.0.0
npm -g install imagemin-cli@3.0.0
npm install -g grunt-cli@1.2.0
```
