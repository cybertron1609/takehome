uriparse
========

A sample URI parser I wrote for an interview.

Specifically, the company wanted me to tackle #2 from [this](http://www.businessinsider.com/heres-the-test-you-have-to-pass-to-work-at-quora-silicon-valleys-hot-new-86-million-startup-2010-4), or more precisely:

In Python, write a class or module with a bunch of functions for manipulating a URI. For this exercise, pretend that the urllib, urllib2, and urlparse modules don't exist. You can use other standard Python modules, such as re, for this. The focus of the class or module you write should be around usage on the web, so you'll want to have things that make it easier to update or append a querystring var, get the scheme for a URI, etc., and you may want to include ways to figure out the domain for a URL (British-site.co.uk, us-site.com, etc.)

We're looking for correctness (you'll probably want to read the relevant RFCs; make sure you handle edge cases), and elegance of your API (does it let you do the things you commonly want to do with URIs in a really straightforward way?,) as well as coding style. If you don't know Python already, then this is also an exercise in learning new things quickly and well. Your code should be well-commented and documented and conform to the guidlines in the PEP 8 Style Guide for Python Code. Include some instructions and examples of usage in your documentation. You may also want to write unit tests.
