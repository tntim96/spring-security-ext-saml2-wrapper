# spring-security-ext-saml2-wrapper

Create shaded JAR
```
mvn package
```

View dependency tree
```
mvn dependency:tree
```

View unknown JAR contents
```
jar tf target/spring-security-saml2-core-shaded-1.0.3.0.jar | grep -wv shaded | grep -wv "org/springframework/security/saml.*" | grep -wv "org/apache/velocity.*" | grep -wv "org/pwasp/esapi" | grep -wv ".*.xsd$" | less
```