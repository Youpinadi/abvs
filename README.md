ABVS (Apache Bench Versus)
=============

abvs is a very simple command in order to estimate perf of a page versus an other.
It can be used to compare 2 websites, or to compare same pages of a site to see if a modification improves or decreases the performances.

Options
-------

* -n Number of requests
* -c Number of concurrent requests
* url1 the first url to test
* url2 the second url to test

Sample usage
-------

    ./abvs http://www.google.com/ http://www.google.fr/

Output:
    ab  http://www.google.com/
    ab  http://www.google.fr/
    http://www.google.com/ (40 req/s) is 9.82% faster than http://www.google.fr/ (36 req/s)

Contributing
------------

Want to contribute? Great! Send me your patches!