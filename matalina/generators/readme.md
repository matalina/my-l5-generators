# My Artisan File Generator

I got tired of writing the same file stubs over and over again.  The following types of files have been created in this package
Note:  I'm having difficulty wrapping my head around making this a composer package.  I get the basics but somethings not quite working for me.

* Interface stubs (`artisan make:interface DummyInterface`)
* Repository stubs extending an interface (`artisan make:repository DummyRepository DummyInterface`)
* Route Binder file for [LaravelBA/route-binder](https://github.com/LaravelBA/route-binder) (`artisan make:route DummyRouteBinder`)
* Create a Model file with corresponding interface and repository of the same name  (`artisan make:rim Dummy`)