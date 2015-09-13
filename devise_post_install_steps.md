Windows PowerShell
Copyright (C) 2009 Microsoft Corporation. All rights reserved.

C:\Users\JEsser\Documents\GitHub> cd ~/desktop/pinteresting
C:\Users\JEsser\desktop\pinteresting [master +0 ~1 -0]> bundle install
DL is deprecated, please use Fiddle
Your Ruby version is 2.1.5, but your Gemfile specified 2.0.0
C:\Users\JEsser\desktop\pinteresting [master +0 ~1 -0]> bundle install
DL is deprecated, please use Fiddle
Fetching gem metadata from https://rubygems.org/............
Fetching version metadata from https://rubygems.org/...
Fetching dependency metadata from https://rubygems.org/..
Resolving dependencies...
Using rake 10.4.2
Using i18n 0.7.0
Using json 1.8.3
Using minitest 5.8.0
Using thread_safe 0.3.5
Using tzinfo 1.2.2
Using activesupport 4.1.8
Using builder 3.2.2
Using erubis 2.7.0
Using actionview 4.1.8
Using rack 1.5.5
Using rack-test 0.6.3
Using actionpack 4.1.8
Using mime-types 2.6.1
Using mail 2.6.3
Using actionmailer 4.1.8
Using activemodel 4.1.8
Using arel 5.0.1.20140414130214
Using activerecord 4.1.8
Using execjs 2.6.0
Using autoprefixer-rails 5.2.1.3
Installing bcrypt 3.1.10
Using sass 3.2.19
Using bootstrap-sass 3.3.5
Using bundler 1.10.6
Using coffee-script-source 1.9.1.1
Using coffee-script 2.4.1
Using thor 0.19.1
Using railties 4.1.8
Using coffee-rails 4.0.1
Installing orm_adapter 0.5.0
Using responders 1.1.2
Installing warden 1.2.3
Installing devise 3.5.2
Using hike 1.2.3
Using multi_json 1.11.2
Using jbuilder 2.3.1
Using jquery-rails 3.1.4
Using pg 0.18.3
Using tilt 1.4.1
Using sprockets 2.12.4
Using sprockets-rails 2.3.2
Using rails 4.1.8
Using rails_serve_static_assets 0.0.4
Using rails_stdout_logging 0.0.4
Using rails_12factor 0.0.3
Using rdoc 4.2.0
Using sass-rails 4.0.5
Using sdoc 0.4.1
Using sqlite3 1.3.10
Using turbolinks 2.5.3
Using tzinfo-data 1.2015.6
Using uglifier 2.7.2
Bundle complete! 14 Gemfile dependencies, 53 gems now installed.
Use `bundle show [gemname]` to see where a bundled gem is installed.
C:\Users\JEsser\desktop\pinteresting [master +0 ~2 -0]> bundle show devise
DL is deprecated, please use Fiddle
C:/RailsInstaller/Ruby2.1.0/lib/ruby/gems/2.1.0/gems/devise-3.5.2
C:\Users\JEsser\desktop\pinteresting [master +0 ~2 -0]> rails generate devise:in
stall
DL is deprecated, please use Fiddle
      create  config/initializers/devise.rb
      create  config/locales/devise.en.yml
===============================================================================

Some setup you must do manually if you haven't yet:

  1. Ensure you have defined default url options in your environments files. Her
e
     is an example of default_url_options appropriate for a development environm
ent
     in config/environments/development.rb:

       config.action_mailer.default_url_options = { host: 'localhost', port: 300
0 }

     In production, :host should be set to the actual host of your application.

  2. Ensure you have defined root_url to *something* in your config/routes.rb.
     For example:

       root to: "home#index"

  3. Ensure you have flash messages in app/views/layouts/application.html.erb.
     For example:

       <p class="notice"><%= notice %></p>
       <p class="alert"><%= alert %></p>

  4. If you are deploying on Heroku with Rails 3.2 only, you may want to set:

       config.assets.initialize_on_precompile = false

     On config/application.rb forcing your application to not access the DB
     or load models when precompiling your assets.

  5. You can copy Devise views (for customization) to your app by running:

       rails g devise:views

===============================================================================
C:\Users\JEsser\desktop\pinteresting [master +2 ~2 -0 !]>