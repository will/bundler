# Bundler Issues

## Troubleshooting

Before reporting a bug, try these troubleshooting steps:

    rm -rf ~/.bundle/ ~/.gem/ .bundle/ Gemfile.lock
    bundle install

## Reporting bugs

If you are still having problems, please report bugs to the [Bundler issue tracker](http://github.com/carlhuda/bundler/issues/).

Instructions that allow the Bundler team to reproduce your issue are vitally important. When you report a bug, please create a gist of the following information and include a link in your ticket:

  - What version of bundler you are using
  - What version of Ruby you are using
  - Whether you are using RVM, and if so what version
  - Your Gemfile
  - Your Gemfile.lock
  - If you are on 0.9, whether you have locked or not
  - If you are on 1.0, the result of `bundle config`
  - The command you ran to generate exception(s)
  - The exception backtrace(s)

If you are using Rails 2.3, please also include:

  - Your boot.rb file
  - Your preinitializer.rb file
  - Your environment.rb file
