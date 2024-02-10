# Micro frontends (MFE) 

Micro frontends are an architectural approach to building web applications as a collection of loosely coupled, independently deployable frontend components. There are various types of micro frontends based on how they are implemented and integrated:

1. **Composition-based micro frontends**: In this approach, each micro frontend is responsible for a specific feature or functionality of the application. These micro frontends are composed together to form the complete user interface. Integration may be achieved through server-side composition or client-side composition using techniques like iframes or web components.

2. **Integration-based micro frontends**: Here, micro frontends can be built using different frontend frameworks or technologies (e.g., React, Angular, Vue.js). Integration is typically done using a common set of APIs or protocols, such as Web Components, Custom Events, or a state management system like Redux.

3. **Shell-based micro frontends**: In this approach, a shell or container application provides the infrastructure and navigation for the micro frontends. Each micro frontend is a standalone application that is responsible for its own routing and state management. The shell loads and integrates these micro frontends dynamically at runtime.

4. **Domain-based micro frontends**: Micro frontends are organized around specific business domains or capabilities within the application. Each domain or capability is developed and deployed independently as a micro frontend. This approach helps in aligning development teams with business domains, promoting autonomy and scalability.

5. **Build-time micro frontends**: In this approach, micro frontends are built separately and then integrated at build time. This can be achieved using build tools and techniques like Module Federation in webpack or dynamic imports.

6. **Runtime micro frontends**: Here, micro frontends are loaded and integrated dynamically at runtime. This approach allows for more flexibility and agility, as micro frontends can be updated and deployed independently without requiring a full application rebuild.

These types are not mutually exclusive, and different combinations of approaches may be used based on the specific requirements and constraints of the project.