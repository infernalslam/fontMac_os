# fontMac_os
* mac_os HTML

```HTML

<h1>Hello, San Francisco</h1>
<h2>Hello, San Francisco</h2>
<h3>Hello, San Francisco</h3>
<p>Hello, San Francisco</p>
<p class="thin">Hello, San Francisco</p>
<p class="ultralight">Hello, San Francisco</p>

```

```CSS

/**
 * http://applemusic.tumblr.com/
 */

/** Ultra Light */
@font-face {
  font-family: "San Francisco";
  font-weight: 100;
  src: url("https://applesocial.s3.amazonaws.com/assets/styles/fonts/sanfrancisco/sanfranciscodisplay-ultralight-webfont.woff");
}

/** Thin */
@font-face {
  font-family: "San Francisco";
  font-weight: 200;
  src: url("https://applesocial.s3.amazonaws.com/assets/styles/fonts/sanfrancisco/sanfranciscodisplay-thin-webfont.woff");
}

/** Regular */
@font-face {
  font-family: "San Francisco";
  font-weight: 400;
  src: url("https://applesocial.s3.amazonaws.com/assets/styles/fonts/sanfrancisco/sanfranciscodisplay-regular-webfont.woff");
}

/** Medium */
@font-face {
  font-family: "San Francisco";
  font-weight: 500;
  src: url("https://applesocial.s3.amazonaws.com/assets/styles/fonts/sanfrancisco/sanfranciscodisplay-medium-webfont.woff");
}

/** Semi Bold */
@font-face {
  font-family: "San Francisco";
  font-weight: 600;
  src: url("https://applesocial.s3.amazonaws.com/assets/styles/fonts/sanfrancisco/sanfranciscodisplay-semibold-webfont.woff");
}

/** Bold */ 
@font-face {
  font-family: "San Francisco";
  font-weight: 700;
  src: url("https://applesocial.s3.amazonaws.com/assets/styles/fonts/sanfrancisco/sanfranciscodisplay-bold-webfont.woff");
}

* {
    font-family: "San Francisco"   
}

h1 { font-weight: 700; }
h2 { font-weight: 600; }
h3 { font-weight: 500; }
p { font-weight: 400; }
p.thin { font-weight: 200; }
p.ultralight { font-weight: 100; }

```
