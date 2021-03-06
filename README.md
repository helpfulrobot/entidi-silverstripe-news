silverstripe-news
=================

The [silverstripe-news](http://silverstripe.entidi.com/) module
implements two new page types for handling a typical basic news system:
*NewsHolder* (the folder containing related news) and *NewsPage* (the
page presenting a single news).

Every `NewsHolder` will have its own feed and by default it will render
its children (supposedly all `NewsPage` instances) in a `<dl>` list.

Features
--------

* Should work out-of-the-box.
* Ready to use templates compatible with the
  [silverstrap](http://dev.entidi.com/p/silverstrap/) theme.
* Atom 1.0 feed for every `NewsHolder` instance: it can be accessed by
  specificaly requesting an `application/atom+xml` mime type at the
  `NewsHolder` URL or by accessing the `feed` news underneath it, e.g.
  `http://mysite/news/feed/`.
* Back-end fully localized.
* Author customizable for every `NewsHolder` instance.
* Author customizable for every `NewsPage` instance.

Support
-------

For bug reports or feature requests, please use the dedicated
[development tracker](http://dev.entidi.com/p/silverstripe-news/).
