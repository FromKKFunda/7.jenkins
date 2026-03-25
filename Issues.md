
Error: Could not transfer metadata com.kk:maven-web-application-kkfunda:0.0.1-SNAPSHOT/maven-metadata.xml from/to nexus (http://3.110.160.202:8081/repository/snapshot_free/): status code: 401, reason phrase: Unauthorized (401)
While triggering the pipeline, if we get this error, then?

Solution:
=========

Got Jenkins Default directory: cd /var/lib/jenkins/

tools >>> husdson folder >>>>> maven 3.x.x > conf >>> settings.xml                                                find / -name settings.xml
   <server>
      <id>nexus</id>
      <username>admin</username>
      <password>Mani52@1</password>
    </server>
