require 'rubygems'
require 'rake'

begin
  gem 'jeweler', '~> 1.5.2'
  require 'jeweler'

  Jeweler::Tasks.new do |gem|
    gem.name        = 'dm-is-tree'
    gem.summary     = 'DataMapper plugin allowing the creation of tree structures from data models'
    gem.description = gem.summary
    gem.email       = 'leapord729 [a] comcast.net'
    gem.homepage    = 'http://github.com/datamapper/%s' % gem.name
    gem.authors     = [ 'Timothy Bennett' ]
    gem.has_rdoc    = 'yard'

    gem.rubyforge_project = 'datamapper'
  end

  Jeweler::GemcutterTasks.new

  FileList['tasks/**/*.rake'].each { |task| import task }
rescue LoadError
  puts 'Jeweler (or a dependency) not available. Install it with: gem install jeweler'
end
