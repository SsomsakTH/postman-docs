---
title: "Echo API"
updated: 2023-05-19
contextual_links:
  - type: section
    name: "Additional resources"
  - type: subtitle
    name: "Blog posts"
  - type: link
    name: "10 Postman Features Everyone Should Know"
    url: "https://blog.postman.com/10-postman-features-everyone-should-know/"
  - type: link
    name: "Introducing Postman’s WebSocket Echo Service"
    url: "https://blog.postman.com/introducing-postman-websocket-echo-service/"

---

You can use the Postman Echo API to test requests in Postman. The Echo API returns a JSON response that includes all details from the request you sent, including any data items you included.

Many Postman learning resources, including the documentation here in the Learning Center, use the Echo API because it provides a quick way to send a request without worrying about authentication or request configuration. If you want to learn how to do something in Postman without connecting to a "real" API, you can use the Echo API.

## Using the Echo API

The Echo API includes endpoints to test different request methods, parameters, authentication, and a variety of supporting utilities. To learn about the available endpoints, read the [Echo API documentation](https://www.postman.com/postman/workspace/published-postman-templates/documentation/631643-f695cab7-6878-eb55-7943-ad88e1ccfd65?ctx=documentation).

To test the Echo API, open a new request in Postman and enter the following path in the URL field:

```http
postman-echo.com/get
```

Select the `GET` method, then select __Send__. The Echo API will return a JSON object that has details from the request.

![Postman Echo response](https://assets.postman.com/postman-docs/v10/postman-echo-api-response-v10.jpg)

## Next steps

To continue working with the Echo collection, and to find other collections to aid in learning about APIs:

- You can fork the [Echo collection](https://www.postman.com/postman/workspace/published-postman-templates/documentation/631643-f695cab7-6878-eb55-7943-ad88e1ccfd65?ctx=documentation) to use pre-built requests to the API. You can also edit the requests in the forked collection to suit your needs.
- You can also find many other useful collections for learning about Postman and APIs in the [Public API Network](/docs/getting-started/exploring-public-api-network/).
