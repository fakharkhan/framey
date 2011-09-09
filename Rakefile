require 'rake/testtask'

begin
  require "jeweler"
  Jeweler::Tasks.new do |gem|
    gem.name = "framey"
    gem.summary = "A gem for easy Rails integration with the Framey video recording service."
    gem.description = "A gem for easy Rails integration with the Framey video recording service."
    gem.email = "david@qlabs.com"
    gem.authors = ["Dave Renz"]
    gem.files = Dir["{lib}/**/*"]
    gem.homepage = "http://framey.com"
    gem.add_dependency 'httparty'
    gem.add_development_dependency 'jeweler'
  end
  Jeweler::GemcutterTasks.new
rescue
  puts "Jeweler or dependency not available."
end
