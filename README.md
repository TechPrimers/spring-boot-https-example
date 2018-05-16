# Spring Boot with HTTPS

# Command to create self signed SSL Certificate JKS
`keytool -genkey -alias https-example -storetype JKS -keyalg RSA -keysize 2048 -validity 365 -keystore https-example.jks`

# Secured access
`https://localhost:8443/hello` - returns 'Hello YouTube'