# Tyrus-P2

This POM will build the tyrus-standalone-client bundle from maven into a P2 update site.

Build using `mvn clean verify` and then expose the produced `target/repository/` directory over HTTP(s) using your favourite web server.
