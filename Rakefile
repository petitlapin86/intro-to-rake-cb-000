
namespace :db do
  
  desc 'migrate changes to your database'
  task :environment do
  require_relative './config/environment'
end
  task :migrate => :environment do
    Student.create_table
  end
end

namespace :db do
 
  desc 'seed the database with some dummy data'
  task :seed do 
    require_relative './db/seeds.rb'
  end
end

  desc 'drop into the Pry console'
task :console => :environment do
  Pry.start 
end