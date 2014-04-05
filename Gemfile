require 'rbconfig'
source 'https://rubygems.org'

group :development do
  gem 'guard'
  gem 'guard-phpunit2'
  if RbConfig::CONFIG['host_os'] =~ /linux|freebsd|openbsd|sunos|solaris/
    gem 'libnotify'
  end
end
