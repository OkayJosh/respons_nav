Respons_nav Application
========================

The "Navigation Application" is a reference application created to show how
to develop navigation component leveraging on the svg html elements and the canvas html element.

Requirements
------------

  * PHP 7.1.3 or higher;
  * and the [usual Symfony application requirements][1].

How to run the application
--------------------------
	* open the directory that you clone the application in the command line
	* 	```bash
		$ cd respons_nav
		$ php bin/console server:run
		```

Usage
-----

There's no need to configure anything to run the application. Just execute this
command to run the built-in web server and access the application in your
browser at <http://localhost:8000>:

Alternatively, you can [configure a fully-featured web server][2] like Nginx
or Apache to run the application.

Tests
-----

Execute this command to run tests:

```bash
$ cd respoms_nav/
$ ./vendor/bin/simple-phpunit
```

[1]: https://symfony.com/doc/current/reference/requirements.html
[2]: https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
