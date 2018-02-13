
namespace :db do
  desc 'migrate changes to your database'
  task :environment do
  require_relative './config/environment'
end
  task :migrate => :environment do
    Student.create_table
  end
end