require 'rake'
require 'rake/testtask'
require 'rake/rdoctask'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "gattica"
    gemspec.summary = "Gattica is a Ruby library for extracting data from the Google Analytics API."
    gemspec.email = "rob.cameron@active.com"
    gemspec.homepage = "http://github.com/activenetwork/gattica"
    gemspec.description = "Gattica is a Ruby library for extracting data from the Google Analytics API."
    gemspec.authors = ["The Active Network"]
    gemspec.add_dependency('hpricot','>=0.6.164')
  end
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end

Rake::TestTask.new do |t|
  t.libs << 'lib'
  t.pattern = 'test/**/test_*.rb'
  t.verbose = false
end