# Spring Cloud Contracts

You always need confidence when pushing new features into a new application or service in a distributed system. To that end, this project provides support for Consumer-driven Contracts and service schemas in Spring applications, covering a range of options for writing tests, publishing them as assets, and asserting that a contract is kept by producers and consumers — for both HTTP and message-based interactions.

The usage of this project combine a set of Dependencies in your project and a set of organizational operations between the Consumer and the Producers.

## Specificacion

In the phase, the Consumer, use contracts from the different producers to improve the Integratoin tests

![](1.jpg)

### Context:

Spring Cloud Contracts help any Spring Development with the usage of Contract Driven Development. This solution could be used in 2 different ways: 

- Producer approach: The API/Event System provides a set of Expections (Stable set of behaviour of the artifacts) stored.
- Consumer approach: The consumer uses contracts from producers in the Integration Tests and stablish a set of organizational mechanism to maintain the contracts. Using this approach, any Consumer can deliver with more confident because it doesn't need to wait in any 

![](2.jpg)

![](3.jpg)

![](4.jpg)

## References

- https://www.martinfowler.com/articles/consumerDrivenContracts.html
- https://github.com/spring-cloud/spring-cloud-contract
- https://github.com/spring-cloud-samples/spring-cloud-contract-samples
- https://cloud.spring.io/spring-cloud-static/Greenwich.RELEASE/single/spring-cloud.html#_spring_cloud_contract

