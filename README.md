Sentinel
========
[![Build Status](https://travis-ci.org/foxjerem/sentinel.svg?branch=master)](https://travis-ci.org/foxjerem/sentinel)
[![Code Climate](https://codeclimate.com/github/foxjerem/sentinel/badges/gpa.svg)](https://codeclimate.com/github/foxjerem/sentinel)
[![Test Coverage](https://codeclimate.com/github/foxjerem/sentinel/badges/coverage.svg)](https://codeclimate.com/github/foxjerem/sentinel)

A log auditor / visualizer to detect malicious or suspicious activity patterns in web application access. Powered by the elastic search API.

## TODO:
* Add mock ES API server to allow all testing to be done online
* Refactor settings
* Add settings test coverage
* Setup feature_helper config
* Size markers based on access count and display IP on hover
* Set maximum size on single ES query of 500 records
* Throw error if single query returns more than 500 records
* Figure out ES query pagination
* Refactor analytics engine

Create mock API server
Create mock API client
Create mock record builder based on JSON template
Add environment variables

[NB: This repository is a work in progress]