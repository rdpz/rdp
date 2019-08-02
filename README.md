# rdp


Software Installation Needed
* Jhipster 
* Mongo
* Docker

Code Generator for Jhipster
*npm install -g generator-jhipster


Projects : 
 app-serviceone : has the docker compose for the jhipster registry and also a microservice
 Command :        docker-compose -f app-serviceone/src/main/docker/jhipster-registry.yml  up

jhipster-registry_1  | ----------------------------------------------------
jhipster-registry_1  | 	Application 'jhipster-registry' is running! Access URLs:
jhipster-registry_1  | 	Local: 		http://localhost:8761
jhipster-registry_1  | 	External: 	http://172.20.0.2:8761
jhipster-registry_1  | 	Profile(s): 	[composite, dev, swagger, uaa]
jhipster-registry_1  | ----------------------------------------------------
