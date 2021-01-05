# API

## Create new key
**URL:** /v1/new
**Method:** POST
**Body:** Json:
	 - Required string "name"
	 - Optional string "/url/to/collection/"
	 - Optional string type("name" | "collection" | "json") default "name" (if invalid, use default)
**Success Response:**
	 - HTTP Code: 201
	 - Content: Json: {"status":<http code>, "full_path":<full path to item>}
**Error Response:**
	 - Name Already Taken
		 - HTTP Code: 409
## WIP, will be worked on later
