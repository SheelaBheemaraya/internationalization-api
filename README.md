# internationalization-api

nternationalization is the process of designing web applications or services in such a way that it can provide support for various countries, various languages automatically without making the changes in the application.


Open the REST client Postman and perform the following changes:

Select the GET request.
Type the URI http://localhost:9087/hello-world-internationalized
Click on Headers tab and type:
||KEY             | VALUE|
content type       application/json
accept-language    us

->Now we change the RequestHeader us to fr and send a GET request again.

||KEY             | VALUE|
content type       application/json
accept-language    fr
