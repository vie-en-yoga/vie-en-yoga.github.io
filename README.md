# vie-en-yoga.github.io

Vie-en-Yoga's website

## Local Development

### Ruby

Install Ruby v4.0 from <https://www.ruby-lang.org/en/downloads/>
Or using `rbenv`:

```console
$ rbenv install 4.0.3
$ rbenv global 4.0.3
$ ruby --version
ruby 4.0.3 (2026-04-21 revision 85ddef263a) +PRISM [arm64-darwin25]
```

### Install libraries for this project

```console
bundle update && bundle install
```

### Run the website locally

```console
bundle exec jekyll serve
```
