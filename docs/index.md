## **Innovation Insight for Microservices**

According to Gartner, “Microservices enable unprecedented agility and scalability, but the architecture causes significant cultural disruption. Application leaders should understand this new design paradigm, its prerequisites and its disruptive impact before determining where and when to use it — if at all.”

**MSA supports CD practice.**

A microservice is a tightly scoped, strongly encapsulated, loosely coupled, independently deployable and independently scalable application component. Microservices architecture (MSA) applies service-oriented architecture (SOA) and domain-driven design (DDD) principles to deliver distributed applications. MSA is an architectural paradigm and implementation model for building services and cloud-native applications, and it has three core objectives: development agility, deployment flexibility and precise scalability. “The essential goal of MSA is to enable development teams to independently build, test, package, deploy and scale individual components within an application.” For instance, most organizations that adopt microservices is to support their CD practice. They typically deploy multiple updates to production systems every day to meet rapidly evolving business requirements and demands. If something goes wrong, how do we determine what caused the failure? MSA enables organizations to deliver new features as independent components, which reduces CD risks because CD of features within a monolithic code base is risky.

**Three different levels of service granularity are Microservice, Miniservice and Macroservice. Applying MSA is mostly complex, and in fact many organizations are doing MSA as a combination of miniservices and macroservices. This approach way could be wrong and getting disappointing results. Basing the benefits of MSA, Microservices should be used for just the features of the application that require extreme agility and scalability.**

This is a useful summary from Gartner for the benefits of MSA:
- **Agility** — MSA facilitates a CD practice, enabling an organization to deploy new application features as quickly as they can be developed.
- **Risk reduction** — Because MSA deployments are small and independent, the risk associated with each deployment is reduced.
- **Distributed development** — MSA reduces dependencies between components, which enables feature teams to work more autonomously.
- **Technology flexibility** — Because microservices are loosely coupled, development teams can use a variety of technologies and languages to implement the different facets of an application.
- **Scalability** — MSA provides the means to scale just the parts of an application that cause contention and bottlenecks.
- **Resiliency** — MSA design patterns, when applied correctly, yield self-healing applications that can continue operating in the face of partial outages, and that can recover rapidly and gracefully.


