## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
Software developers can create new applications by reusing services and enabling them to connect across many platforms and languages through the use of service-oriented architecture (SOA). Self-contained software intended to do a particular task is called a service of application architecture (SOA). To create new apps, applications connect to services via SOA and easy interface standards.
2. List and discuss the characteristics of SOA.
-Standardized service contract - SOA was initially implemented using the SOAP protocol.  SOAP requires the use of a WSDL to utilize the service. REST simplifies this model in an easy-to-use implementation model. REST uses a request-response model to transmit data with a set of resources and verbs.
-Loose coupling - A primary benefit of SOA is the agility brought about by loose-coupling through services for the clients that interact with providers that support them. Instead of connecting a client app directly to a ticketing system, you put a service in between that disconnects the two systems breaking the dependency. 
-Abstraction - A service hides its underlying technology from the consumer. Abstraction allows the Enterprise to define technology in the context of a business process.  Abstraction breaks dependencies and introduces agility.   
-Reusability - Reusability creates a flywheel effect for innovation. Push teams to look for existing services before creating new ones. A critical component of driving reusability adoption is educating the consumers about what exists to date. 
-Autonomy - Users can then consume this service in a secure defined way in any compatible front end with no other needed dependencies. Utilizing the MuleSoft Exchange portal, users can register to consume a service. The portal helps to track the use of a service.
-Statelessness - A service deals with moments in time. It has no memory. If a client asks for data the service responds but does not keep track or store any data. If the context is needed for subsequent calls the onus is on the client to manage that context. You can cache data but that is a capability that the service can utilize as an option but will not depend on it.
-Discoverability - To support reuse, a service must be able to be found by a consumer. The system must educate the consumer on the proper mechanism to interact with the service and offer as much detail as possible to accelerate its use. 
-Composability- The building blocks of the Enterprise are the composable services it offers to its user community. And as we’ve heard, the future of business is composable.  Enable your organization to combine packaged business capabilities to define business processes. Service orchestration and choreography provide solid support for composing services and achieving business goals. 
3. Define Microservices.
Microservices are an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs. These services are owned by small, self-contained teams.
4. List and discuss the benefits of using Microservices.
Scalability improvements
Since each microservice runs independently, it is easier to add, remove, update or scale each cloud microservice. Developers can perform these tasks without disrupting any other microservice in the system. Companies can scale each microservice as needed. For instance, if a particular microservice experiences increased demand because of seasonal buying periods, more resources can be efficiently devoted to it.

Improved fault isolation
Under a monolithic architecture structure, when developers experience a failure in one element of the architecture, it will collapse all architecture components. With a microservices architecture, if one service fails, it’s much less likely that other parts of the application will fail because each microservice runs independently. However, businesses need to be careful, because large volumes of traffic can still be overwhelming in some cases.

Program language and technology agnostic
A microservice application can be programmed in any language, so dev teams can choose the best language for the job. The fact that microservices architectures are language agnostic also allows the developers to use their existing skill sets to maximum advantage – no need to learn a new programming language just get the work done. 

Simpler to deploy
A microservices architecture lets teams deploy independent applications without affecting other services in the architecture. This feature, one of the pros of microservices, will enable developers to add new modules without redesigning the system's complete structure.

Reusability across different areas of business
Some microservice applications may be shareable across a business. If a site has several different areas, each with a login or payment option, the same microservice application can be used in each instance

Faster time-to-market
Developers can plug this new “microsurgery” into the architecture without fear of conflicts with other code or of creating service outages that ripple across the website. Development teams working on different microservices don't have to wait for each other to finish.

Ability to experiment
It’s simple to roll out new features because each service is independent of the others. If customers don't like it, or the business benefits aren’t clear, it's much easier to roll it back without affecting the rest of the operation.

Improved data security
If the components of the computer systems architecture break down into smaller pieces, sensitive data is protected from intrusions from another area. While there are connections between all microservices, developers can use secure APIs to connect the services. Secure APIs safeguard data by ensuring it is only available to specifically authorized users, applications and servers. 

Outsourcing flexibility
It may be necessary for a business to outsource certain functions to third-party partners. Many companies are concerned about protecting intellectual property with a monolithic architecture format. 

Team optimization
Experts explain that this guideline improves work efficiency, allows businesses to achieve goals faster, makes teams easier to manage, creates greater focus among the group and results in higher quality products

Attractive for engineers
Engineers find microservices architecture enticing, and companies have a better chance of finding top-flight talent to work on microservices application development.

5. List and discuss the similarities and differences of SOA and Microservices.
Many of the chief characteristics of SOA and microservices are similar. Both involve a cloud or hybrid cloud environment for developing and running applications, are designed to combine multiple services necessary for creating and using applications, and each effectively breaks up large, complicated applications into smaller pieces that are more flexible to arrange and deploy. Because both microservices and SOA function in cloud settings, each can scale to meet the modern demands of big data size and speeds. OA is a modular means of breaking up monolithic applications into smaller components, while microservices provides a smaller, more fine-grained approach to accomplishing the same objective. Both of these architectures are routinely run in the cloud, which increases the flexibility for building and deploying applications. Ultimately, the best approach depends on each business’s own unique needs and use case. 
Many of the chief characteristics of SOA and microservices are similar. Both involve a cloud or hybrid cloud environment for developing and running applications, are designed to combine multiple services necessary for creating and using applications, and each effectively breaks up large, complicated applications into smaller pieces that are more flexible to arrange and deploy. Because both microservices and SOA function in cloud settings, each can scale to meet the modern demands of big data size and speeds. OA is a modular means of breaking up monolithic applications into smaller components, while microservices provides a smaller, more fine-grained approach to accomplishing the same objective. Both of these architectures are routinely run in the cloud, which increases the flexibility for building and deploying applications. Ultimately, the best approach depends on each business’s own unique needs and use case. 