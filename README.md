# OmniSocial

A Rails engine for Twitter and Facebook logins using [OmniAuth](http://github.com/intridea/omniauth)

## Installation

OmniSocial requires Rails 3.

To use OmniSocial in a Rails application, simply require it in the Gemfile:

    gem 'omnisocial'

Then install it by running `bundle`.

Once this is done, run `rails g omnisocial` to copy an initializer, database migration and some CSS and image assets into your base application directory.

Then edit `config/initializers/omnisocial.rb` and include your application's Twitter and Facebook OAuth configuration.

Then run `rake db:migrate` to create the user and login_account tables.

Finally, test that the logins work by accessing `/login` inside your application.

## Copyright & License

OmniSocial is Copyright (c) 2010 [Tim Riley](http://openmonkey.com/) and [Icelab](http://icelab.com.au/), and is released under MIT License.

The "Sign in with Twitter/Facebook" buttons are from [Komodo Media](http://www.komodomedia.com/blog/2009/05/sign-in-with-twitter-and-facebook-buttons/), distributeed under the [Creative Commons Attribution-Share Alike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/).

The twitter bird image is courtesy of [Pasquale D’Silva](http://wefunction.com/2008/07/freebie-twitter-icons-illustration/).

