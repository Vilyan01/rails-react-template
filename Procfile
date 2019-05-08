web: bundle exec rails s
worker: bundle exec sidekiq -t 25 -c 5 -v
release: bin/rake db:migrate