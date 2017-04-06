===============================
pynotedb
===============================

This will be a python parser for NoteDB. This repository is currently empty.

About NoteDB
------------

NoteDB is a way of organising review content so that it is stored as 
git objects in the same git repo as the code,
originally created by the people at gerrit. See here for more:

https://gerrit.googlesource.com/homepage/+/md-pages/docs/Notedb.md

https://github.com/CodethinkLabs/pynotedb/blob/master/rfc.mkd

This project
------------

This is a WIP python NoteDB parser.

The goal is to make an API that can be used for code review,
for cases when teams wish to keep the details of review in the same place as 
the code. By providing an API for NoteDB specifically, 
there are multiple benefits, eg: review metadata is preserved if the code 
is moved and offline code review is possible.

The API itself will provide a pluggable interface for interacting with review 
metadata, allowing people to more easily extend the ecosystem around code 
review with custom components, and communicate with existing review systems.

The existing implementations for NoteDB parsers and APIs are in Java and Perl.
As python is a popular language, this python version is intended for better
interoperability with existing tools written in python.

* Free software: Apache license
* Documentation: http://docs.openstack.org/developer/pynotedb
* Source: http://git.openstack.org/cgit/openstack-infra/pynotedb
* Bugs: http://bugs.launchpad.net/pynotedb

Features
--------

* TODO
