# GitHub Pages site

It's nice to be able to use GitHub pages with projects, so I keep a little landing page here too.

## Building locally

Adapted from the GitHub documentation:
<https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll>

```sh
# Install Jekyll
gem install --user-install bundler jekyll

# Install the prereqs
bundle install

# Start a webserver for local dev preview
bundle exec jekyll serve

# From time to time you may need to update the github-pages gem
bundle update github-pages
```
