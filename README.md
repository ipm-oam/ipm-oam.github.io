# IPM-OAM webpage

Based on [bulma-clean-theme](https://github.com/chrisrhymes/bulma-clean-theme).

## Installation on Ubuntu

- Install Ruby and other prerequisites

```console
sudo apt-get install ruby-full build-essential zlib1g-dev
```

- Avoid installing RubyGems packages (called gems) as the root user. Instead, set up a gem installation directory for your user account. The following commands will add environment variables to your `~/.bashrc` file to configure the gem installation path:

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

- Finally, install Jekyll and Bundler:

```
gem install jekyll bundler
```

- Now, install the jekyll and bundler gems:

```ruby
gem install jekyll bundler
```

## Documentation of the original theme

Check out the demo site for the [Documentation](https://www.csrhymes.com/bulma-clean-theme/docs/)

## Development

Please complete installation part. Then clone this repository. 

To set up your environment, in `ipm-oam.github.io` folder, run `bundle install`.

Your theme is set up just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

## Addition of contents

The `index.md` creates the main page contents. Please add your contents to the `presentation` folder. There is also an `archive` folder to keep track of the old contents which should not be seen at the main page.

## Deploy (publish) the site

After adding and commiting your changes, please `push` them:

```console
git push origin main
```

Github will build the site. After a few minutes, your changes to the site will be applied.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

