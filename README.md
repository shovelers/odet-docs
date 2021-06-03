
### Install Ruby 3.0.0
RUBY_CONFIGURE_OPTS="--with-openssl-dir=/usr/local/opt/openssl" rbenv install 3.0.0

### Install bundler:2.1.4
gem install bundler:2.1.4

### Run bundle install
bundle \_2.1.4\_ install

### Local server
bundle exec jekyll serve --config _config_local.yml

