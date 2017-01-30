# Daemontools Integration

## Overview

Get metrics from daemontools service in real time to:

* Visualize and monitor daemontools states
* Be notified about daemontools failovers and events.

## Installation

Install the `dd-check-daemontools` package manually or with your favorite configuration manager

## Configuration

Edit the `daemontools.yaml` file to point to your server and port, set the masters to monitor

## Validation

When you run `datadog-agent info` you should see something like the following:

    Checks
    ======

        daemontools
        -----------
          - instance #0 [OK]
          - Collected 39 metrics, 0 events & 7 service checks

## Compatibility

The daemontools check is compatible with all major platforms
