# -*- ruby -*-

require 'rubygems'
require 'hoe'

Hoe.plugin :git
Hoe.plugin :isolate
Hoe.plugin :minitest
Hoe.plugins.delete :rubyforge

Hoe.spec 'rdoc-perl_pod' do
  developer 'Eric Hodel', 'drbrain@segment7.net'
  developer 'Hugh Sasse', 'hgs@dmu.ac.uk'

  extra_deps << ['rdoc', '~> 3']
  extra_dev_deps << ['isolate', '~> 3']

  self.rubyforge_name = 'rdoc'
  self.isolate_dir = 'tmp/isolated'
end

# vim: syntax=Ruby
