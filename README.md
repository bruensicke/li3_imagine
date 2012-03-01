# li3_imagine

Lithium library for image manipulation using Imagine [PHP Imagine](https://github.com/avalanche123/Imagine).

Imagine version: `0.2.8`

## Installation

Add a submodule to your li3 libraries:

	git submodule add git@github.com:bruensicke/li3_imagine.git libraries/li3_imagine

and activate it in you app (config/bootstrap/libraries.php), of course:

	Libraries::add('li3_imagine');

You can also use it directly like this:

	Libraries::add('Imagine', array(
		'prefix' => 'Imagine\\',
		'path' => LITHIUM_LIBRARY_PATH . '/Imagine/lib/Imagine',
	));

## Credits

* [li3](http://www.lithify.me)

Please report any bug, here: https://github.com/bruensicke/li3_imagine/issues





