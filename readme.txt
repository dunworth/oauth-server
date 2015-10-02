Create keystore with this command:
keytool -genkeypair -keystore keystore.jks   -dname "CN=localhost, OU=Unknown, O=Unknown, L=Unknown, ST=Unknown, C=Unknown"  -keypass password  -storepass password  -keyalg DSA  -sigalg SHA1withDSA  -keysize 1024  -alias mule  -ext SAN=DNS:localhost,IP:127.0.0.1 -validity 9999


