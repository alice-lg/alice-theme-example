
# Alice Theme Example

Give your looking glass a fresh new look!

## How this works
You can put assets (images, fonts, javscript, css) in 
your theme folder. In your alice config, you just have
to specify the path to your theme. For example:

    [theme]
    path = /opt/alice-themes/alice-theme-example


Stylesheets and scripts are automatically included in
the client's html and are served from the backend.

Alice provides early stages of an extension API, which is for now 
only used to modify the content of the welcome screen,
by providing a javascript in your theme containing:

```javascript
Alice.updateContent({
    welcome: {
        title: "My Awesome Looking Glass",
        tagline: "powered by Alice"
    }
});
    
```

## Screenshots

You want an example? This is the default theme:
![Alice screenshot before customization](/doc/alice-before.png?raw=true)

This is the `alice-theme-example` customization:
![Alice screenshot after customization](/doc/alice-after.png?raw=true)




