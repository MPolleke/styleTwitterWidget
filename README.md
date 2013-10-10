
### Styling the Twitter Widget

Since Spring 2013 the v1.0 version of the standard Twitter Widget doesn’t work anymore.

The old widget was built in JavaScript, and added elements to the loaded page. It was easy to add css styling for that, you could just add it to the main stylesheet of your page.

With the new widget, which uses the new API that doesn’t work anymore. It is still built in JavaScript, but it adds an iframe to the page. And adding rules to your standard stylesheet has no effect on an iframe.

You can however add a stylesheet to an iframe, and that’s what I did. It’s available as download. All you have to do is change the location of the stylesheet in it. You can then add it to your page-layout. It does use and need jQuery.

