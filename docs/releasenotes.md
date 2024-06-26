---
layout: docs
menu: releasenotes
subtitle: 'Release Notes for the CloudCaptain Client'
---

Version 1.36.2 (2024-05-07)
---------------------------
- OpenJDK 21 support

Version 1.36.1 (2024-02-01)
---------------------------
- #296 Automatically disable progress bar on GitHub Actions and BitBucket

Version 1.36.0 (2024-01-23)
---------------------------
- Support for Play 3.0 payloads
- Updated cacerts to 2024.01.20

Version 1.35.5 (2023-07-11)
---------------------------
- Support for larger payloads up to 1 GB

Version 1.35.4 (2023-07-10)
---------------------------
- Added support for m6in, r6in, c6in instances

Version 1.35.3 (2023-02-01)
---------------------------
- #228 Error on NewRelic keys for EU servers
- #281 Error on valid NewRelic keys

Version 1.35.2 (2022-01-12)
---------------------------
- Renamed Boxfuse to CloudCaptain in copyright message
- #257 Fixed ERROR: Hyper-V is not supported on your OS

Version 1.35.1 (2021-12-06)
---------------------------
- #262 Fixed support for m6i, r6i, c6i and db.t4g instances

Version 1.35.0 (2021-12-01)
---------------------------
- Default to OpenJDK 17

Version 1.34.0 (2021-11-27)
---------------------------
- #262 Added support for m6i, r6i, c6i and db.t4g instances

Version 1.33.9 (2021-11-03)
---------------------------
- #210 Fixed JMX Remote Access for Java 9+

Version 1.33.8 (2021-11-03)
---------------------------
- #210 OpenJDK 17.0.0.1 support with jdk.management.agent module

Version 1.33.7 (2021-11-02)
---------------------------
- #210 OpenJDK 17.0.0 support

Version 1.33.6 (2021-09-17)
---------------------------
- #259 Fix NewRelic Java agent download

Version 1.33.5 (2021-07-20)
---------------------------
- #254 Fix sysctl.conf support for Tomcat payloads

Version 1.33.4 (2021-05-27)
---------------------------
- Java 11 support (preview)

Version 1.33.3 (2020-02-10)
---------------------------
- New Relic license keys ending with NRAL support
- Do not launch JVM with -d64

Version 1.33.2 (2020-01-14)
---------------------------
- RDS 2019 certificates for JVM apps support

Version 1.33.1 (2019-11-27)
---------------------------
- RDS 2019 certificates for Node.js apps support

<h2 id="1.33.0.1460">Version 1.33.0.1460 (2018-08-23)</h2>
<p><strong>Important: the CloudCaptain Client now requires Java 8 to run (up from Java 7 previously)</strong></p>
<ul>
    <li>Spring Boot 2.0 support</li>
    <li>t3 and r5 EC2 instance support</li>
</ul>

<h2 id="1.32.2.1447">Version 1.32.2.1447 (2018-03-20)</h2>
<ul>
    <li>Fix /tmp mounting for NVMe volumes (m5 and c5 instances)</li>
</ul>

<h2 id="1.32.1.1442">Version 1.32.1.1442 (2018-02-20)</h2>
<ul>
    <li>AWS long IDs support</li>
</ul>

<h2 id="1.32.0.1441">Version 1.32.0.1441 (2018-02-12)</h2>
<ul>
    <li>Private Vault support</li>
</ul>

<h2 id="1.31.1.1429">Version 1.31.1.1429 (2018-01-23)</h2>
<ul>
    <li>Fixed NVMe storage detection</li>
    <li>Fixed Node.js debugging in newer Node versionsAdded M5 and C5 EC2 instance support</li>
</ul>

<h2 id="1.31.0.1424">Version 1.31.0.1424 (2018-01-18)</h2>
<ul>
    <li>Added M5 and C5 EC2 instance support</li>
    <li>Upgraded to Linux 4.14.14</li>
</ul>

<h2 id="1.30.4.1421">Version 1.30.4.1421 (2018-01-09)</h2>
<ul>
    <li>JMX: Fall back to private IP if the instance doesn't have a public one</li>
</ul>

<h2 id="1.30.3.1419">Version 1.30.3.1419 (2017-11-16)</h2>
<ul>
    <li>Added support for /dev/stdin, /dev/stdout and /dev/stderr device files</li>
    <li>Fixed an issue with incomplete capacity definitions</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.30.2.1410">Version 1.30.2.1410 (2017-10-20)</h2>
<ul>
    <li>Improved robustness of open when no image was specified</li>
    <li>Extract json files from the root of DropWizard jar files to the filesystem (analog to what is already happening for yml and jks files)</li>
</ul>

<h2 id="1.30.1.1407">Version 1.30.1.1407 (2017-10-04)</h2>
<ul>
    <li>Improved robustness of invalid Dropwizard config file parsing</li>
</ul>

<h2 id="1.30.0.1405">Version 1.30.0.1405 (2017-10-03)</h2>
<ul>
    <li>Added load-balanced-https app support</li>
    <li>Fixed issue when attempting to remove non-existent image</li>
    <li>Fixed issue with open for one-off and worker apps</li>
</ul>

<h2 id="1.29.1.1400">Version 1.29.1.1400 (2017-09-15)</h2>
<ul>
    <li>Fixed display issue with logs with tail disabled</li>
    <li>Fixed Hyper-V log tailing</li>
</ul>

<h2 id="1.29.0.1396">Version 1.29.0.1396 (2017-09-04)</h2>
<ul>
    <li>One-off apps support</li>
</ul>

<h2 id="1.28.7.1392">Version 1.28.7.1392 (2017-08-23)</h2>
<ul>
    <li>Fixed an issue with Hyper-V logs hanging</li>
</ul>

<h2 id="1.28.6.1390">Version 1.28.6.1390 (2017-08-08)</h2>
<ul>
    <li>Fixed VirtualBox NAT Network forwarding rules</li>
    <li>Avoid Gradle throwing ClassCastException when inadvertently passing int values instead of Strings for certain properties</li>
</ul>

<h2 id="1.28.5.1383">Version 1.28.5.1383 (2017-08-03)</h2>
<ul>
    <li>Node.js apps started with -live now auto-reload on json file changesy</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.28.4.1381">Version 1.28.4.1381 (2017-07-13)</h2>
<ul>
    <li>Improved auto-configuration for Play 2.6</li>
    <li>More robust Hyper-V VM creation for slightly broken Hyper-V installations</li>
</ul>

<h2 id="1.28.3.1379">Version 1.28.3.1379 (2017-07-10)</h2>
<ul>
    <li>Allow overriding SPRING_PROFILES_ACTIVE during image fuse</li>
</ul>

<h2 id="1.28.2.1376">Version 1.28.2.1376 (2017-07-02)</h2>
<ul>
    <li>Fixed Hyper-V detection on certain Windows installations</li>
</ul>

<h2 id="1.28.1.1375">Version 1.28.1.1375 (2017-06-30)</h2>
<ul>
    <li>Switched to https for all third party component download sites</li>
    <li>Fixed NPE on certain macOS configurations</li>
</ul>

<h2 id="1.28.0.1372">Version 1.28.0.1372 (2017-06-28)</h2>
<ul>
    <li>Added dev environment support for Hyper-V on Windows 10 Pro machines</li>
</ul>

<h2 id="1.27.1.1353">Version 1.27.1.1353 (2017-06-07)</h2>
<ul>
    <li>Fixed domain configuration regression</li>
</ul>

<h2 id="1.27.0.1352">Version 1.27.0.1352 (2017-06-06)</h2>
<ul>
    <li>Added support for custom AWS tags to be added to AWS resources in addition to the default CloudCaptain ones</li>
    <li>Fail fast on invalid config parameters and misspellings</li>
    <li>Fixed manual database type override</li>
    <li>Fixed minimal VirtualBox version error message</li>
    <li>The default number of CPUs for a VirtualBox instance is now 2</li>
    <li>The default for virtualbox.natnetwork is now false</li>
</ul>

<h2 id="1.26.7.1312">Version 1.26.7.1312 (2017-05-20)</h2>
<ul>
    <li>Automatically adjust Linux file-max user limits to the current kernel limits</li>
</ul>

<h2 id="1.26.6.1311">Version 1.26.6.1311 (2017-05-19)</h2>
<ul>
    <li>Fixed an issue with the MySQL JDBC driver not being able to access the root certificates from the
        truststore
    </li>
</ul>

<h2 id="1.26.5.1309">Version 1.26.5.1309 (2017-05-17)</h2>
<ul>
    <li>Fixed issue when parsing Play configuration with unresolved placeholders</li>
    <li>Tomcat, TomEE, Node.js and Spring Loaded are now fetched directly from archive.apache.org, nodejs.org and
        repo.spring.io instead of the CloudCaptain Inventory
    </li>
</ul>

<h2 id="1.26.4.1303">Version 1.26.4.1303 (2017-05-08)</h2>
<ul>
    <li>Fixed regression for JVM apps that explicitly set the main class</li>
</ul>

<h2 id="1.26.3.1302">Version 1.26.3.1302 (2017-05-08)</h2>
<ul>
    <li>Fixed TLS (acm) support for Play</li>
    <li>New Relic Java and Linux agents are now fetched directly from download.newrelic.com instead of the CloudCaptain
        Inventory
    </li>
</ul>

<h2 id="1.26.2.1299">Version 1.26.2.1299 (2017-05-03)</h2>
<ul>
    <li>Added support for specifying Linux kernel arguments with <code>-linux.args</code></li>
    <li>Fixed jvm.jmx password file permission issue</li>
</ul>

<h2 id="1.26.1.1297">Version 1.26.1.1297 (2017-04-25)</h2>
<ul>
    <li>Added support for automatic TLS (SSL) certificates for load-balanced apps using AWS Certificate Manager</li>
    <li>Better detection of Play projects that only use Build.scala instead of build.sbt</li>
</ul>

<h2 id="1.26.0.1293">Version 1.26.0.1293 (2017-04-16)</h2>
<ul>
    <li>Upgraded to Linux 4.9 kernel</li>
    <li>Dropped support for VirtualBox 4.2 and 4.3 (both outdated and unsupported by Oracle) due to lack of
        compatibility with newer Linux kernel. CloudCaptain now requires VirtualBox 5.0 or newer.
    </li>
    <li>Added initial ability to mount Elastic File Systems</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.25.7.1285">Version 1.25.7.1285 (2017-04-06)</h2>
<ul>
    <li>Added support for http and https protocols in port definitions</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.25.6.1276">Version 1.25.6.1276 (2017-03-31)</h2>
<ul>
    <li>Added support for the new longer New Relic keys</li>
    <li>Fixed support for custom JREs to use JMX remote passwords</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.25.5.1274">Version 1.25.5.1274 (2017-03-24)</h2>
<ul>
    <li>CloudWatch Logs: logs.layout support</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.25.4.1271">Version 1.25.4.1271 (2017-03-22)</h2>
<ul>
    <li>CloudWatch Logs: TRACE log level support</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.25.3.1269">Version 1.25.3.1269 (2017-03-20)</h2>
<ul>
    <li>CloudWatch Logs: prefix and suffix wildcard filtering support</li>
    <li>CloudWatch Logs: message filtering support</li>
    <li>Node.js: Native bin and lib support</li>
</ul>

<h2 id="1.25.2.1265">Version 1.25.2.1265 (2017-03-15)</h2>
<ul>
    <li>Maven plugin: Support user/secret decryption</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.25.1.1262">Version 1.25.1.1262 (2017-03-01)</h2>
<ul>
    <li>Custom elastic IP support</li>
</ul>

<h2 id="1.25.0.1261">Version 1.25.0.1261 (2017-02-23)</h2>
<ul>
    <li>Custom domain support</li>
    <li>Prevent uncompiled JHipster 4 apps to be picked up as Node.js</li>
    <li>Gradle Plugin is now compatible with Spring Boot 1.5 and newer</li>
</ul>

<h2 id="1.24.9.1258">Version 1.24.9.1258 (2017-02-17)</h2>
<ul>
    <li>More JHipster 4 compatibility fixes</li>
</ul>

<h2 id="1.24.8.1257">Version 1.24.8.1257 (2017-02-16)</h2>
<ul>
    <li>Fixed JHipster 4 compatibility</li>
    <li>Autodetect disabled Spring Boot health endpoint</li>
    <li>Better detection of Node.js applications that require npm or yarn to start</li>
</ul>

<h2 id="1.24.7.1255">Version 1.24.7.1255 (2017-02-15)</h2>
<ul>
    <li>Better auto-recovery for CloudWatch Logs Mock startup issues</li>
    <li>Improved retries for failed downloadsFixed usage of logs.filters.level</li>
</ul>

<h2 id="1.24.6.1250">Version 1.24.6.1250 (2017-02-10)</h2>
<ul>
    <li>Fixed usage of logs.filters.level</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.24.5.1247">Version 1.24.5.1247 (2017-01-24)</h2>
<ul>
    <li>JVM apps: support for including native binaries and libs</li>
    <li>Extended AWS r4 instance support to all supported regions</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.24.4.1242">Version 1.24.4.1242 (2017-01-17)</h2>
<ul>
    <li>Fixed startup of Tomcat and Play images with a custom JRE</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.24.3.1226">Version 1.24.3.1226 (2017-01-15)</h2>
<ul>
    <li>Bug fixes</li>
</ul>

<h2 id="1.24.2.1223">Version 1.24.2.1223 (2017-01-13)</h2>
<ul>
    <li>VirtualBox with CloudWatch Logs: Fixed messages from previous instances of the same app being displayed on
        boot
    </li>
    <li>Commandline Client: Fixed a regression when calling run with an explicit payload name</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.24.1.1219">Version 1.24.1.1219 (2017-01-07)</h2>
<ul>
    <li>Print exit code in instance logs if application process terminates</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.24.0.1207">Version 1.24.0.1207 (2017-01-04)</h2>
<ul>
    <li>New applications now use CloudWatch Logs by default</li>
    <li>Support for larger payloads up to 512 MB</li>
    <li>Vastly reduced memory usage when fusing payloads larger than 128 MB by buffering on disk</li>
    <li>AWS ca-central-1, eu-west-2 and us-east-2 region support</li>
    <li>AWS t2.xlarge, t2.2xlarge, m4 and r4 instance type support</li>
    <li>Tomcat: support for user-supplied server.xml file</li>
</ul>

<h2 id="1.23.4.1200">Version 1.23.4.1200 (2016-12-08)</h2>
<ul>
    <li>Extended log filtering support with start, end and limit filters</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.23.3.1189">Version 1.23.3.1189 (2016-11-26)</h2>
<ul>
    <li>Fixed overriding -Xmx and -Xms with custom values</li>
    <li>Fixed version number extraction for tar.gz files</li>
</ul>

<h2 id="1.23.2.1187">Version 1.23.2.1187 (2016-11-22)</h2>
<ul>
    <li>Expose private IP address of instance as <code>BOXFUSE_INSTANCE_IP_PRIVATE</code> environment variable</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.23.1.1185">Version 1.23.1.1185 (2016-11-19)</h2>
<ul>
    <li><code>insecure</code> flag support to disable TLS certificate chain validation</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.23.0.1181">Version 1.23.0.1181 (2016-11-15)</h2>
<ul>
    <li>Generic Linux x64 app support</li>
    <li>Spring Boot: support for extracting default values from ${varname:value} config values</li>
    <li>Convert: now uses the region of the environment specified by the env property</li>
    <li>Command-line: convert now exposes the region of the AMI as a machine-readable property</li>
    <li>Maven: convert now exposes the id and region of the AMI as a Maven property</li>
    <li>Gradle: convert now exposes the id and region of the AMI as a Gradle property</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.22.4.1171">Version 1.22.4.1171 (2016-11-10)</h2>
<ul>
    <li>Log filtering support for Maven and Gradle plugins</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.22.3.1167">Version 1.22.3.1167 (2016-11-09)</h2>
<ul>
    <li>Log filtering support</li>
    <li>Colorized output</li>
</ul>

<h2 id="1.22.2.1149">Version 1.22.2.1149 (2016-10-28)</h2>
<ul>
    <li>Support for all R3 instance sizes in sa-east-1</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.22.1.1146">Version 1.22.1.1146 (2016-10-24)</h2>
<ul>
    <li>New Relic support</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.22.0.1140">Version 1.22.0.1140 (2016-09-22)</h2>
<ul>
    <li>CloudWatch Logs support</li>
    <li>Renamed apptype configuration setting to app.type</li>
    <li>Renamed dbtype configuration setting to db.type</li>
    <li>Bumped minimum required Maven version to 3.1.1</li>
    <li>Fixed support for GitHub accounts containing only digits</li>
    <li>Fixed CA certificates for Go apps</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.21.8.1115">Version 1.21.8.1115 (2016-08-21)</h2>
<ul>
    <li>Bug fixes</li>
</ul>

<h2 id="1.21.7.1111">Version 1.21.7.1111 (2016-08-19)</h2>
<ul>
    <li>Fixed error when fusing images for Play apps without any jvm.args specified</li>
</ul>

<h2 id="1.21.6.1109">Version 1.21.6.1109 (2016-08-19)</h2>
<ul>
    <li>Enable prod profile for JHipster by default</li>
    <li>Disable virtualbox.natnetwork by default</li>
    <li>Added TomEE datasource auto-configuration</li>
    <li>Added possibility to override Play database auto-configuration</li>
</ul>

<h2 id="1.21.5.1105">Version 1.21.5.1105 (2016-08-18)</h2>
<ul>
    <li>JHipster support</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.21.4.1099">Version 1.21.4.1099 (2016-08-12)</h2>
<ul>
    <li>Bug fixes</li>
</ul>

<h2 id="1.21.3.1097">Version 1.21.3.1097 (2016-08-11)</h2>
<ul>
    <li>Fixed an issue with Play keystore handling</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.21.2.1092">Version 1.21.2.1092 (2016-08-09)</h2>
<ul>
    <li>Go and Revel support</li>
    <li>Spring Boot "fully executable jar" support</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.21.1.1080">Version 1.21.1.1080 (2016-08-03)</h2>
<ul>
    <li>Bug fixes</li>
</ul>

<h2 id="1.21.0.1079">Version 1.21.0.1079 (2016-08-03)</h2>
<ul>
    <li>Worker apps support</li>
    <li>Added support for Spring Boot and Grails executable war files</li>
    <li>Added virtualbox.natnetwork networking mode for VirtualBox 5.1 and newer</li>
    <li>Image creation is now up to 25% faster</li>
</ul>

<h2 id="1.20.9.1064">Version 1.20.9.1064 (2016-07-25)</h2>
<ul>
    <li>Automatically expose AWS credentials from ~/.aws/credentials inside VirtualBox instances</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.20.8.1057">Version 1.20.8.1057 (2016-07-21)</h2>
<ul>
    <li>Fixed Spring Boot Java agents issue</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.20.7.1051">Version 1.20.7.1051 (2016-07-20)</h2>
<ul>
    <li>Fixed Command-line Client upgrade issue</li>
</ul>

<h2 id="1.20.6.1050">Version 1.20.6.1050 (2016-07-20)</h2>
<ul>
    <li>Fixed environment variable issue for run and AWS environments</li>
</ul>

<h2 id="1.20.5.1049">Version 1.20.5.1049 (2016-07-19)</h2>
<ul>
    <li>Added VirtualBox 5.1 support</li>
    <li>Added machine-readable output with -m</li>
    <li>Fixed overriding of Spring Boot http or https port during run</li>
    <li>Fixed exposing environment variables with spaces as system properties for JVM apps</li>
    <li>Fixed empty subnets error when using Gradle plugin</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.20.4.1035">Version 1.20.4.1035 (2016-07-11)</h2>
<ul>
    <li>Fixed issue with longer instance IDs not being recognized</li>
</ul>

<h2 id="1.20.3.1034">Version 1.20.3.1034 (2016-07-10)</h2>
<ul>
    <li>Environment Variables can now contain special characters</li>
    <li>Added support for also automatically loading environment-specific config files in addition to the general
        ones
    </li>
</ul>

<h2 id="1.20.2.1032">Version 1.20.2.1032 (2016-07-08)</h2>
<ul>
    <li>Environment Variables can now be fused into an image and optionally overridden when launching an instance
    </li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.20.1.1028">Version 1.20.1.1028 (2016-07-07)</h2>
<ul>
    <li>Added live reloading support in dev for Linux</li>
    <li>Faster live reloading for Windows and Mac OSX</li>
    <li>Added support for loading Spring Boot config from the config package in addition to the classpath root</li>
    <li>More robust parsing of Play configs</li>
    <li>Added AWS ap-south-1 (Mumbai) region support</li>
    <li>Node.js engine version, app name and app version can now also be autodetected directly from package.json
    </li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.20.0.1018">Version 1.20.0.1018 (2016-06-30)</h2>
<ul>
    <li>Added live reloading support in dev for Windows and Mac OSX</li>
    <li>Restored compatibility with VirtualBox 4.2</li>
</ul>

<h2 id="1.19.12.1000">Version 1.19.12.1000 (2016-06-19)</h2>
<ul>
    <li>More fixes for Turkish locale</li>
</ul>

<h2 id="1.19.11.999">Version 1.19.11.999 (2016-06-18)</h2>
<ul>
    <li>Fixed image generation on computers with a Turkish locale</li>
</ul>

<h2>Version 1.19.10.998 (2016-06-17)</h2>
<ul>
    <li>Fixed issue with subnets when mvn boxfuse:run</li>
</ul>

<h2>Version 1.19.9.992 (2016-06-16)</h2>
<ul>
    <li>boxfuse.image is now defined as a property after invoking convert from Maven or Gradle</li>
    <li>Fixed issue with cacerts when using the Oracle JRE</li>
</ul>

<h2>Version 1.19.8.990 (2016-06-10)</h2>
<ul>
    <li>Apps can now be reconfigured directly as part of the run command</li>
</ul>

<h2>Version 1.19.7.987 (2016-06-08)</h2>
<ul>
    <li>Capacity can now be set directly as part of the run command</li>
</ul>

<h2>Version 1.19.6.981 (2016-06-02)</h2>
<ul>
    <li>Support for custom JREs (like the Oracle JRE) to replace the default OpenJDK one</li>
</ul>

<h2>Version 1.19.5.972 (2016-05-28)</h2>
<ul>
    <li>VirtualBox: Wait for Dev VM to boot database before starting app instances</li>
    <li>Added sysctl.conf support for tuning kernel parameters</li>
</ul>

<h2>Version 1.19.4.967 (2016-05-23)</h2>
<ul>
    <li>Added support for Node.js LTS releases (0.10, 0.12, 4)</li>
</ul>

<h2>Version 1.19.3.966 (2016-05-18)</h2>
<ul>
    <li>Fixed hang introduced in 1.19.2 when fusing using the CLI</li>
</ul>

<h2>Version 1.19.2.965 (2016-05-17)</h2>
<ul>
    <li>Ports can now be overridden when invoking run on an existing image</li>
    <li>Improved NewRelic config file parsing</li>
    <li>Major performance improvement for fusing images</li>
</ul>

<h2>Version 1.19.1.952 (2016-05-14)</h2>
<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.19.0.951 (2016-05-13)</h2>

<ul>
    <li>create and destroy are now idempotent</li>
    <li>Fixed healthcheck when explicitly setting healthcheck.port to http</li>
    <li>Fixed Java Agents support for Spring Boot 1.4</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.18.7.938 (2016-03-23)</h2>

<ul>
    <li>Added Node.js database support</li>
</ul>

<h2>Version 1.18.6.922 (2016-03-21)</h2>

<ul>
    <li>Added the ability to display important notifications about your account</li>
</ul>

<h2>Version 1.18.5.918 (2016-03-19)</h2>

<ul>
    <li>Added destroy command to destroy apps from the client</li>
</ul>

<h2>Version 1.18.4.917 (2016-03-16)</h2>

<ul>
    <li>Improved command-line argument validation</li>
    <li>Added easy JCE crypto policy override</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.18.3.914 (2016-03-15)</h2>

<ul>
    <li>Better ls output for Node.js apps</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.18.2.913 (2016-03-11)</h2>

<ul>
    <li>Fixed error when explicitly selecting TomEE 7.0.0-M3 components</li>
</ul>

<h2>Version 1.18.1.911 (2016-03-10)</h2>

<ul>
    <li>Added TomEE 7.0 support</li>
</ul>

<h2>Version 1.18.0.909 (2016-03-03)</h2>

<ul>
    <li>Added initial Node.js support</li>
</ul>

<h2>Version 1.17.8.903 (2016-02-29)</h2>

<ul>
    <li>Fixed rare cases where the Dev VM fails to start due to read-only file system permissions</li>
    <li>Fixed CPU count detection on broken OSes</li>
    <li>Fixed VirtualBox 4.3 compatibility</li>
</ul>

<h2>Version 1.17.7.901 (2016-02-27)</h2>

<ul>
    <li>Added Spring Boot 1.4.0.M1 and newer compatibility</li>
    <li>Fixed info for certain applications with no database</li>
</ul>

<h2>Version 1.17.6.900 (2016-02-23)</h2>

<ul>
    <li>Added Play KeyStore auto-configuration</li>
    <li>Minor bug fixes and sanity checks</li>
</ul>

<h2>Version 1.17.5.895 (2016-02-18)</h2>

<ul>
    <li>More robust handling of broken Dropwizard config files</li>
    <li>Minor bug fixes</li>
</ul>

<h2>Version 1.17.4.892 (2016-02-17)</h2>

<ul>
    <li>Added Slick datasource auto-configuration for Play 2.4+ payloads</li>
    <li>Added jvm.jmx property</li>
    <li>Allow -tmp= to set temp space size when running existing images</li>
</ul>

<h2>Version 1.17.3.884 (2016-02-16)</h2>

<ul>
    <li>Fixed PostgreSQL and MySQL detection for projects built with SBT</li>
    <li>Fixed passing of Play 2.3 database user</li>
</ul>

<h2>Version 1.17.2.882 (2016-02-15)</h2>

<ul>
    <li>Fixed error message when attempting to remove non-existent images</li>
    <li>Enabled info for apps that haven't got any images yet</li>
</ul>

<h2>Version 1.17.1.879 (2016-02-13)</h2>

<ul>
    <li>Fixed detection of Play 2.3 config files inside broken Play dist zips</li>
</ul>

<h2>Version 1.17.0.878 (2016-02-12)</h2>

<ul>
    <li>Added MySQL support</li>
    <li>Added DB type autodetection for plain executable jars</li>
    <li>Added open -db</li>
    <li>Added info</li>
</ul>

<h2>Version 1.16.4.863 (2016-02-04)</h2>

<ul>
    <li>Fixed detection of correct DB type for new apps create via the CloudCaptain Console</li>
    <li>Improved handling of broken zip files</li>
</ul>

<h2>Version 1.16.3.861 (2016-02-03)</h2>

<ul>
    <li>Added PostgreSQL driver autodetection for Tomcat and TomEE</li>
    <li>Better auto-selection of shaded artifacts</li>
</ul>

<h2>Version 1.16.2.857 (2016-02-02)</h2>

<ul>
    <li>Images now automatically perform a thread dump to stdout when an OutOfMemoryError occurs</li>
    <li>More robust handling of Broken VirtualBox installations</li>
</ul>

<h2>Version 1.16.1.852 (2016-01-30)</h2>

<ul>
    <li>More robust handling of corrupted Dev VMs</li>
    <li>Added New Relic for Play support</li>
</ul>

<h2>Version 1.16.0.850 (2016-01-28)</h2>

<ul>
    <li>Added Database management and PostgreSQL Dev VM support</li>
</ul>

<h2>Version 1.15.7.847 (2016-01-22)</h2>

<ul>
    <li>Fixed upload retries on TLS negotiation errors</li>
</ul>

<h2>Version 1.15.6 (2016-01-18)</h2>

<ul>
    <li>Better support for building images on CodeShip</li>
    <li>Added support for JavaAgents with files in subfolders</li>
</ul>

<h2>Version 1.15.5 (2016-01-06)</h2>

<ul>
    <li>More robust retry logic for resumable uploads</li>
</ul>

<h2>Version 1.15.4 (2015-12-31)</h2>

<ul>
    <li>Fixed an issue with pulling image uploaded with the new resumable upload</li>
</ul>

<h2>Version 1.15.3 (2015-12-30)</h2>

<ul>
    <li>logs.tail now also works with boxfuse run (VirtualBox only)</li>
    <li>Fixed bringing up instance-specific logs inside a project directory</li>
</ul>

<h2>Version 1.15.2 (2015-12-28)</h2>

<ul>
    <li>Uploads to the Vault are now resumable and more robust on slow/flaky networks</li>
</ul>

<h2>Version 1.15.1 (2015-12-27)</h2>

<ul>
    <li>Support Play http/https port and payload/healthcheck path configuration via application.conf</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.15.0 (2015-12-22)</h2>

<ul>
    <li>Added Grails support</li>
    <li>Added Spring Boot application.yml config support</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.14.1 (2015-12-10)</h2>

<ul>
    <li>Give all instances 1 GB of temp space by default</li>
    <li>Spring Boot config detection now automatically also falls back to application-default.properties and
        application.properties
    </li>
    <li>Automatically configure TomEE ActiveMQ to use /tmp for temp space</li>
    <li>Automatically configure the Spring Boot Actuator disk space health check to monitor /tmp</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.14.0 (2015-12-09)</h2>

<ul>
    <li>Added support for temp storage mounted under /tmp</li>
    <li>Auto-correct scaling alarm duration that is not a multiple of 60 to the nearest allowed value</li>
</ul>

<h2>Version 1.13.7 (2015-12-08)</h2>

<ul>
    <li>Fixed a bug with the command-line client update on Mac OSX and Linux</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.13.6 (2015-11-27)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.13.5 (2015-11-25)</h2>

<ul>
    <li>Added auto-scaling based on network I/O</li>
</ul>

<h2>Version 1.13.4 (2015-11-17)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.13.3 (2015-11-13)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.13.2 (2015-11-12)</h2>

<ul>
    <li>Ignore javadoc and source jars in payload autodetection</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.13.1 (2015-11-11)</h2>

<ul>
    <li>Autodetect payloads in Maven, Gradle & Play project structures</li>
    <li>CloudCaptain is now smarter about not regenerating identical images</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.13.0 (2015-11-09)</h2>

<ul>
    <li>Added support for Play 2.3 and newer</li>
    <li>CloudCaptain will now by default try to map VirtualBox instance ports to the same local ports if available</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.12.2 (2015-10-25)</h2>

<ul>
    <li>Added support for auto-scaling</li>
</ul>

<h2>Version 1.12.1 (2015-10-20)</h2>

<ul>
    <li>Fixed JRE detection on Windows</li>
</ul>

<h2>Version 1.12.0 (2015-10-19)</h2>

<ul>
    <li>Allow Spring Boot http and https configuration to be set via -ports.http and -ports.https</li>
    <li>The BOXFUSE_INSTANCE_IP is now always correctly set to the externally reachable IP address of the instance
    </li>
    <li>Added support for udp ports</li>
    <li>Added support for restricted ports</li>
</ul>

<h2>Version 1.11.8 (2015-10-15)</h2>

<ul>
    <li>Fixed Java Agents path for Spring Boot, Dropwizard and Executable Jar payloads</li>
    <li>Also extract non-.jar files from /javaagents directory for Spring Boot, Dropwizard and Executable Jar
        payloads
    </li>
    <li>Always export CloudCaptain environment variables before user-defined ones</li>
</ul>

<h2>Version 1.11.7 (2015-10-14)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.11.6 (2015-10-13)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.11.5 (2015-10-07)</h2>

<ul>
    <li>Support for NTLM proxy authentication</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.11.4 (2015-10-05)</h2>

<ul>
    <li>Added support for using the client behind a network proxy</li>
</ul>

<h2>Version 1.11.3 (2015-10-03)</h2>

<ul>
    <li>App names may now contain single dashes</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.11.2 (2015-09-30)</h2>

<ul>
    <li>Gradle Plugin is now published in the <a href="https://plugins.gradle.org/plugin/com.boxfuse.client">Gradle
        Plugin portal</a></li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.11.1 (2015-09-30)</h2>

<ul>
    <li>Increased healthcheck connection read timeout to 10 seconds</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.11.0 (2015-09-28)</h2>

<ul>
    <li>Added TomEE support</li>
</ul>

<h2>Version 1.10.2 (2015-09-19)</h2>

<ul>
    <li>Output current CloudCaptain configuration in debug output</li>
</ul>

<h2>Version 1.10.1 (2015-09-16)</h2>

<ul>
    <li>Improved robustness for flaky health checks</li>
</ul>

<h2>Version 1.10.0 (2015-09-07)</h2>

<ul>
    <li>Added cfg command to (re)configure environments</li>
</ul>

<h2>Version 1.9.7 (2015-09-03)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.9.6 (2015-08-28)</h2>

<ul>
    <li>Gradle plugin: Properties can now be set directly on a task</li>
    <li>Do not fail when the MAC address could not be detected</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.9.5 (2015-08-27)</h2>

<ul>
    <li>Fixed port in use detection for Mac OSX</li>
</ul>

<h2>Version 1.9.4 (2015-08-22)</h2>

<ul>
    <li>Workaround for VirtualBox defect leading to rare VM start failures on Windows hosts</li>
    <li>Changed default boxfuse.yml Dropwizard config to only log at WARN level and higher</li>
    <li>Redesigned inventory display</li>
</ul>

<h2>Version 1.9.3 (2015-08-18)</h2>

<ul>
    <li>Added support for 4.x Linux kernels</li>
    <li>Improved VirtualBox performance for images using Linux kernel 4.x</li>
    <li>Improved EC2 performance for all images</li>
</ul>

<h2>Version 1.9.2 (2015-08-16)</h2>

<ul>
    <li>Fixed Spring Boot default port when application-boxfuse.properties exists</li>
    <li>Force Spring Boot disk space health check to be disabled</li>
    <li>Fixed overriding Dropwizard port definitions with boxfuse.ports</li>
</ul>

<h2>Version 1.9.1 (2015-08-15)</h2>

<ul>
    <li>Setting a property to an empty value will now unset the property</li>
    <li>Fixed <a href="https://github.com/boxfuse/boxfuse-issues/issues/35">Issue 35</a>: Can't display all images
        for a given app (Gradle plugin)
    </li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.9.0 (2015-08-14)</h2>

<ul>
    <li>Added convert command for separate image to AMI conversion</li>
</ul>

<h2>Version 1.8.10 (2015-08-12)</h2>

<ul>
    <li>Added support for Spring Boot management.port config property</li>
    <li>Fixed ps for the test environment</li>
</ul>

<h2>Version 1.8.9 (2015-07-29)</h2>

<ul>
    <li>Fixed <a href="https://github.com/boxfuse/boxfuse-issues/issues/31">Issue 31</a>: boxfuse.app setting
        appears to be ignored (Gradle plugin)
    </li>
    <li>Fixed <a href="https://github.com/boxfuse/boxfuse-issues/issues/33">Issue 33</a>: boxfuseLs Gradle task
        doesn't work
    </li>
</ul>

<h2>Version 1.8.8 (2015-07-28)</h2>

<ul>
    <li>Auto-extract keystore files (.jks and .keystore) from Spring Boot jars</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.8.7 (2015-07-27)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.8.6 (2015-07-25)</h2>

<ul>
    <li>Auto-extract keystore files (.jks and .keystore) from Dropwizard jars</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.8.5 (2015-07-24)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.8.4 (2015-07-20)</h2>

<ul>
    <li>Added support for payload.port & payload.path</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.8.3 (2015-07-19)</h2>

<ul>
    <li>Added support for custom Spring Boot context, servlet and admin paths</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.8.2 (2015-07-17)</h2>

<ul>
    <li>Expose environment name as BOXFUSE_ENV environment variable within instance</li>
    <li>Bug fixes</li>
</ul>

<h2 id="1.8.1">Version 1.8.1 (2015-07-14)</h2>

<ul>
    <li>Now compatible with VirtualBox 5 on all platforms</li>
</ul>

<h2>Version 1.8.0 (2015-07-05)</h2>

<ul>
    <li>Added scale command</li>
    <li>Much faster startup for large WAR-based payloads</li>
    <li>Also allow to enable debug & debug.wait with run, instead of only with fuse</li>
</ul>

<h2>Version 1.7.1 (2015-06-17)</h2>

<ul>
    <li>Fixed JRE font handling</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.7.0 (2015-06-10)</h2>

<ul>
    <li>Added new create command to clients</li>
    <li>Create new apps automatically from client on push</li>
</ul>

<h2>Version 1.6.2 (2015-06-05)</h2>

<ul>
    <li>Commandline: Cygwin support</li>
    <li>Maven plugin: Fixed loading credentials from settings.xml</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.6.1 (2015-05-25)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.6.0 (2015-05-19)</h2>

<ul>
    <li>Spring Boot support</li>
    <li>Added Gradle plugin</li>
    <li>Added OS-specific distributions containing a JRE</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.5.2 (2015-05-09)</h2>

<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.5.1 (2015-05-07)</h2>

<ul>
    <li>Improved support for systems without VirtualBox installed</li>
    <li>Progress bars &amp; spinners are now automatically disabled on CI servers</li>
</ul>

<h2>Version 1.5.0 (2015-05-07)</h2>

<ul>
    <li>Added support for test environment on AWS</li>
    <li>Credentials can now also be passed in via the BOXFUSE_USER and BOXFUSE_SECRET environment variables</li>
</ul>

<h2>Version 1.4.0 (2015-05-03)</h2>

<ul>
    <li>Added automatic instance logs on startup</li>
    <li>Added property logs.auto to disable automatic instance logs on startup</li>
    <li>Allow jvm.args, jvm.main.class and jvm.main.args to be passed in at instance launch</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.3.3 (2015-04-30)</h2>
<ul>
    <li>Fall back to new generated version in case of conflict during fuse</li>
</ul>

<h2>Version 1.3.2 (2015-04-24)</h2>
<ul>
    <li>Fixed out of memory error for large payloads</li>
</ul>

<h2>Version 1.3.1 (2015-04-23)</h2>
<ul>
    <li>Increased maximum payload size to 300 MB</li>
</ul>

<h2>Version 1.3.0 (2015-04-22)</h2>
<ul>
    <li>Added Dropwizard support</li>
    <li>Added healthcheck.port setting</li>
    <li>Increased default healthcheck timeout to 300 seconds</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.2.0 (2015-03-24)</h2>
<ul>
    <li>Environment variables are now automatically also exposed as JVM system properties</li>
    <li>Renamed env.NAME -> envvars.NAME</li>
    <li>Fixed http -> https redirection for Tomcat on VirtualBox</li>
    <li>Fixed Maven plugin usage without payload</li>
</ul>

<h2>Version 1.1.0 (2015-03-23)</h2>
<ul>
    <li>Added kill, logs and open for AWS Instances</li>
    <li>Added rm for CloudCaptain Vault Images</li>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.0.3 (2015-03-07)</h2>
<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.0.2 (2015-02-27)</h2>
<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.0.1 (2015-02-24)</h2>
<ul>
    <li>Bug fixes</li>
</ul>

<h2>Version 1.0.0 (2015-02-24)</h2>
<ul>
    <li>Initial public release</li>
</ul>

<!--p class="next-steps">
    <a class="btn btn-primary" href="/docs/faq">FAQ <i class="fa fa-arrow-right"></i></a>
</p-->
