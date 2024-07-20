[![Build Status](https://travis-ci.com/cedricfrancoys/equal.svg?branch=master)](https://travis-ci.com/cedricfrancoys/equal)
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
[![Maintainer](https://img.shields.io/badge/maintainer-cedricfrancoys-blue)](https://github.com/cedricfrancoys)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/cedricfrancoys/equal/pulls)
![eQual - Create great Apps, your way!](https://github.com/cedricfrancoys/equal/blob/master/public/assets/img/equal_logo.png?raw=true)
# Create great Apps, your way!

eQual is a versatile, language-agnostic and web-oriented framework, aiming to elegantly manage interactions between front-end Apps and Business Logic involved in modern Web Applications.

## Benefits

**Rock Solid Security** Secure every API endpoint with User Management, Role-Based Access Controls, SSO Authentication, JWT, CORS, and OAuth.

**Server-Side Scripting** Implement custom logic on the request or response of any API endpoint or quickly build your own custom APIs with JavaScript V8, Node.js, or PHP.

**Instant APIs** Without Code Automatically generate a complete set of REST APIs with live documentation for any SQL or NoSQL database, file storage system, or external service.

## Example

### CLI
`$ ./equal.run --get=demo_first`

### HTTP
GET /?get=demo_first HTTP/1.1

### Source
```
<?php
// Tired of steep learning curves?
echo "This is a valid Contoller!";
```

## Requirements

eQual requires the following environment:

* **PHP 7+** with extensions mysqli (mandatory) + gd opcache zip tidy (optional)
* **Apache 2+** or **Nginx**
* **MySQL 5+** compatible DBMS (tested up to MySQL 5.7 and MariaDB 10.3)

## Install

Download code as ZIP:
```
wget https://github.com/cedricfrancoys/equal/archive/master.zip
```
or clone with Git :
```
git clone https://github.com/cedricfrancoys/equal.git
```

For more info, see : [http://doc.equal.run/getting-started/installation](http://doc.equal.run/getting-started/installation/)
