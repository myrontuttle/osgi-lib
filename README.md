osgi-lib
========

OSGi-fied Library

Server
---------
* Install Karaf 2.3.2
* features:install webconsole (or features:install http if you just want command prompt)
* features:install transaction
* features:install jpa

For Web
---------
* wicket-*
* javax.inject
* ops4j-base-lang
* org.apache.log4j
* org.apache.servicemix.bundles.cglib-2.2.2
* org.ops4j.pax.wicket.service

For Database
------------
* commons-*
* org.apache.servicemix.bundles.serp
* geronimo-jpa_2.0_spec (not sure if this is only needed for Dev)
* openjpa-2.2.2
* db-command -> Adds console commands for DB interaction
* datasource-h2 -> H2 datasource (contains directions for drivers)

For Application
---------------
* org.uncommons.maths -> Sci Evolve
* com.google.guava -> Sci Evolve
* joda-time -> Trade Adapt & Web
* javax.mail -> Trade Alert Receivers
