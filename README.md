# Repo for teslatrails.net

- [x] Conceptualize site
  - [x] Draft purpose of site
    - Purpose: Create a forum for users to post and discuss photos of their Tesla vehicles in nature (e.g. trail heads, camping, etc)
    - Secondary: Answer hiking/camping related questions regarding Tesla vehicles (e.g. camp mode, accessories, etc)
  - [x] Wireframe
        ![draft of teslatrails.net](drafts/Web%201920%20–%201.png)
- [ ] Create database to store users, user information, posts
  - [ ] Investigate and choose DB structure (MongoDB, Redis, SQL)
  - [ ] Implement database
- [ ] Develop Python backend using Flask/Django to service API requests
  - [ ] User: Create, read, update
    - [ ] User types? User, company/sponsor
  - [ ] 3rd party oauth
  - [ ] Post: Create, read, update, delete
    - [ ] Post types? User, sponsor/market
    - [ ] Location for photos
  - [ ] Tagging
- [ ] Develop React front end
  - [ ] Home page
  - [ ] General Forum
    - [ ] Location Search?
  - [ ] FAQ
  - [ ] Market?
