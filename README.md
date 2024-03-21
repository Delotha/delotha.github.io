# Delotha Consulting Website

## Repo Info

This is the repository for Delotha Consulting's website on GitHub Pages.

You can find it at [delotha.com](https://www.delotha.com).

This site uses the [Midnight Jekyll theme](https://pages-themes.github.io/midnight/)

## Development

These are the commands required to develop this website locally:

```sudo apt install ruby-full```

Don't install Ruby gems as root, though. Put this into your .bashrc to configure where to install gems for your user:

```markdown
# Install Ruby Gems to ~/gems
export GEM_HOME="$HOME/gems"
export PATH="$HOME/gems/bin:$PATH"
```

Go to the folder where the website is
```bundle install```

This is the repeatable command to build the site and view it:  ```bundle exec jekyll serve```
