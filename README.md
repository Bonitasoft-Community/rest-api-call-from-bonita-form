# REST API call from a Bonita form


This example demonstrate how to perform a REST API call directly from a Bonita form. It is useful when you need to display data that you can get by calling a REST API.

The solution is build using:
- a form variable of type "External API"
- the form variable initial value is set by specifying in the variable configuration the URL of the REST API to call (GET request)
- the form variable is then bind to form widgets (a table in this example) to display the value

Note that in this example all the processing happen on the client side, i.e. in the web browser of the user who display the form.

If you need to process the result of the REST API call as part of your process execution (for example use it in gateway condition or as input for a connector) you should rather use the REST connector. [Another example](https://github.com/Bonitasoft-Community/rest-connector-to-business-data) is available to demonstrate this alternative. 

## Use this example
You can download the .bos file from the release section and import this file in your own Studio workspace.
