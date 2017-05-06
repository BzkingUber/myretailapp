# myretailapp
Steps to run:

1)Download MongoDB
2)Start mongoDB
3)gradle bootRun
4)Starts on localhost:9005
5)Tests do not require MongoDB running as they use the Embedded Mongo framework

ROUTES:

GET     /products/{id}
Example: http://localhost:9005/products/13860428

PUT     /products/{id} 

Example:
http://localhost:9005/products/13860428

RequestBody:
{
	"value": "15.0",
	"currencyCode": "USD"
}
