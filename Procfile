interactive: bundle exec sidekiq -C config/sidekiq-task-interactive.yml -r ./core.rb
autoscheduled: bundle exec sidekiq -C config/sidekiq-task-autoscheduled.yml -r ./core.rb
enrichment: bundle exec sidekiq -C config/sidekiq-task-enrichment.yml -r ./core.rb
application: bundle exec sidekiq -C config/sidekiq-app.yml -r ./core.rb
puma: bundle exec  puma -C ./config/puma.rb
