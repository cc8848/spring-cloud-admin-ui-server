# spring-cloud-admin-ui-server

* mvn clean package -Dmaven.test.skip docker:build
* docker run --name admin-server -d -p 10080:10080 spring-cloud/admin-ui-server
* docker logs -f admin-server
