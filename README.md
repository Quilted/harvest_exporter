# Harvest Exporter

A Ruby command line app that exports data from a [Harvest](http://getharvest.com/) account.

# Usage

## General

    ruby harvest_exporter
    
## Export Project Budget Estimates and Actuals

    ruby harvest_exporter budget
    
Use the --filename option to specify a different filename with relative filepath

    ruby harvest_exporter budget --filename [filename with relative filepath]