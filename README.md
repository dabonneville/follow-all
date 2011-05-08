Follow All
==========
Follow All allows you to enter the name of any public Twitter list and follow
all the members of that list.

Continuous Integration
----------------------
[![Build Status](http://travis-ci.org/codeforamerica/follow-all.png)](http://travis-ci.org/codeforamerica/follow-all)

Demo
----
You can see a running version of the application at
<http://follow-all.heroku.com/>.

Installation
------------
    git clone git://github.com/codeforamerica/follow-all.git
    cd follow-all
    bundle install

Usage
-----
Running your own instance of Follow All requires you to [register an app with
Twitter](http://dev.twitter.com/apps) to obtain OAuth credentials. Once you
obtain credentials, substitute your consumer key and secret into the command
below.

    CONSUMER_KEY=abc CONSUMER_SECRET=123 rails server