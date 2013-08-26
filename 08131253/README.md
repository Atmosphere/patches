To install this patch:

add in web.xml:
```xml
<init-param>
    <param-name>org.primefaces.push.rules</param-name>
    <param-value>org.atmosphere.patches.patch08131253.FixedBroadcasterCachePushRule</param-value>
</init-param>
```
In pom.xml, add:
```xml
  <dependency>
      <groupId>org.atmosphere.patches</groupId>
      <artifactId>atmosphere-08131253</artifactId>
      <name>atmosphere-08131253</name>
      <version>1.0.0-SNAPSHOT</version>
  </dependecy>
```


