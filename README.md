# Hello-and-Hello-From-Remote

- Two dockerized Spring Boot applications: Service_A (port 8000) and Service_B (port 8080).<br/>
- With same libraries and dependencies.<br/>
- Communicate with each other through http calls.<br/>
- Service_A and Service_B are running in two separate containers.<br/>
- Each service has two methods: hello and hello_from_remote.<br/>
- Each hello_from_remote method sends a http call to other service's hello method.
