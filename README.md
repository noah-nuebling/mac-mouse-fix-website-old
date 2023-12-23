# Mac Mouse Fix Website

This repo contains the old MMF website which is hosted at mousefix.org. 
The new website is in the repo at https://github.com/noah-nuebling/mac-mouse-fix-website/ and is hosted at macmousefix.com.

mousefix.org now simply redirects to macmousefix.com. I tried to set up a URL Redirect on namecheap.com, but it doesn't work for https://mousefix.org, only for http://mousefix.org. And to fix it I'd have to buy an SSL certificate or something. So now I'm just doing the redirect inside the 404.html file which is rendered for all paths - mousefix.org/, mousefix.org/about, mousefix.org/boobs, etc. This is apparently worse for SEO than a URL Redirect or sth but I don't really care about Google anyways.

The .nojekyll file prevents github from rendering the readme at the domain root mousefix.org/
