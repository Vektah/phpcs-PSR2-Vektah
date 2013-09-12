vektah/psr-2
------------

This is a slightly releaxed PSR-2 ruleset for phpcs.

 * Does not check line length: Screens keep getting wider, why doesnt our code?
 * Does not limit to one param per line for multi line functions: Its often much clearer to have:

```
foo([
	'asdf' => 'hjkl',
]);
```
compared to
```
foo(
	[
		'asdf' => 'hjkl',
	]
);
```
