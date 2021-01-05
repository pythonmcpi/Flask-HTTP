# Flask-HTTP
A simple system for storing values using HTTP requests

API in [API.md](API.md)

I'm making this project as practice for using Flask to make HTTP apis. This project implements a server which supports creating new name, collections, setting values, getting values, updating values, and maybe more. To do this, it uses HTTP GET, POST, PUT, PATCH, and DELETE. Responses are in json, or in the case of GETting a value, the value. For more info, read the [API Docs](API.md).

## Todo
> Please note that items with a & mean they may not be implemented.
- [ ] Basic Flask Application
- [ ] Route: /v1/
	- [ ] POST /v1/new
	- [ ] GET /v1/content/*
	- [ ] 301 /content/* > /v1/content/*
	- [ ] PUT /v1/content/*
	- [ ] PATCH /v1/content/* (json only)
	- [ ] DELETE /v1/content/*
	- [ ] Names
	- [ ] Collections
	- [ ] Json
