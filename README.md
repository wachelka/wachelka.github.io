# English by Emily

## Install jekyll macOS

```
# install jekyll
gem install --user-install bundler jekyll
# check ruby version
ruby -v
# export proper version ...ruby/X.X.0/bin...
echo 'export PATH="$HOME/.gem/ruby/2.6.0/bin:$PATH"' >> ~/.zshrc
# check that "GEM PATHS" point to your home directory
gem env
# create a new Gemfile to list your project’s dependencies
bundle init
# edit the Gemfile in a text editor and add jekyll as a dependency
gem "jekyll"
# run bundle to install jekyll for your project
bundle
```
