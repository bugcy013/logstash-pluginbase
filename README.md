logstash-pluginbase
===================

A base repo to make logstash plugins.

Gem Dependencies
================

To add a Ruby Gem dependancy, modify the logstash-contrib.gemspec file and add something like the following:

gem.add_runtime_dependency "net-http-persistent"

Java Dependencies
=================

Work in Progress

Build
=====

Run 'make tarball' to build the project. A tarball will end up in ./build. Extract the file over top of your logstash directory. 
(Hint: or, just copy the ./lib and ./vendor directories to your logstash folder)

Todo
====

Currently, the project will build as logstash-contrib which isn't what we want :)
