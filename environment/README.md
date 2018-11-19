researches                 | version | updated at  | links
---------------------------|---------|-------------|------
META                       | 0.0.2   | 13/11/2018  | [Link](https://github.com/faelplg/web-development-researches)
**Software Deployment**    | 0.0.1   | 19/11/2018  | --

# Software Deployment

Software deployment is a set of procedures which allows an application to be available for management, testing, and use. Its complexity will **depend directly on the design requirements and system architecture**. Despite this, there is a certain convention that is interesting to be understood.

This convention divides software deployment into three environments or structures:

> An environment or tier is a computer system in which a computer program or software component is deployed and executed. In simple cases, such as developing and immediately executing a program on the same machine, there may be a single environment, but in industrial use the development environment (where changes are originally made) and production environment (what end users use) are separated; often with several stages in between.
[[1]](#wikipedia)

1. **Development:**  It is the environment where the developer implements and tests the application code. Typically, the tests here are related to code syntax, styles, libraries compatibility and project requirements. Once the application is implemented and tested, the project is moved to staging phase, where it will be tested with the production environment requirements.

2. **Staging:** This environment is made to look exactly like the production server environment. The application is tested on the staging server to check for reliability and to make sure it does not fail on the actual production server. This type of testing on the staging server is the final step before the application could be deployed on a production server. The application needs to be approved in order to deploy it on the production server. [[2]](#techopedia)

3. **Production:** It is the environment where your services and store are made available to your customers. [[3]](#techopedia) Once the approval is done, the application then becomes a part of this server [[2]](#techopedia).

## Development

The development environment is the set of tools and structures where the developers implement and test the application. This environment should be as most organized as possible to allow a team of developers to work in a integrated and efficient way.

> A development environment is a collection of procedures and tools for developing, testing and debugging an application or program. In software development, the development environment is a set of processes and tools that are used to develop a source code or program. [[2]](#techopedia)

### Related:
* [IDE - Integrated Development Environment](https://en.wikipedia.org/wiki/Integrated_development_environment)

## Staging & Production environment

The staging environment (or server) is used to test an application once its development is done. This server helps you verify systems' behavior and performance in the same way it will be delivered to the user in a production environment.

Production environment is a term used mostly by developers to describe the structure where the application will be delivered to the final users. At this moment, the application needs to be reliable and optimized because its goal is to deliver performance and lightweight navigation for the user through the production environment. Optimization aspects include, for example, file minification, image compression, code splitting, etc.

> One way to define a production environment is by contrasting it with a testing environment. In a testing environment, a product is still being used theoretically. Users, typically engineers, look for bugs or design flaws. In the production environment, the product has been delivered and needs to work flawlessly. [[3]](#techopedia)

## Sources

#### Wikipedia
[**[1]** Deployment environment](https://en.wikipedia.org/wiki/Deployment_environment)

#### Techopedia
[**[2]** Development environment](https://www.techopedia.com/definition/16376/development-environment)

[**[3]** Production environment](https://www.techopedia.com/definition/8989/production-environment)

[**[4]** Staging server](https://www.techopedia.com/definition/8989/production-environment)
