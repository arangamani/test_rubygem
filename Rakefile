lib = File.expand_path('../lib', __FILE__)
$LOAD_PATH.unshift(lib) unless $LOAD_PATH.include?(lib)
require 'test_rubygem/version'
require 'rake'
require 'jeweler'

Jeweler::Tasks.new do |gemspec|
  gemspec.name             = 'test_rubygem'
  gemspec.version          = TestRubyGem::VERSION
  gemspec.platform         = Gem::Platform::RUBY
  gemspec.date             = Time.now.utc.strftime("%Y-%m-%d")
  gemspec.require_paths    = ["lib"]
  gemspec.executables      = `git ls-files -- bin/*`.split("\n").map{|f| File.basename(f)}
  gemspec.files            = `git ls-files`.split("\n")
  gemspec.extra_rdoc_files = ['LICENSE', 'README.md']
  gemspec.authors          = [ 'Kannan Manickam' ]
  gemspec.email            = [ 'arangamani.kannan@gmail.com' ]
  gemspec.homepage         = 'https://github.com/arangamani/test_rubygem'
  gemspec.summary          = 'A Test Rubygem to test Rubygems API client'
  gemspec.description      = %{
This is a test gem to test the Rubygem API Client}
  gemspec.test_files = `git ls-files -- {spec}/*`.split("\n")
  gemspec.rubygems_version = '1.8.17'
end
