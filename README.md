ihe-iti
=======

![Bender](http://i.imgur.com/M6TjMim.jpg)

A better description
--------------------

IHE has a bunch of profiles as part of the IT Infrastructure (ITI) Framework.
Like anything related to healthcare, it comes with its own quirks. Also given
that these profiles use SOAP Web Services and use MTOM and JAXB doesn't like
a lot of things that are being done here, any developer is likely to have a
tough time dealing with these profiles.

This project aims to make it easier for anyone who wants to work with these
profiles.

Usage
-----

If you want to download the library from Sonatype, add this to your dependencies
section:

    com.github.rahulsom:ihe-iti:0.5

To browse the latest builds, you can see [MavenRepository](http://mvnrepository.com/artifact/com.github.rahulsom/ihe-iti). It also has instructions for Maven, Gradle, Ivy, sbt, etc.

And add this to your repositories section:

    https://oss.sonatype.org/content/groups/public
    
You can browse latest snapshots on:

    http://oss.sonatype.org/content/repositories/snapshots/com/github/rahulsom/ihe-iti/
    
Alternately you can download and build this locally. This project is built using
Maven. Just clone the repo & checkout the branch, and run

    mvn install

That should make it possible for you to use these classes.

Sample code is [here](http://rahulsom.github.io/ihe-iti/).

Contributing
------------

A lot of profiles are not being built because they haven't been tested. If you
feel you need to use one of these, please feel free to modify the pom and send
a pull request.

Issue tracking is done through GitHub at [https://github.com/rahulsom/ihe-iti/issues](https://github.com/rahulsom/ihe-iti/issues). Feel free to raise issues or fix open issues.

Questions & Discussion
----------------------

There's a Google Groups Mailing list at [ihe-iti](https://groups.google.com/d/forum/ihe-iti). That's the best way to get answers.

Builds
------

This project is being built on travis. See
[https://travis-ci.org/rahulsom/ihe-iti](https://travis-ci.org/rahulsom/ihe-iti)
It gets automatically deployed to [Sonatype OSS](https://oss.sonatype.org/).

[![Build Status](https://travis-ci.org/rahulsom/ihe-iti.png)](https://travis-ci.org/rahulsom/ihe-iti)
