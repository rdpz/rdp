# rdp


Software Installation Needed
* Jhipster 
* Mongo ( running on 27017)
* Docker

Code Generator for Jhipster
*npm install -g generator-jhipster


Projects : 
 app-serviceone : has the docker compose for the jhipster registry and also a microservice
 Command :        docker-compose -f app-serviceone/src/main/docker/jhipster-registry.yml  up
<pre>
 ----------------------------------------------------
 	Application 'jhipster-registry' is running! Access URLs:
 	Local: 		http://localhost:8761
 	External: 	http://172.20.0.2:8761
 	Profile(s): 	[composite, dev, swagger, uaa]
 ----------------------------------------------------

this is the single rest service which is available for now
 ----------------------------------------------------------
	Application 'appServiceOne' is running! Access URLs:
	Local: 		http://localhost:8081/
	External: 	http://127.0.1.1:8081/
	Profile(s): 	[dev, swagger]
----------------------------------------------------------

</pre>

app-uaa : authentication service 
./mvnw
<pre>
----------------------------------------------------------
	Application 'uaa' is running! Access URLs:
	Local: 		http://localhost:9999/
	External: 	http://127.0.1.1:9999/
	Profile(s): 	[dev, swagger]
----------------------------------------------------------
</pre>

app-gateway:     the gateway 
<pre>
---------------------------------------------
	Application 'rdpGateway' is running! Access URLs:
	Local: 		http://localhost:8080/
	External: 	http://127.0.1.1:8080/
	Profile(s): 	[dev, swagger]
---------------------------------------------
</pre>

