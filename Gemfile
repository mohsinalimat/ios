source "https://rubygems.org"

gem "fastlane", git: "https://github.com/fastlane/fastlane", branch: 'plugin-manager'
gem "cocoapods"
gem "danger", git: "https://github.com/danger/danger"

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
