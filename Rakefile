require 'rom/sql/rake_task'

require_relative 'lib/projects'

namespace :db do
  task :setup do
    ROM::SQL::RakeSupport.env = Projects::DB
  end
end