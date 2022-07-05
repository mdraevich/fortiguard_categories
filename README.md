# FortiGuard Webfilter categories

## Introduction
The file [categories.yml](./categories.yml) contains a complete list of FortiGuard categories:
- **category description**;
- **web resource** that belongs to the category;
- **integer value** that is used to reference the category in FortiGate configuration file.

## Why?
If you're familiar with FortiGate, you've already known that all Webfilter FortiGuard categories are presented as integer values in configuration file.

While it's quiet reasonable solution from the configuration perspective, it also acts like a roadblock on the way to automation of Webfilter checks -- it's pretty hard to find out the mapping between an integer value and an appropriate web resource.