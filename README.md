# Splendid Tech
My not only awesome but actually splendid tech stack. Verified to be splendid and used on a nearly daily basis. BTW I'm mostly a back-end guy.

- [Blog](https://aboutsimon.com/blog/)
- [Twitter](https://twitter.com/aboutsimon)

## Highlights
My absolute favorites which made me think and deserve extra attention.

### PyPy
- [Website](http://pypy.org/)
- PyPy is a replacement for CPython. It is built using the RPython language that was co-developed with it. The main reason to use it instead of CPython is speed: it runs generally faster.

This is the home of dark magic. [JIT](https://en.wikipedia.org/wiki/Just-in-time_compilation) + [RPython](https://rpython.readthedocs.org/en/latest/) + Stackless. Also all [efforts](http://pypy.org/tmdonate2.html) to remove the [Global Interpreter Lock](https://wiki.python.org/moin/GlobalInterpreterLock) from a Python language are highly appreciated. The PyPy team IMHO is trying to make the world of dynamic languages a better place.

### Sophia
- [Website](http://sphia.org/)
- [Github](https://github.com/pmwkaa/sophia)
- Append-Only MVCC storage designed for fast write and read, small to medium key-values.

I was working on several databases to solve very specific problems over the last years. I tried several storage back-ends/libraries like [LevelDB](https://github.com/google/leveldb), [RocksDB](http://rocksdb.org/), [HyperLevelDB](http://hyperdex.org/performance/leveldb/), [LMDB](http://symas.com/mdb/) or [TokuDB](https://www.percona.com/software/mysql-database/percona-tokudb), but Sophia really is killer and deserves way more attention.

## Algos
- [smhasher](https://code.google.com/p/smhasher/) MurmurHash the fast non-cryptographic hash function
- [LZ4](https://github.com/Cyan4973/lz4) Lossless compression algorithm, providing compression speed at 400 MB/s per core, scalable with multi-cores CPU
- [HyperLogLog](https://en.wikipedia.org/wiki/HyperLogLog) Probabilistic cardinality estimator. Efficiently count very large data sets.

## Data formats

- [msgpack](http://msgpack.org/) Efficient binary serialization format. JSON in fast and small.

## Libraries & Frameworks

### C / C++
- [hiredis](https://github.com/redis/hiredis) Minimalistic C client for redis
- [MARISA Trie](https://code.google.com/p/marisa-trie/) A static and space-efficient trie data structure. Supports lookup, reverse lookup, common prefix search and predictive search
- [Sophia](http://sphia.org/) Append-Only MVCC storage designed for fast write and read, small to medium key-values

### Python

- [Arrow](http://crsmithdev.com/arrow/) Date and time library
- [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) Screen-scraping library
- [Bottle](http://bottlepy.org/docs/dev/index.html) Lightweight WSGI micro web-framework
- [cffi](https://cffi.readthedocs.org/en/latest/) C Foreign Function Interface for Python
- [Flask](http://flask.pocoo.org/) A micro web-framework
- [hiredis-py](https://github.com/redis/hiredis-py) Wrapper for hiredis
- [ipaddr](https://github.com/google/ipaddr-py) Google's Python IP address manipulation library
- [objgraph](https://mg.pov.lt/objgraph/) A module to visually explore Python object graphs
- [py-radix](https://github.com/mjschultz/py-radix) Radix tree implementation for IPv4 and IPv6 prefix matching
- [pybloomfiltermmap](https://github.com/axiak/pybloomfiltermmap) Fast Python Bloom Filter using Mmap
- [PyLucene](http://lucene.apache.org/pylucene/) API to Java Lucene
- [Pyparsing](http://pyparsing.wikispaces.com/) Library to create and execute simple grammars
- [Requests](http://docs.python-requests.org/en/latest/) HTTP library
- [Scrapy](http://scrapy.org/) A web scraping framework
- [ujson](https://github.com/esnme/ultrajson) Ultra fast JSON encoder and decoder
- [Yapps](https://wiki.python.org/moin/Yapps) Easy to use parser generator
- [marisa-trie](https://pypi.python.org/pypi/marisa-trie) API to MARISA Trie C++ library
- [Jinja2](http://jinja.pocoo.org/) Template engine
- [gevent](http://www.gevent.org/) Coroutine-based networking library using greenlets

### JavaScript
- [Backbone.js](http://backbonejs.org/) Solid library for single page application
- [backbone.radio](https://github.com/marionettejs/backbone.radio) Messaging library for Backbone applications
- [Marionette.js](http://marionettejs.com/) SPA framework using Backbone.js
- [Moment.js](http://momentjs.com/) Parse, validate, manipulate, and display dates
- [Parsley](http://parsleyjs.org/) Form validation library
- [JADE](http://jade-lang.com/) Template engine

### Java
- [Lucene](https://lucene.apache.org/core/) High-performance, full-featured text search engine library

## Programs & Tools

### App managers
- [supervisord](http://supervisord.org/) A client/server system to monitor and control processes
- [uWSGI](https://uwsgi-docs.readthedocs.org/en/latest/) Application server, proxies, process managers and monitors implemented in a common API and a common configuration style

### Storage / Databases
- [ElasticSearch](https://www.elastic.co/products/elasticsearch) Distributed, RESTful Search Engine based on Lucene. Hyped but evolved into something beautiful
- [redis](http://redis.io/) In-memory data structure store, used as database, cache and message broker
- [RethinkDB](https://www.rethinkdb.com/) JSON database with nice API. Lovely for prototyping and small applications

### Dev Tools
- [virtualenv](https://virtualenv.readthedocs.org/en/latest/) Isolated Python environments
- [virtualenvwrapper](https://virtualenvwrapper.readthedocs.org/en/latest/) Set of extensions to virtualenv

## Front-end Dev
- [Bootstrap](http://getbootstrap.com/) Most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web
- [Font Awesome](http://fortawesome.github.com/Font-Awesome/) Font and CSS toolkit
- [Yeoman](http://yeoman.io/) Scaffolding tool for web applications
- [Grunt](http://gruntjs.com/) Task runner for repetitive tasks like minification, compilation, unit testing, linting, etc
- [Jekyll](https://github.com/jekyll/jekyll) A blog-aware, static site generator in Ruby

## Operations
- [Nginx HTTP server boilerplate configs](https://github.com/h5bp/server-configs-nginx) Collection of configuration snippets that can help your server improve the web site's performance and security
- [SSH Can Do That? Productivity Tips for Working with Remote Servers](http://blogs.perl.org/users/smylers/2011/08/ssh-productivity-tips.html)

## Lists
- [Fast Non-Standard Data Structures for Python](http://kmike.ru/python-data-structures/)
- [Queues](http://queues.io/) Quality list of queues with a collection of articles, blog posts, slides, and videos about them
- [Stream Processing Papers](https://cwiki.apache.org/confluence/display/SAMZA/Stream+Processing+Papers)
- [Tools to measure system performance and OS jitter](http://highscalability.com/blog/2015/5/27/a-toolkit-to-measure-basic-system-performance-and-os-jitter.html) Toolkits to measure basic system performance and OS jitter

## Websites & Blog Posts
- [commandlinefu](http://www.commandlinefu.com/commands/browse/sort-by-votes) The place to record those command-line gems that you return to again and again
- [High Scalability](http://highscalability.com/) Blog with good posts about scalability and performance topics
- [How L1 and L2 CPU caches work](http://www.extremetech.com/extreme/188776-how-l1-and-l2-cpu-caches-work-and-why-theyre-an-essential-part-of-modern-chips)
- [How Pony (ORM) does its tricks?](http://stackoverflow.com/questions/16115713/how-pony-orm-does-its-tricks)
- [Understanding CPU utilization](http://careers.directi.com/display/tu/Understanding+CPU+Utilization+and+Optimization)
- [What Your Computer Does While You Wait](http://duartes.org/gustavo/blog/post/what-your-computer-does-while-you-wait/)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
