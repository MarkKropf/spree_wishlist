# Spree Wishlist extension

[![Build
Status](https://secure.travis-ci.org/spree/spree_wishlist.png)](http://travis-ci.org/spree/spree_wishlist)

The Spree Wishlist extension enables multiple wishlists per user, as well as managing those
as public (sharable) and private.  It also includes the ability to notify a friend via email
of a recommended product.

## Installation

1. Add the following to your Gemfile

<pre>
    gem 'spree_wishlist', '~> 1.3'
    gem 'spree_email_to_friend'
</pre>

2. Run `bundle install`

3. To setup the asset pipeline includes and copy migrations run: `rails g spree_wishlist:install`

## Development

  * Fork the repo
  * clone your repo
  * Run `bundle`
  * Run `bundle exec rake test_app` to create the test application in `spec/test_app`.
  * Make your changes.
  * Ensure specs pass by running `bundle exec rake`
  * Submit your pull request
