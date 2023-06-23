# Password Font
A custom font to deploy when required to visually obfuscate user-entered text.

See:

 - https://github.com/RouninMedia/password-font/blob/main/password.ttf

## CSS
```
@font-face {
  font-family: 'password' ;
  font-display: block; 
  src: url('/.assets/site/theme/elements/fonts/password/password.woff2') format('woff2'), /* Super Modern Browsers */
       url('/.assets/site/theme/elements/fonts/password/password.woff') format('woff'); /* Pretty Modern Browsers */
}

.myObfuscatedTextInput {
  width: 240px;
  height: 20px;
  line-height: 30px;  
  font-family: password, sans-serif;
}
```
