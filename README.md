1. Databases
2. [ACID](https://www.geeksforgeeks.org/acid-properties-in-dbms/)</br>
3. Relational Database
4. [Normalization](https://www.geeksforgeeks.org/normal-forms-in-dbms/)</br>
5. Indexes - Why? How they work? What are the side effects?
  - Indexes are used to quickly locate data without having to search every row in a database table every time a database table is accessed. Indexes can be created using one or more columns of a database table, providing the basis for both rapid random lookups.</br>
  - Side effects:
    - Extra memory is needed for the indexing data structure
    - Lookup time for index table
    - Updates on the indexed table become slower because also the indexing structure need to be updated
  - Working:
    - The structure that is used to store a database index is called a B+ Tree. In a B+ Tree, the key values are separated into many smaller piles. As the name implies, the piles, technically called nodes, are connected in a tree-like fashion.
    - [Diff b/w B tree and B+ tree](https://www.softwaretestinghelp.com/b-tree-data-structure-cpp/#:~:text=The%20difference%20in%20B%2B%20tree,in%20a%20linked%20list%20fashion)</br>
    - In B+ trees, we have records only in leaf nodes and not in internal nodes
6. Transactions: A transaction can be defined as a group of tasks. A single task is the minimum processing unit which cannot be divided further.</br>
   A transaction in a database system must maintain Atomicity, Consistency, Isolation, and Durability − commonly known as ACID    properties.
7. APIs: APIs let your product or service communicate with other products and services without having to know how they’re implemented. This can simplify app development, saving time and money.
8. JWT tokens - Used for encoding and decoding
  - Variuos blocks like Header- Algo type, payload data and verify signature - your 256 bit secret
9. What is CORS?
  - Cross Origin resource sharing is bascically needed to load resources from other websites (origins)
  - Manages cross-origin requests
  - Cross-origin requests, however, mean that servers must implement ways to handle requests from origins outside of their own
  - CORS allows servers to specify who (i.e., which origins) can access the assets on the server, among many other things
  - The CORS standard is needed because it allows servers to specify not just who can access its assets, but also how the assets can be accessed
  - Cross-origin requests are made using the standard HTTP request methods. Most servers will allow GET requests, meaning they will allow resources from external origins (say, a web page) to read their assets
  - HTTP requests methods like PATCH, PUT, or DELETE, however, may be denied to prevent malicious behavior
10. Cookies:
   - Cookie is a small piece of data sent from a website and stored on the user's computer by the user's web browser while the user is browsing
   - Cookies were designed to be a reliable mechanism for websites to remember stateful information like browsing history, cart items etc
11. GET and POST:
  - Both GET and POST method is used to transfer data from client to server in HTTP protocol
  - Main difference between POST and GET method is that GET carries request parameter appended in URL string while POST carries request parameter in message body which makes it more secure way of transferring data from client to server in http protocol.
12. HTTP vs HTTPS
   - HTTPS is much more secure than HTTP. When you connect to an HTTPS-secured server—secure sites like your bank’s will automatically redirect you to HTTPS—your web browser checks the website’s security certificate and verifies it was issued by a legitimate certificate authority
13. [Domain Name Service(DNS)](https://www.networkworld.com/article/3268449/what-is-dns-and-how-does-it-work.html)
14. [Eventloop in nodejs](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)
15. CAP: A data cap, often erroneously referred to as a bandwidth cap, is an artificial restriction imposed on the transfer of data over a network.
16. [How TCP connection is established?](https://www.vskills.in/certification/tutorial/information-technology/basic-network-support-professional/tcp-connection-establish-and-terminate/) [How https work?](https://www.cloudflare.com/learning/ssl/what-is-https/#:~:text=How%20does%20HTTPS%20work%3F,encryption%20protocol%20to%20encrypt%20communications.&text=This%20key%20lives%20on%20a,in%20a%20way%20that's%20secure)
17. How html, css & js is rendered on a browser?
18. [How Dns Resolutons works?](https://totaluptime.com/kb/how-does-a-dns-query-work/#:~:text=DNS%20queries%20resolve%20in%20a%20number%20of%20different%20ways.&text=The%20DNS%20server%20can%20use,answer%20back%20to%20the%20client) [What is reverse proxy?](https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/)
19. [Browser page render and DOM/Tree like structure](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction)
20. [React. Why it is better? How it is so fast?](https://www.altexsoft.com/blog/engineering/the-good-and-the-bad-of-reactjs-and-react-native/)
21. Is there a limit to the number of callbacks?
22. [Will http work if we remove tcp?](https://www.quora.com/Does-HTTP-use-TCP-or-UDP-Why)
23. [What happens when you type google.com](https://medium.com/@maneesha.wijesinghe1/what-happens-when-you-type-an-url-in-the-browser-and-press-enter-bb0aa2449c1a)
24. How Ajax works: Asynchronous JavaScript and XML. AJAX is a technique for creating fast and dynamic web pages. AJAX allows web pages to be updated asynchronously by exchanging small amounts of data with the server behind the scenes. This means that it is possible to update parts of a web page, without reloading the whole page.
25. Why postman?
26. How internet works?
27. http vs https:
  - HTTP URL in your browser's address bar is http:// and the HTTPS URL is https://.
  - HTTP is unsecured while HTTPS is secured.
  - HTTP sends data over port 80 while HTTPS uses port 443.
  - HTTP operates at application layer, while HTTPS operates at transport layer.
  - No SSL certificates are required for HTTP, with HTTPS it is required that you have an SSL certificate and it is signed by     a CA.
  - HTTP doesn't require domain validation, where as HTTPS requires at least domain validation and certain certificates even     require legal document validation.
  - No encryption in HTTP, with HTTPS the data is encrypted before sending
28. [hashing vs encryption](https://www.solarwindsmsp.com/blog/hashing-vs-encryption%C2%A0)
29. [Web Sockets and Http request](https://developerinsider.co/difference-between-http-and-http-2-0-websocket/#:~:text=WebSocket%20is%20a%20protocol%20providing,HTTP%20providing%20half%2Dduplex%20communication.&text=Means%2C%20server%20can%20push%20information,does%20not%20allow%20direct%20HTTP))
30. Process thread
31. Difference between encryption and hashing. What is used in real-life projects for saving passwords etc?
  - Hashing
