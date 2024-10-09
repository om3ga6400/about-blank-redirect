# How to use
Choose one of the options below then follow the instructions for it.

## Website
To use this, fork the repo and edit "index.html" and replace "INSERT URL HERE" with the URL you want to redirect to.

## Bookmarklet

Just add this into the URL section of a new bookmark and replace "INSERT URL HERE" with the URL you want to redirect to:
```
javascript: var win = window.open();   win.document.body.style.margin = '0';   win.document.body.style.height = '100vh';   var iframe = win.document.createElement('iframe');   iframe.style.border = 'none';   iframe.style.width = '100%';   iframe.style.height = '100%';   iframe.style.margin = '0';   iframe.src = 'INSERT URL HERE';   win.document.body.appendChild(iframe);
```

# Problems
If this dosent work make sure to enable popups!

# Example
https://om3ga6400.github.io/aboutblank-redirect/

# Credits
https://github.com/NRZT555/about-blank-cloaker - Most of the code
