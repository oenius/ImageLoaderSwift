NAME = "ImageLoader"
WORKSPACE = "#{NAME}.xcworkspace"

task :test do
  sh "carthage bootstrap --no-use-binaries --use-submodules"
  sh "xcodebuild clean test -workspace #{WORKSPACE} -scheme #{NAME} -sdk iphonesimulator"
end
