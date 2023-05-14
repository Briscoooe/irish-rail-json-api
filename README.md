An unofficial REST API wrapper for the [Irish Rail Realtime API](http://api.irishrail.ie/realtime/). The current API returns XML across a series of inconsistently named SOAP endpoints and it's not very user-friendly. I used Flask to make a self-documenting OpenAPI REST API around it, making it easier to interact with and get a view of how the different endpoints relate to each other