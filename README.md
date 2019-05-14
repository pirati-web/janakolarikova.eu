# janakolarikova.eu

Osobní web kandidátky s články a životopisem.

Vytvořeno dle vzoru https://github.com/Kedrigern/profant.eu .

Publikováno pod licencí CC-BY-3.0-CZ.

## Lokalní spuštění

```
npm install
bundle install --path vendor/bundle
bundle exec jekyll serve --livereload --future --drafts
```

## Install

On Fedora 27:

```
dnf in gcc rubygem-bundler ruby-devel rubygem-jekyll rubygem-nokogiri
bundle install --path vendor/bundle
bundle exec jekyll serve --livereload --future --drafts
```

## SSL

- [An illustrated guide to setting up your website using GitHub and Cloudflare](https://medium.freecodecamp.org/an-illustrated-guide-for-setting-up-your-website-using-github-cloudflare-5a7a11ca9465)
