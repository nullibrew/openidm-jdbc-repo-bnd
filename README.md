# openidm-jdbc-repo-bnd
<p>Gradle project to automate/ease creation of OpenIDM jdbc repo bundles</p>

<p>Usage
<ol>
<li>install gradle</li>
<li>Download jdbc jar and place it in /lib (currenlty only ojdbc6.jar)</li>
<li>run 'gradle wrap'</li>
</ol>
</p>

<p>The project will download biz.aQute.bnd from maven central, execute the command, and output the new jar file into /build</p>

<p>reference docs: http://openidm.forgerock.org/doc/bootstrap/install-guide/#repository-oracledb</p>
