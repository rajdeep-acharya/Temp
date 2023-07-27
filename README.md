# Temp
 for temporary works & internet resouces


### The 12-Factor App 

<p align="center">
  <img src="The-12-factor-app-principles.jpg">
  <br/>
</p>

The 12-factor app methodology is a set of best practices for building modern software applications that are scalable, maintainable, and easily deployable. It was originally introduced by Heroku and has since become a widely adopted standard in the software development community. The 12 factors are as follows:

1. Codebase: A single codebase tracked in a version control system, with multiple deployments.
2. Dependencies: Explicitly declare and isolate dependencies. Use dependency management tools.
3. Config: Store configuration in the environment, separate from the code.
4. Backing services: Treat backing services (databases, caches, etc.) as attached resources that can be easily swapped.
5. Build, release, run: Strictly separate the build, release, and run stages of the application lifecycle.
6. Processes: Run the application as one or more stateless processes.
7. Port binding: Export services via port binding. Applications should be self-contained and not rely on runtime injection of a web server.
8. Concurrency: Scale out via the process model. Applications should be able to scale horizontally.
9. Disposability: Maximize robustness with fast startup and graceful shutdown. Processes should be able to start and stop quickly.
10. Dev/Prod parity: Keep development, staging, and production environments as similar as possible.
11. Logs: Treat logs as event streams and provide centralized logging. Application should not concern itself with routing or storage of its output stream.
12. Admin processes: Run admin/management tasks as one-off processes. They should be run in the same environment as the app, with access to the same config and code.

By following these principles, developers can create applications that are easier to develop, test, deploy, and scale, while also improving the overall reliability and maintainability of the software.