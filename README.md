# How to set up Jenkins on localhost with war

* Download the WAR from Jenkins site:
	https://jenkins.io/doc/book/installing/#war-file

* Start Jenkins: 

`
java -jar jenkins.war --enable-future-java
`

If everything goes well, below message should be seen in the logs:

`
INFO: Jenkins is fully up and running
`

By default, jenkins starts up on 8080 port. It can be reached by using the URL: http://localhost:8080

## License

MIT © Mandeep "Manny" Sah 