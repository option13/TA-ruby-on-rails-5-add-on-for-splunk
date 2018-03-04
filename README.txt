This add-on provides Splunk knowledge objects for Ruby on Rails 5.x applications

INSTALLATION
Install this add-on on search heads and forwarders. There are no index-time
extractions, so it is not required on indexers.
Define an input to monitor your app's production.log file, and set the
sourcetype to ruby_on_rails_5_x.

PREREQUISITES
config.log_level for the rails app is set to debug.

CIM COMPLIANCE
This add-one's fields are named to be compatible with the CIM Web data model.
