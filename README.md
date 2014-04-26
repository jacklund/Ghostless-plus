# [Ghostless] (http://stefanleonte.com/ghostless-free-ghost-theme/)

Ghostless is a free [Ghost](http://ghost.org) minimalistic theme based on [Less](http://jarederickson.com/less-a-free-super-minimal-wordpress-theme/). You can consider it a port from Wordpress to Ghost.

It includes all of the features of the original theme but updated to Ghost.

### Instalation instructions

1. Copy the contents of the .zip file into `/content/themes/`.
2. Restart your Ghost instance.
3. From the Ghost admin select Ghostless as your theme.

### Q&A

#### How do I add an image at the top of the page?

Ghost Admin -> Settings -> General -> Blog Logo.

#### How do I add an author image?

Ghost Admin -> Settings -> User -> Profile Picture.

#### How do I enable Disqus comments?

Edit post.hbs, search for `disqus_shortname` and replace it's `example` value with your Disqus user short name.

### Limitations

Please note that due to limitations in Ghost the following features are not yet available:

- pages
- navigation links
- category links
- tag links

Please also note that some features can be available with some coding knowledge, but this is not in the scope of the theme.

### Theme preview

![Preview picture](https://raw.github.com/sleonte/ghostless/master/ghostless.png)
