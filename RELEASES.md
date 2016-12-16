# Release Notes

## v1.4.0 (12 December 2016)
* Removes PHP ActiveRecord's autoloader, as Composer usage is now widespread [#5](https://github.com/zamzar/php-activerecord/issues/5)

## v1.3.1 (1 December 2016)
* Fixed a bug in which PDO exceptions thrown when starting a transactions would not be reported correctly [#3](https://github.com/zamzar/php-activerecord/issues/3)

## v1.3.0 (31 October 2016)
* Adds PHP 7 compatibility

## v1.2.0 (30 September 2016)
* First release of Zamzar fork of `php-activerecord/php-activerecord`
* Added a simple, file-based implementation of PHP AR cache for installs without memcached [#2](https://github.com/zamzar/php-activerecord/issues/2)
* Fixed a bug in which foreign keys would not be set when using `create_association` [#1](https://github.com/zamzar/php-activerecord/issues/1)