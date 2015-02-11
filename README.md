# openidm-jdbc-repo-bnd
Gradle project to automate/ease creation of OpenIDM jdbc repo bundles

Usage
1.) install gradle
2.) Download jdbc jar and place it in /lib (currenlty only ojdbc6.jar)
3.) run 'gradle wrap'


The project will download biz.aQute.bnd from maven central, execute the command, and output the new jar file into /build

reference docs: http://openidm.forgerock.org/doc/bootstrap/install-guide/#repository-oracledb
