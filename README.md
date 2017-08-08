# Online Offline Equilavence: what our interplanetary tomorrow can teach us about building apps today

The slides!

## How do I use this repo, though?

These slides are built using [remarkjs](https://github.com/gnab/remark), which allows you to write your slides in nice simple markdown and turns them into beautiful, browser-powered slides complete with speaker notes. Read its readme to find out more about it.

This particular project uses yarn and whatnot to give some niceties in the development environment that probably aren't necessary. The only thing you actually need are the files in the `public` folder--you could just open `index.html` in a browser, and BAM! Slides! In fact, that's the plan for how to deploy these slides to the internet--drop everything in `public` into an Amazon S3 bucket, or copy them into my local [Partyshare](https://partysha.re/) folder to distribute them via IPFS for free.

I'm pretty proud of the styles I used for the slides. It took me a while to figure out how to override RemarkJS's styles in that way. If you enjoy it, feel free to copy it.
