---
title: "Webhooks"
datePublished: Fri Jun 30 2023 16:51:37 GMT+0000 (Coordinated Universal Time)
cuid: cln73ul4l00jp9vnv8sgjhd4p
slug: webhooks
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1696143166823/f68d9373-1e23-4569-b34e-b7625098927f.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1696468855552/70c2e2e0-31f9-4893-b6f6-8c6562617979.jpeg
tags: development, webhooks

---

**WEBHOOKS**

**Webhooks** are ways for a web application and external service to send real-time notification to one or more applications. They are automated [HTTP](https://www.freecodecamp.org/news/what-is-http/) requests, triggered when specific events such as comments being posted to a blog, occurs in a source system and sent to a destination system, sometimes with a payload of data.

![Cartoon Webhooks](https://cdn.hashnode.com/res/hashnode/image/upload/v1696143162941/5f7d7d44-a067-4946-9a95-a3e6a751bcb6.png)



The concept of webhooks consists of two parties:

- 
**The sender**:- The application that is notifying another system about an event. It gathers important data about the event and packages it in a payload, then initiates an [HTTP POST](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/POST) request containing the payload data to the webhook URL or endpoint already provided by the receiver.

- 
**The receiver**:- The application that receives and processes the webhook data. It receives the HTTP request and extracts and processes the payload data.


![Sender and Reciever](https://cdn.hashnode.com/res/hashnode/image/upload/v1696143164851/af508b49-e27b-407f-9e10-e8f10623fd0d.png)




**THINGS TO NOTE ABOUT WEBHOOKS**

- 
Webhooks payloads are usually in serialized form-encoded [JSON](https://www.json.org/json-en.html) or [XML](https://aws.amazon.com/what-is/xml/#:~:text=Extensible%20Markup%20Language%20(XML)%20is,implemented%20for%20structured%20data%20management.) [](url)formats.

- 
Both the sender and receiver applications must have the necessary functionalities to send and receive HTTP requests.

- 
A secure HTTPS  URL endpoint should be provided as the webhook receiver.

- 
It is best to respond with a 200 or 302 [HTTP response status code](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) when a notification is sent.

- 
A single webhook request can be distributed to multiple destinations that need the information. 

**USES OF WEBHOOKS**

Webhooks are used in web development to enable communication between different services, some other uses are;

- 
Data Synchronization

- 
Integration with Third-Party Services

- 
Real-time Updates

- 
Web Analytics and Tracking


**CONCLUSION**

Webhooks have become a popular method  to improve efficiency among online platforms by enabling real-time communication between applications.