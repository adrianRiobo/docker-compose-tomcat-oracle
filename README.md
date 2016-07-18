# docker-compose-tomcat-oracle

This is a sample two tier web application. It uses compose to create two containers:

Front Container is a Tomcat based container. It adds oracle client utilities for oracle 11g and scripts to check for db initialization in the linked Data Container to continue wih web app deploy on container initialization.

Data Container is an Oracle 11g XE bases container.
