## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
Using software components known as services to build business applications is known as service-oriented architecture, or SOA. Every service offers a certain business function, and they can converse with one another in multiple languages and platforms.
2. List and discuss the characteristics of SOA.
Standardized Service Contract: Services adhere to a service-description. A service needs to have some information that defines what the service is about.
Loose Coupling: Services minimize dependencies on each other. So if the service functionality breaks at several points in time, this should not crush the client application or stop it from running.
Service Abstraction: Services wrap the logic they encapsulate from the unknown external world. The service shouldn't show how it performs its functionality.
Service Reusability: Logic is divided into services to maximize re-use.
Service Autonomy: Services must control the logic they encapsulate.
Service Statelessness: Services should stay stateless. This determines that services should not keep data from one state to the other. This would be required to be done from each client application.
Service Discoverability: Services can be discovered (usually in a service registry). We have previously viewed this in the theory of the UDDI, which performs a registry which can contain information about the web service.
Service Composability: It breaks large problems into tiny problems.
Service Interoperability: Services should use standards that provide different supporters to use the service. This is examined so obviously these days that it is frequently dropped as a principle.
3. Define Microservices.
The microservice architecture enables an organization to deliver large, complex applications rapidly, frequently, reliably and sustainably - a necessity for competing and winning in today’s world.
4. List and discuss the benefits of using Microservices.
Improved Productivity- Breaking an application down into smaller autonomous fragments makes it easier to build and maintain. Each service can be developed, deployed, and managed independently, and can utilize different programming languages, different technology, and different software environments based on the needs of each. 
Better Resiliency - Implementing microservice-based architecture adds ease to the process of  identifying and resolving the root cause of performance issues. The improved fault isolation offered by individual modules means larger applications remain unaffected by a single failure.
Increase Scalability - The fact that each service can be written in a different language or technology allows DevOps teams to choose the most appropriate tech stack for each module without concerns about incompatibility. 

5. List and discuss the similarities and differences of SOA and Microservices.
SOA is not dynamic and cannot fit for different purposes. They must be adapted or redeveloped every time a critical architecture piece of the involved technology changes. On the contrary, microservices try to be more independent by building on standardized interfaces that are valid across different technologies. However, there are often different standards, which can in the end lead to the same challenge that SOA has.

SOA typically shares fundamental components across different services. On the contrary, microservices usually have everything they need within the service, duplicated in every single microservice. Microservices are hence a bit slower, but less dependent on underlying services in order to work.
