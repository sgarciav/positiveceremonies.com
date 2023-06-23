# About

This is website for my business **Positive Ceremonies by Sergio**, bringing joy
to your forever after . I use [Jekyll](https://jekyllrb.com/) and
the [Freelancer](https://jekyllthemes.io/theme/freelancer-theme) theme. This
repo is meant to keep track of the changes I've made to the orignal theme.

# Dependencies

After following
the
[Jekyll Installation Documentation](https://jekyllrb.com/docs/installation/),
execute the following to install the gems in the Gemfile:

    cd /path/to/positiveceremonies.com
    bundle install

**Note**: You can always execute the following to update the gems in your
system:

    sudo apt install jekyll bundler
    gem update --system

# Usage

Execute the following to start hosting the website locally:

    cd /path/to/positiveceremonies.com
    bundle exec jekyll serve

## Interact with the Theme

 - Place images in `/img/portfolio/`
 - Replace `your-email@domain.com` in `_config.yml` with your email
   address. Refer to [formspree](http://formspree.io/) for more information.
 - Create posts to display your projects. Use the follow as an example:

```txt
---
layout: default
modal-id: 1
date: 2020-01-18
img: cabin.png
alt: image-alt
project-date: January 2020
client: The Client
category: Web Development
description: The description of the project

---
```

# Misc

## License

MIT License

## Credits

Credits go to the freelancer-theme project
([GitHub link](https://github.com/jeromelachaud/freelancer-theme)) from which
this repo was forked.
