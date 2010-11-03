require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "heroku_san"
    gem.summary = %Q{A bunch of useful Rake tasks for managing your Heroku apps}
    gem.description = %Q{Manage multiple Heroku instances/apps for a single Rails app using Rake}
    gem.email = "elijah.miller@gmail.com"
    gem.homepage = "http://github.com/glennr/heroku_san"
    gem.authors = ["Elijah Miller", "Glenn Roberts"]
    gem.files = Dir["{lib}/**/*", "VERSION", "LICENSE", "CHANGELOG", "TODO", "README.rdoc", "Rakefile"]
    gem.extra_rdoc_files = []
    gem.add_dependency("heroku")
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

desc 'Default: build gem.'
task :default => :build
