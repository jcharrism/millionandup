# millionandup
PRUEBA TECNICA | INGENIERO DEVOPS

TEST DEVOPS IT

You have been working for a robotics company, which has developed new
software with artificial intelligence. You can use the following tools to deploy
new software:
- Azure DevOps
- Azure Cloud Services
- K8s
- Kafka
- Nginx
- LinkerD
- Prometheus
- Cloudflare
- Loki
- Grafana
About software, the software is developed with EDA architecture and uses
microservices with Python, .Net, and NodeJs, the team works with SCRUM and
uses the repository git. The database uses different engines SQL Server,
MongoDB, and Cassandra.

Exercises:
1. Create a file yaml and DockerFile to create a new pod in K8s for a
microservice in Python. (remember: the microservice cannot use more than 3
GB of memory, this must be in namespace: tech.prod and use a network
“internal prod”)
2. Create file pipeline yaml for Azure DevOps this will have to do: build,
validate the unit test, and create an artifact.
3. The application has a performance problem, the developer team found
the problem with image size, you must create a CloudFlare Worker for resizing
and caching images.
4. With the tool as previously mentioned before create a diagram to
improve observability.
Deliverables:
Create a repository to github with yaml file and diagram further do not forget in
readme file put on the variables or specific configuration
