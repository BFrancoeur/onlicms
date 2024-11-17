# onlicms
A new cms that will be as robust as WordPress, with a fraction of the code

# Architecture
- PHP shells/stubs
- JavaScript (Typescript?) page layout generation
- Static HTML pages with dynamic inputs (similar to Gatsby, Netlify, etc.)
- Two-server architecture: one to render the layout and one to generate optimized, static HTML for the front-end. _Can this be done on a single server?_

# Tasks
- Create database (Mongo or Maria?)
 - Create a secure database connection
    
- Create Homepage
 
- Create Admin dashboard page
  
- Create permissions for these roles:
  - User/Subscriber
  - Contributor/Author
  - Editor
  - Admin (CMS only)

 - Create User dashboard
 -  Create Contributor dashboard
 -  Create Editor dashboard

 -  Create Basic Content Editing Page
  - CRUD Content
    - Set allowed file types
    - Include fields for author info (eventualy autofill this info)
      - Author First Name
      - Author Last Name
      - Author Title
      - Author Publish Date
      - Author Update
     
- 
