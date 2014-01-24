$:.unshift File.dirname(__FILE__) + 'lib'
$:.unshift './lib', './spec'

require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new
task :default => :test


desc "Pruebas rspec"
task :test do
     sh 'rspec -I. spec/matriz_spec.rb'
end
