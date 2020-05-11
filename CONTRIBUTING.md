## Build

To build and preview this site, use

```bash
# install jekyll and themes, only once
sudo apt install ruby zlib1g-dev jekyll
bundle install

# this runs the server, run from root dir
bundle exec jekyll serve -s docs
```

After this, the site can be previewed at [localhost:4000]().

## Publish

The site is published to [https://zeppe.github.io/karate]() on push.
