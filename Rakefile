timestamp = Time.now.utc.strftime("%Y%m%d%H%M%S")
filename = "#{timestamp}_create_users.rb"
filename = "#{timestamp}_create_products.rb"
filename = "#{timestamp}_create_reviews.rb"

require_relative './config/environment'
require 'sinatra/activerecord/rake'

desc "Runs a Pry console"
task :console do
  # This line turns on logging of the SQL generated by Active Record
  ActiveRecord::Base.logger = Logger.new(STDOUT)
  
  # Open a Pry session
  Pry.start
end