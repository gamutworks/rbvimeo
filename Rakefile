# Look in the tasks/setup.rb file for the various options that can be
# configured in this Rakefile. The .rake files in the tasks directory
# are where the options are used.

load 'tasks/setup.rb'

ensure_in_path 'lib'
require 'rbVimeo'

task :default => 'test:run'

PROJ.name = 'rbvimeo'
PROJ.authors = 'Matt Pruitt'
PROJ.email = 'guitsaru@gmail.com'
PROJ.url = 'www.guitsaru.com'
PROJ.rubyforge.name = 'rbvimeo'
PROJ.summary = "A ruby wrapper for the vimeo api"
PROJ.version = '0.2.0'
PROJ.spec.opts << '--color'
PROJ.gem.dependencies << 'hpricot'

# EOF
