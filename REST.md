# **REST**

    REST is stands for REpresentational State Transfer. It is an architectural style for distributed hypermedia systems and was given by Roy Fielding in 2000.

## **Architectural Constraints**

REST uses six architectural constraints which makes any web service a  RESTful system.
![REST ARCHITECTURAL](https://media-exp1.licdn.com/dms/image/C4D12AQHh6l0xkbhTPg/article-cover_image-shrink_720_1280/0/1622931040032?e=1634774400&v=beta&t=SCpnIdpTYRAi0a5Cy4GUl-yGZK9HGEuFesOfa-ZunTo "REST ARCHITECTURE")

##### Source: <https://www.linkedin.com/pulse/understanding-rest-architecture-gabriel-gitonga>

- ### **1 Uniform interface:**

        This constraint suggests that there should be a uniform way for the interaction of the server and the client, and this should be irrespective of the device or the type of application being used.
    Further, there are 4 guiding principles of Uniform Interface.

    1. Identification of Resources in the requests:** Individual resources are identified in the request. For example, using URIs in web services.
    2. Manipulation of resources through representations- any client holding a representation of a resource has enough information to delete or change the resource data.
    3. Self-descriptive messages: Every message includes information to describe how to process the message
    4. Hypermedia as the Engine of Application State(HATEOAS): it includes the links for each response so that clients can discover all the available resources that they can need.

- ### **2 Stateless:**  

        It is a communication protocol where no session information is retained by the server. Here relevant session data is transmitted by the client to the receiver in such a manner that every packet of information can only be understood in isolation, without having the previous packet’s information in the session. There is a drawback when the client needs to send a large amount of data to the server so it reduces the scope of network optimization and also requires more bandwidth for the process.

- ### **3 Cacheable:**

        For the improvement of the performance, the servers must mark their responses as cacheable or not. So that the infrastructures and the clients can cache them when possible.They can dispose of non-cacheable Information so that no client uses stale data.

- ### **4 Client-Server:**

        REST application uses a server that manages application data and state. The server communicates with the client and handles the user interactions. A clear separation of concerns divides the server with the client. This also means that anyone can update and improve them in independent tracks.

- ### **5 Layered System:**

        REST allows us to use a layered system architecture where we can deploy the APIs on the server and store data on server B and authenticate requests in server C. any layer does not know anything about the other layers other than immediate layers and also there can be a lot of intermediate servers between the client and the end server. Although intermediate servers may improve system availability by providing the shared caches and also by enabling load-balancing.

- ### **6 Code on demand:**

        This is an optional feature, where the server can also provide executable code to the client. For example, compiled components such as Java applets or the client-side scripts such as JavaScripts. 
