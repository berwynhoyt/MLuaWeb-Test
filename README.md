# YottaWeb-Test

A test of different web frameworks with different YottaDB connectors

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/RamSailopal/YottaWeb-Test)

Single containers are provisioned for each stack with the YottaDB layer, web proxy layer and application/YottaDB connector layer all enclosed.

# Python Stack

**Stack 1 - yottapython**

Flask - https://flask.palletsprojects.com/en/2.1.x/

Apache - https://httpd.apache.org/

YottaDB-Python - https://docs.yottadb.com/MultiLangProgGuide/pythonprogram.html

**Stack  2 - yottamg_python**

Flask

Apache

mg_python - https://github.com/chrisemunt/mg_python


# Node Stack

**Stack 1 - nodem**

Express - https://expressjs.com/

Apache

nodem - https://www.npmjs.com/package/nodem

**Stack 2 - mgdbx**

Express

Apache

mgdbx - https://github.com/chrisemunt/mg-dbx


# Native M Stack - yottamgweb

mgweb-server - https://github.com/robtweed/mgweb-server


# Go Stack - yottago

Gin - https://github.com/gin-gonic/gin

Apache

YottaDB-Go - https://docs.yottadb.com/MultiLangProgGuide/goprogram.html


# Running Tests

Each stack is tested using Locust - https://docs.locust.io/en/stable/what-is-locust.html





