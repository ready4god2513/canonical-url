require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |s|
    s.name = "canonical-url"
    s.summary = %Q{Rails plugin to take advantage of the new Canonical URL support of search engines.}
    s.email = "michael@intridea.com"
    s.homepage = "http://github.com/mbleigh/canonical-url"
    s.description = %q{Rails plugin to take advantage of the new Canonical URL support of search engines.}
    s.authors = ["Michael Bleigh"]
    s.files = FileList["[A-Z]*", "{lib,rails}/**/*"]
  end
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end

require 'rake/rdoctask'
Rake::RDocTask.new do |rdoc|
  rdoc.rdoc_dir = 'rdoc'
  rdoc.title = 'canonical-url'
  rdoc.options << '--line-numbers' << '--inline-source'
  rdoc.rdoc_files.include('README*')
  rdoc.rdoc_files.include('lib/**/*.rb')
end

# require 'rake/testtask'
# Rake::TestTask.new(:test) do |t|
#   t.libs << 'lib' << 'test'
#   t.pattern = 'test/**/*_test.rb'
#   t.verbose = false
# end
# 
# begin
#   require 'rcov/rcovtask'
#   Rcov::RcovTask.new do |t|
#     t.libs << 'test'
#     t.test_files = FileList['test/**/*_test.rb']
#     t.verbose = true
#   end
# rescue LoadError
#   puts "RCov is not available. In order to run rcov, you must: sudo gem install spicycode-rcov"
# end
# 
# begin
#   require 'cucumber/rake/task'
#   Cucumber::Rake::Task.new(:features)
# rescue LoadError
#   puts "Cucumber is not available. In order to run features, you must: sudo gem install cucumber"
# end
# 
# task :default => :test
