# Repo for the new CheckSig website

[new checksig.io](https://checksig-inside.github.io/multilangsite/)

## Testing your GitHub Pages site locally with Jekyll

The first time setup requires Ruby and Jekyll installation, plus:

  gem install bundler
  bundle install

Then, every time:

```shell
$ bundle exec jekyll serve --incremental
Configuration file: C:/path/to/repo/checksig-custody.github.io/_config.yml
            Source: C:/path/to/repo/checksig-custody.github.io
    Destination: C:/path/to/repo/checksig-custody.github.io/_site
    Generating...
    Jekyll Feed: Generating feed for posts
                    done in 100.31 seconds.
Auto-regeneration: enabled for 'C:/path/to/repo/checksig-custody.github.io'
    Server address: http://127.0.0.1:4000
Server running... press ctrl-c to stop.
```

To preview your site, in your web browser, navigate to <http://127.0.0.1:4000>

From time to time you might want to update the GitHub Pages gem:

```shell
$ bundle update github-pages
Fetching gem metadata from https://rubygems.org/...........
Fetching gem metadata from https://rubygems.org/.
Resolving dependencies....
Using concurrent-ruby 1.1.5
Using i18n 0.9.5
Fetching minitest 5.14.0 (was 5.13.0)
Installing minitest 5.14.0 (was 5.13.0)
[...]
Using terminal-table 1.8.0
Fetching github-pages 204 (was 203)
Installing github-pages 204 (was 203)
Bundle updated!
```

See also:

- <https://jekyllrb.com/docs/installation/>
- <https://bundler.io/>
- <https://help.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll>

## MacOS Installation

  brew install ruby
  echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.zshrc

in the project root folder:

  bundle install

tested with:

  $ ruby -v
  ruby 3.0.0p0 (2020-12-25 revision 95aff21468) [x86_64-darwin20]
  $ gem -v
  3.2.3
