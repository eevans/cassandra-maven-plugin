cassandra-maven-plugin
======================

This is a fork of [Mojo's Cassandra Maven Plugin](http://mojo.codehaus.org/cassandra-maven-plugin/), a project which if not dead upstream, is at least releasing sporadically.

To install:

    ...
    <plugin>
      <groupId>org.codehaus.mojo</groupId>
      <artifactId>cassandra-maven-plugin</artifactId>
      <version>2.0.2-ONMS-20131028-1</version>
      ...
    </plugin>
    ...

    ...
    <pluginRepositories>
      <pluginRepository>
        <snapshots>
          <enabled>false</enabled>
        </snapshots>
        <releases>
          <enabled>true</enabled>
        </releases>
        <id>opennms-repo</id>
        <name>OpenNMS Repository</name>
        <url>http://maven.opennms.org/content/groups/opennms.org-release</url>
      </pluginRepository>
    </pluginRepositories>
    ...
