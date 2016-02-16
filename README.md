# What is this?
A bleeding-edge boilerplate for opinionated minimalists coding static websites. It has:

- Sass libraries written by Thoughtbot.
- barebones Jade markup templates written by me.
- sensible folder structure
- Prepros config file to make things compile client-side automatically.

It's simply my preferred starting point for creating semantically pure, organized and DRY website code. Unless you have a somewhat tech savvy client who's going to make regular updates to their own site, then building a basic site on a CMS is like using a combustion engine to make toast. Yes, even a cool CMS like Grav or Ghost. 

At the same time, you’ll probably want to do things like share the header and footer between pages, use simple variables, cascade your stylesheets, sometimes invoke a grid. You know, stuff that organized web devs do. 

But there's no reason we need a complicated workflow or ANY server requirements to accomplish this. You know what else we don’t need? Bloated, outdated libraries like Bootstrap and Foundation generating non-semantic code and weird CSS behavior.

## Compiling
It's ready to go for Prepros but you could easily use it with your favorite build tool like grunt, gulp, codekit, ghostlab, etc. It’s intended to work like this.
- files in /jade compile to /html
- files in /scss compile to /css
- the root path for the site is /html
