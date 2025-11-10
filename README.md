# knowledge-is-power

## Note
This was a university project. The source code has been kept private to prevent future students using the work for plaigarism. Potential employers can request the codebase by emailing me: joesambristow@gmail.com. 

## Introduction
A bookstore webapp. The stack was MySQL / AWS RDS -> Java backend API -> React.js frontend consumer. The only material provided was a poor quality book database, with many columns violating first normal form. Development time was dedicated to addressing this.  

## Features
* Access control (user read-only, admin read + write).
* CRUD support for JSON, XML, String data formats.
* Browse by genre, search term.
* Pagination.

## Noteworthy Implementation Details
* Client and server-side input validation (sanitisation, validation, escaping).
* Client and server-side error handling (appropriate status codes + messages).
* Performance optimisation (HikariCP connection pooling, AbortController for asynchronous processing).
* Compliance with endpoint conventions.
* Database normalisation: genres.
* AWS cloud implementation (AuroraDB + Elastic Beanstalk).
