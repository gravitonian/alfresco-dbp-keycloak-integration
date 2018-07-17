# Alfresco Digital Business Platform (DBP) integration with Alfresco Identity Service (i.e. Keycloak)

This project is the source code for the "Getting Started with Alfresco Identity Service EA (Keycloak)" article.

It shows how to enable Single Sign On (SSO) for ACS, APS, and ADF applications.
It also shows how to connect Keycloak to an external directory server.

The complete DBP solution can be started up by navigating into the /docker-compose directory
and executing $ docker-compose up

However, for APS to work properly you need an Enterprise license, which you can get from a trial download at
https://www.alfresco.com/platform/process-services-bpm/trial/download. After downloading the license put it in the
/docker-compose/aps/enterprise-license directory.
