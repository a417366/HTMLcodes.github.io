| Error| Description|
|----------|----------|
|401 Unauthorized|The required client identification has not been successfully provided.<br/>User authentication failed or did not take place. <br/> The application is not registered with the plan that is used.<br/> The application is not active.|
|404 Not Found|Information for the provider organization or environment was not found.<br/> The API URL was not found in the organization or environment.|
|405 Method Not Allowed |The API URL was found, but no operation was found that supports the requested HTTP verb.|
|406 Not Acceptable |The API cannot produce any responses that are supported by the application|
|500 Internal Server Error |An error occurred while executing this request.|
|503 Service Unavailable |The status of an API was switched from online to offline, making the API unavailable across all Products in which it is contained|
