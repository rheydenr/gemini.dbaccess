
Gemini DBAccess 1.1 Release - February 6, 2013

The Gemini DBAccess is about providing modularized access to JDBC resources (OSGi). 
The bundles below exports a DataSourceFactory object so that client applications of the JDBC driver 
can import and access the features of the driver without having to package the driver as part of the application.

DBAccess implements the JDBC Service Specification Version 1.0 of the OSGi Service 
Platform Enterprise Specification, Release 4, Version 4.2, section 125.

This version of DBAccess provides you with the database access to the database platforms listed below.
(please also visit the wiki for forther information: http://wiki.eclipse.org/Gemini/DBAccess/SupportedDrivers):

Derby:
osgi.enterprise_<version>.jar
org.eclipse.gemini.dbaccess.derby_<version>.jar
org.eclipse.gemini.dbaccess.util_<version>.jar
org.eclipse.gemini.dbaccess.samples_<version>.jar
org.apache.derby_<version>.jar (currently 10.8.2.2)

Note: To use versions of Derby other than 10.8.2.2 you may need to replace the derby.jar and derbyclient.jar 
driver jars inside the org.apache.derby bundle with the version that you require.


MySQL:
osgi.enterprise_<version>.jar
org.eclipse.gemini.dbaccess.mysql_<version>.jar
org.eclipse.gemini.dbaccess.util_<version>.jar
mysql-connector-java-5.1.20-bin.jar (not included, please download here: http://www.mysql.com/downloads/connector/j/)

HSQLDB:
osgi.enterprise_<version>.jar
org.eclipse.gemini.dbaccess.hsqldb_<version>.jar
org.eclipse.gemini.dbaccess.util_<version>.jar
hsqldb.jar (not included, please download here: http://sourceforge.net/projects/hsqldb/files/)

H2:
osgi.enterprise_<version>.jar
org.eclipse.gemini.dbaccess.hsqldb_<version>.jar
org.eclipse.gemini.dbaccess.util_<version>.jar
h2-<version>.jar (not included, please download here: http://www.h2database.com/html/download.html)
