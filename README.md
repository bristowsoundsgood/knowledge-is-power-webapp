# knowledge-is-power

## Note
This was a university project. The source code has been kept private to prevent future students using the work for plaigarism. Potential employers can request the codebase by emailing me: joesambristow@gmail.com. 

## Introduction
A bookstore webapp. The stack was MySQL / AWS RDS -> Java backend API -> React.js frontend consumer. The only material provided was a poor quality book database, with many columns violating first normal form. Development time was dedicated to addressing this.  


https://github.com/user-attachments/assets/74c2e044-c6b8-490c-9aa9-7b2b669450be


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
