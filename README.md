# knowledge-is-power

## Note
This was a university project. The source code has been kept private to prevent future students using the work for plaigarism. Potential employers can request the codebase by emailing me: joesambristow@gmail.com. 

## Introduction
A bookstore webapp. The stack was MySQL / AWS RDS -> Java backend API -> React.js frontend consumer. The only material provided was a poor quality book database, with many columns violating first normal form. Development time was dedicated to addressing this.  


https://github.com/user-attachments/assets/a52304f9-3437-46a0-ab76-de5bba20c5e8


https://github.com/user-attachments/assets/c4f3d950-6257-4d4d-96f2-51d037b56ac3


## Features
* Access control (user read-only, admin read + write).
* Full CRUD support for 3 data formats: JSON, XML, String.
* Full foreign character support via. UTF-8.
* Book covers (via. Google Books API).
* Browse by genre, title, or author.
* Pagination.

## Noteworthy Implementation Details
* Client and server-side input validation (sanitisation, validation, escaping).
* Client and server-side error handling (appropriate status codes + messages).
* Performance optimisation (HikariCP connection pooling, AbortController for asynchronous processing).
* Compliance with endpoint conventions.
* Database normalisation: genres.
* AWS cloud implementation (AuroraDB + Elastic Beanstalk).
