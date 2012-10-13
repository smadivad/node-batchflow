0.3.0 / 2012-10-13
------------------
* Added `total` and `finished` fields.
* Added `limit` parameter to `parallel()`.
* Changed behavior that keeps batchflow processing if an error occurs instead of stopping before it iterates all items.
* Major refactoring of tests and code.

0.2.0 / 2012-09-16
------------------
* When no parameter is passed to `done()/next()`, then `undefined` is not added to the `results` array of the `end()` callback.

0.1.0 / 2012-09-06
------------------
* Errors would not throw or show up if generated in `each` method and no error handler was set. 
* Fixed bug from `0.0.4` that would still cause an empty collection to execute at least one `each()`. 

0.0.4 / 2012-09-05
------------------
* Fixed bug that would execute `each()` on an empty collection.

0.0.3 / 2012-08-15
------------------
* Fixed bug when array or object contained any synchronous data.

0.0.2 / 2012-08-14
------------------
* Added `error` method.
* Made `series()` an alias for `sequential()`.

0.0.1 / 2012-08-14
------------------
* Initial release.