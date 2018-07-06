# statsd-bash

[![License](https://img.shields.io/github/license/unixorn/statsd-bash.svg)](https://opensource.org/licenses/Apache-2.0)
[![Build Status](https://travis-ci.org/unixorn/statsd-bash.svg?branch=master)](https://travis-ci.org/unixorn/statsd-bash)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/statsd-bash.svg)](https://github.com/unixorn/statsd-bash/stargazers)
[![Code Climate](https://codeclimate.com/github/unixorn/statsd-bash/badges/gpa.svg)](https://codeclimate.com/github/unixorn/statsd-bash)
[![Issue Count](https://codeclimate.com/github/unixorn/statsd-bash/badges/issue_count.svg)](https://codeclimate.com/github/unixorn/statsd-bash)

Bash script to write to statsd

Usage: `write-statsd metricName metricValue`

`write-statsd` defaults to using port 8125 on localhost; set `STATSD_HOST` and `STATSD_PORT` in the environment to change that.
