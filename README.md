# Change Log
This is the Maleficarum Logger component. It uses monolog as it bases but provides initializers and builders for use in api/proxy/worker projects.

## Using plugins 

You can pass array of plugins via ```logger.plugins``` configuration option. Plugin has to be a callable. There will be one argument passed
- instance of \Monolog\Logger class

## [3.1.0] - 2021-09-01
### Added
- Abilty to plugins via configuration
- Default context processor plugin
- Dependency to context tracker package 

## [3.0.0] - 2018-09-17  
### Changed  
- Upgraded IoC component to version 3.x  
- Removed repositories section from composer file  

## [2.0.0] - 2017-08-02
### Changed
- Make use of nullable types provided in PHP 7.1 (http://php.net/manual/en/migration71.new-features.php)

## [1.1.0] - 2017-07-27
### Added
- Make it possible to set log message prefix

## [1.0.0] - 2017-03-24
### Added
- This is an initial release of the component - based on the code written by me and included inside the maleficarum API repository.
