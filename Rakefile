# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'ASA Experiment'
  app.frameworks += ["AVFoundation"]
  app.files_dependencies 'app/controllers/stream_test_controller.rb' => 'app/helpers/sounds_helpers.rb'
  app.identifier = 'com.mt.asa-experiment'
end
