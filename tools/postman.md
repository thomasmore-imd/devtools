# 1. Postman

Postman is a tool to perform HTTP requests. You can make for example GET and POST requests to domain names, IP addresses and localhost. Postman also supports other methods like PUT and DELETE.

Postman can be helpful while setting up and testing API's.

## 1.1 Installation

You can download Postman on their website: https://www.getpostman.com. Optionally, you can create an account, for example if you want to save requests (see 1.3 Collections).

## 1.2 Making requests

By default, an empty request tab will pop up. Fill in the URL of the page you request (for example: http://dummy.restapiexample.com/api/v1/employees) and click Send.

Optionally, you can set parameters, authorization (with token or login credentials), headers and body (form parameters or JSON).

## 1.3 Collections

Collections are groups of HTTP requests. You can save the URL, parameters, headers and authorization settings for each request by clicking the Save button in the request tab.

### 1.3.1 Variables

To maintain your requests more easily, you can save some variables into your collections. This can be helpful if you have lots of requests with the same base URL or to set an API version.

You can set variables in your collection's settings: Collections tab, right click the collection and click Edit. In the popup, open the tab Variables and fill in the key and value of your variable. Using your variable in a request is easy: just use {{VARIABLE_NAME}}.

Example: if you have a variable with key 'API_BASE_URL' and value 'http://dummy.restapiexample.com/api/v1', just make a request with this URL: '{{API_BASE_URL}}/employees'.