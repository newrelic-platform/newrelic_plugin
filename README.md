# New Relic Platform Agent SDK

## Requirements

 * Tested with Ruby 1.8.7 and 1.9.3
 * New Relic account on rpm.newrelic.com, with early access enabled 
   (contact cooper@newrelic.com to set up early access)

## Get Started

This repo represents the core Ruby gem used to build plugin agents for
the New Relic platform. If you are looking to build or use a platform
component, please refer to the
[getting started documentation](http://newrelic.com/docs/platform/plugin-development).

Install this gem by running `gem install newrelic_plugin` or add it to your
[bundler](http://gembundler.com/) Gemfile like this:

```ruby
gem "newrelic_plugin"
```

Alternatively you can build and install the gem locally:

```bash
git clone git@github.com:newrelic-platform/newrelic_plugin.git
cd newrelic_plugin
rake build
gem install pkg/newrelic_plugin*
```

## Support

Reach out to us at
[support.newrelic.com](http://support.newrelic.com/).
There you'll find documentation, FAQs, and forums where you can submit
suggestions and discuss with staff and other users.

Also available is community support on IRC: we generally use #newrelic
on irc.freenode.net

Find a bug? E-mail <support@newrelic.com>, or submit a ticket to

[support.newrelic.com](http://support.newrelic.com/).

Thank you!
