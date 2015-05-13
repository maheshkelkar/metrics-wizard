# Metrics Wizard

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/lookout/metrics-wizard)
[![Build Status](https://travis-ci.org/lookout/metrics-wizard.svg?branch=master)](https://travis-ci.org/lookout/metrics-wizard)

Metrics Wizard is a Java agent for aggregating and reporting on metrics from
any JVM process.

The agent will scan and automatically register metrics based on
long/integer/float values in the MBeans of the monitored JVM process.

## Exporting metrics from your application

We highly recommend using
[dropwizard-metrics](https://dropwizard.github.io/metrics/3.1.0/) for the
reporting of metrics in various forms from within an existing application.

## Exporting metrics from an existing application

Metrics Wizard is built to scan the tree of attributes in JMX and monitor the
metrics presented. For the most part plugging Metrics Wizard into an existing
process, like Cassandra, should "just work."

## Helpful links

 * [Gitter chat room for Metrics-Wizard](https://gitter.im/lookout/metrics-wizard)
 * [Metrics-Wizard homepage](http://hackers.lookout.com/metrics-wizard/)
