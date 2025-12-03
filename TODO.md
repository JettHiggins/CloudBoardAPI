- [x] Add credentials : include to USER BASED requests. 
        Problem found (cant do cross origin requests when in http. Will had to update prod to support this.)

- [x] Allow Extension to Send Requests.


- [ ] Add CSRF Protections
 - I mean like so if someone gets someones username (Which is easy right now because you can mess with inputs) - just need to make sure usernames are parsed as strings and not objects
 - They can send a request with that username to the backend which is public using something that bypasses CORS and they could get their Upload using that.
