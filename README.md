# Maintenance Mode

Netlify is very fault-tolerant (and isn't served from a dynamic server), so it doesn't have a maintenance mode.

If you're doing something that takes the site offline for more than a few minutes, clone this repo, drop the whole `./maintenance` folder (which just includes an `index.html` file) into the file upload box at the bottom of your Netlify site's ___Deploy___ tab. You should get something that looks like this:

![](/screenshot.png)
