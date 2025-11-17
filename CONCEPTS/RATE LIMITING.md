Rate limiting is a strategy for limiting network traffic. It puts a cap on how often someone can repeat an action within a certain timeframe – 
for instance, trying to log in to an account. Rate limiting can help stop certain kinds of malicious bot activity.
It can also reduce strain on web servers. However, rate limiting is not a complete solution for managing bot activity.


**How does rate limiting work?**
Rate limiting runs within an application, rather than running on the web server itself. Typically, rate limiting is based on tracking the IP addresses that requests are coming from, and tracking how much time elapses between each request. The IP address is the main way an application identifies who or what is making the request.

A rate limiting solution measures the amount of time between each request from each IP address, and also measures the number of requests within a specified timeframe. If there are too many requests from a single IP within the given timeframe, the rate limiting solution will not fulfill the IP address's requests for a certain amount of time.

Essentially, a rate-limited application will say, "Hey, slow down," to unique users that are making requests at a rapid rate. This is comparable to a police officer who pulls over a driver for exceeding the road's speed limit, or to a parent who tells their child not to eat so much candy in such a short span of time.


---
