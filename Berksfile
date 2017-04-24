source "https://api.berkshelf.com"

cookbook "apt"
cookbook "phpenv", path: "./site-cookbooks/phpenv"

# P135追記
cookbook 'hostsfile'
# P136追記
cookbook "capistrano", path: "./site-cookbooks/capistrano"

# P137追記 capistranoの依存関係解決の為、独自追記　https://goo.gl/GzJ79X
cookbook "ruby-ng"

# P143追記
cookbook 'jenkins'
cookbook 'jenkins-plugin', path: "./site-cookbooks/jenkins-plugin"

#cookbook 'jenkins', path: "./site-cookbooks/jenkins"
