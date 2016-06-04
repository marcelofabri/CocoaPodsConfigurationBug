platform :ios, '9.0'

target 'CocoaPodsConfigurationBug' do

  project 'CocoaPodsConfigurationBug', 'Debug' => :debug, 'BuggyConfiguration' => :debug, 'Release' => :release

  pod 'OHHTTPStubs', :configurations => ['BuggyConfiguration']

  target 'CocoaPodsConfigurationBugTests' do
    inherit! :search_paths

    pod 'OHHTTPStubs'
    pod 'Expecta'
    pod 'Specta'
  end

end
