# Ghost template for fionakhor.com

At first while building this blog I wanted to use NextJS because
I use it at work. I ended up porting the default Casper theme to Nextjs to learn how to use Ghost's content API.  A fun learning experience but I realiazed that this was for Fiona and I wanted the blog to be easy to use with Ghost's backend. So... I reverted to using the default handlebarJS set up. Using Casper as my guide, I structured the blog according to what she wanted. This is the first iteration and we will see what she wants for her blog in the future.

You may also notice tailwind-css here and there.  I played around with it a little.  I really liked it simplicity and how everything is set up with a design system in mind... but I kept reverting to my old vanilla css habits to finally get this blog template done.

To build css files using the postcss-cli, run:
``` bash
$ yarn build-posts
$ yarn build-tailwind
```

Then zip the file:

```bash
$ zip -r theme.zip ./
```

 and upload it to Ghost!