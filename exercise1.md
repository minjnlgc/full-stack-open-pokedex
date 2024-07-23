### Exercise 11.1
For a Java project:
Linting: Can use CheckStyle, a static code analysis tool. I heard that it has plugin for different IDEs.

Testing: Testing in Java can use JUnit (for unit testing), Mockito (mocking object during tests), TestNG (integration and end-to-end testing). JUnit focuses on testing individual units of code, Mokito specialises in managing dependencies and mocking external interactions. Integrating both could create more robust, efficient, and comprehensive tests that cover different scenarios.

Building: Building process in Java is often managed by Maven or Gradle. Maven uses XML configuration to manage project builds and dependencies, while Gradle uses a Groovy-based DSL for more flexibility. (I don't like XML, but they said Maven is easier so I don't know, let the team vote; I guess if it is a small project just choose the easy one?)

The alternative to Jekins and Github Actions: The alternatvive include GitLab CI, which offers robust CI/CD capabilities integrated with GitLab repositories. 

Self-hosted vs. Cloud-based: Depends on several factors. A cloud-based CI environment offers scalability, maintenance-free infrastructure, and easy setup. In contrast, a self-hosted environment provides more control over the infrastructure and can be preferable for projects with stringent security requirements or specialised configurations. I think for a team with 6 just cloud-based?
