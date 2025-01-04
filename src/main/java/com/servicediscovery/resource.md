https://medium.com/@ksaquib/mastering-spring-boot-service-discovery-and-registration-using-spring-cloud-netflix-eureka-a-1eec70317b32https://medium.com/@ksaquib/mastering-spring-boot-service-discovery-and-registration-using-spring-cloud-netflix-eureka-a-1eec70317b32https://medium.com/@ksaquib/mastering-spring-boot-service-discovery-and-registration-using-spring-cloud-netflix-eureka-a-1eec70317b32


https://spring.io/projects/spring-cloud

> Introduction to Service Discovery & Registration in Microservices
> *  Service Registry: A database of available service instances.
> * Service Discovery: The process of finding services.
> * Service Registration: The process of registering services to the registry.


Why Traditional Load Balancers are Not Ideal for Microservices:
1. Static Nature of Traditional Load Balancers
2. Manual Updates and Operational Overhead
3. Inefficient Routing and Scalability Issues
4. Lack of Health Checks and Self-Healing
5. Dynamic Service Discovery and Load Balancing
> Dynamic load balancing solutions, such as those provided by Spring Cloud, leverage this service registry to route requests efficiently. They automatically update their configuration based on the current state of the service registry, ensuring that traffic is always routed to healthy and available instances.\
For example, Spring Cloud Netflix Eureka is a popular service discovery and registration tool that provides <mark>dynamic load balancing</mark>. 