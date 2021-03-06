Goods
=======================================================================

Need data structures for your Go app? We've got the goods.

Overview
-----------------------------------------------------------------------

Goods is a collection of some of the most used data structures around:

* Linkedlist
* Queue
* Stack
* Binary Tree
* Red-Black Tree

Linkedlist, Queue, and Stack are completely **thread-safe**!

Usage
-----------------------------------------------------------------------

Please see the [provided examples](https://github.com/emnl/goods/tree/master/examples).

The tests are a great resources for understanding how Goods should be used. They can be found in each subdir (package) — tests filenames ends with "_test.go".

Goods is abstracted in such a way that you wont have to deal with nodes, only your own values.

Documentation
-----------------------------------------------------------------------

The Goods API reference is available on GoPkgDoc:

* [Linkedlist](http://go.pkgdoc.org/github.com/emnl/goods/linkedlist)
* [Queue](http://go.pkgdoc.org/github.com/emnl/goods/queue)
* [Stack](http://go.pkgdoc.org/github.com/emnl/goods/stack)
* [Binary Tree](http://go.pkgdoc.org/github.com/emnl/goods/binarytree)
* [Red-Black Tree](http://go.pkgdoc.org/github.com/emnl/goods/redblacktree)

Installation
-----------------------------------------------------------------------

First (go) get your prefered package:

	$ go get github.com/emnl/goods/linkedlist


Then import it into your project:

	import "github.com/emnl/goods/linkedlist"


Testing
-----------------------------------------------------------------------

While in a subdir, just run:

	$ go test

All test (from root):

	$ sh test.sh

License
-----------------------------------------------------------------------

Copyright (C) 2012 Emanuel Andersson

MIT License ([more info](http://en.wikipedia.org/wiki/MIT_License))
