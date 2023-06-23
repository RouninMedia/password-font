# Password Font
A custom font to deploy when required to visually obfuscate user-entered text.

See:

 - https://github.com/RouninMedia/password-font/blob/main/password.ttf

## CSS
```
@font-face {
  font-family: 'password';
  src: url('/.assets/site/theme/elements/fonts/password/password.ttf);
}

.myObfuscatedTextInput {
  width: 240px;
  height: 20px;
  line-height: 30px;  
  font-family: 'password';
}
```
