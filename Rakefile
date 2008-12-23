
%w( rubygems rake echoe ./lib/commander.rb ).each { |lib| require lib }

Echoe.new("commander", Commander::VERSION::STRING) do |p|
  p.author = "TJ Holowaychuk"
  p.email = "tj@vision-media.ca"
  p.summary = "The complete solution for Ruby command-line executables"
  p.url = "http://github.com/visionmedia/commander"
  p.runtime_dependencies = ["highline >=1.5.0"]
end

Dir['tasks/**/*.rake'].sort.each { |lib| load lib }
