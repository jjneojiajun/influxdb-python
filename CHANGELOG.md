# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v1.1.0]
- Re-added the main functions for influxdb 
- Adjusted the name for the functions to add relay in front for clarity

## [v1.0.0]
- Forked code from the main repository 'https://github.com/influxdata/influxdb-python'
- Created the admin_request function 
- Edited these functions from the main repository client files:
 1. create_database
 2. drop_database
 3. create_retention_policy
 4. alter_retention_policy
 5. drop_measurement
 6. create_user
 7. grant_admin_privileges
 8. create_continuous_query
 9. drop_continuous_query
 