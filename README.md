request - POST

https://onesignal.com/api/v1/notifications

header

content-type: application/json
authorization: Basic [Base64 Authorization]

body

{
	"app_id":"[App_id site]",
	"filters":[
  		{"field": "tag", "key": "userId", "relation": "=", "value": "example_userId_123"}
	],
    "contents": {"en": "OI!!!!!!"}
}