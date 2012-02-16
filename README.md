Xoket (zah-ket) is about learning and sharing.

http://www.velvetcache.org/2012/02/16/xoket-the-learning-framework

# Principles

# 1. Documentation

As stated above, documentation is essential. PHPDoc formatting will be used.

# 2. MVC

Xoket will be a single request, MVC framework.  HMVC is popular, but in the interest of complexity, we will not be implementing multiple request.

# 3. Explicit is better than Implicit

Taking a queue from [The Zen of Python](http://www.python.org/dev/peps/pep-0020/) I will try to write explicitly, instead of using implicit magic. Unusual technique will be commented and discussed.

# 4. Modular

As much functionality that can be moved out of the core, should be kept out of the core. Auto-loading will be [PSR-0](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md) compatible, but also include some cascading functionality similar to [Kohana](http://kohanaframework.org/3.0/guide/kohana/files).

# 5. Modern

Xoket will be designed for PHP 5.3 and higher. If you aren't running modern PHP you should, there really isn't a good excuse.

