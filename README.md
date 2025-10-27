Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
Why did the backend use a NoSQL MongoDB database?

  The different types of frontend development used in the full-stack project (i.e., Express, JS, and SPA) were used depending on the need for the web application. In an area
  where the web application does not need to be reactive, we can utilize Express HTML. Areas like the Admin Page, where access to editing, adding, and logging in is needed,
  we utilize SPA as it is reactive and better serves these scenarios. 

  The backend utilized a NoSQL MongoDB, since the web application is lightweight, it is a good option for lightweight designs that do not necessarily contain a concrete
  structure. The Admin Page also allows for constant reading and writing for trips that need a flexible, unstructured DB to allow for.


How is JSON different from JavaScript and how does JSON tie together the frontend and backend development pieces?
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

  JSON (JavaScript Object Notation) is different from JavaScript because it is a format for which data is read and written rather than a scripting language. 
  JSON follows a key-value pairing that provides an efficient way to read and write data. Ex.<br> 
  {<br>
    "firstName": "Wesley",<br>
    "lastName": "Van Wie"<br>
  }<br>
  JSON can easily be parsed to extract data for formatting.


Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full-stack application.

  In order for a client to access data or methods that occur on the server, the client must send a proper request to the server. This proper request can be a multitude of
  things; some requests may require a token attached that authorizes a user for each subsequent request, a proper JSON format, authorized credentials, etc. Once these requests
  are sent, the server authorizes the request, and it is routed to the proper controller that contains the calls to the methods for handling that request. The method handles the
  request, and a response is sent back to the client, which may just be a status code or a JSON body.

  

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

  This course has helped me to get closer to reaching professional goals, as it is the first class I have gotten to take that goes into depth in frontend programming, as well as
  tying both the front and backend together to create a functional full-stack application. I have learned how to create a full-stack application that is reactive and
  maintainable through standalone components.
