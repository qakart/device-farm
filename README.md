# device-farm

A simple way to upload your artifacts to test your app in AWS Device Farm


## Usage
```ruby
require "devicefarm"

DeviceFarm.test_with_calabash(
	project_name:"best-project",
	device_pool_name: "top-devices-google-play",
	apk_path:"best-app.apk",
	calabash_test_package_path:"calabash_features.zip")
```

## Installation

```ruby
gem install "devicefarm"
```

## Author

viniciusmo

## License

devicefarm gem is available under the MIT license. See the LICENSE file for more info.

