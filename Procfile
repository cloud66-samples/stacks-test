custom_web: bundle exec unicorn_rails -c config/unicorn.rb -E $RAILS_ENV -D
w1: bundle exec rake test:work $RAILS_ENV
w2: bundle exec rake test:work $RACK_ENV
