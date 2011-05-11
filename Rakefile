require 'rake/extensiontask'

spec = Gem::Specification.new do |s|
  s.name        = "nethogger"
  s.platform    = Gem::Platform::RUBY
  s.extensions  = FileList["ext/**/extconf.rb"]
end

Gem::PackageTask.new(spec) do |pkg|
end

Rake::ExtensionTask.new('nethogs', spec)