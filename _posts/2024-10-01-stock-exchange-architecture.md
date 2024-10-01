---
layout: single
tags:
modified: 2024-10-01
excerpt: "<br>"
author: Serdarcan Buyukdereli
title: Stock Exchange Architecture
author_profile: true
comments: true
categories:
- Architecture
header:
   overlay_color: "#5e616c"
   overlay_image: citation.png
   overlay_filter: .8
   teaser: citation.png
tags:
- Architecture
- DevOps

excerpt: Stock exchange architecture refers to the design and structure of the technological systems that facilitate the trading of securities. It ensures efficient, secure, and high-speed execution of trades, often incorporating features like low-latency communication, fault tolerance, and real-time data processing to support global financial markets*.
pinned: false

---

# System Architecture Design

## Microservice Architecture

### Advantages of Microservices

- **Independent Development and Deployment:** Microservices can be developed and deployed separately, increasing team efficiency and allowing for isolated changes.
- **Technology Flexibility:** The most suitable technology can be chosen for each service, for example, based on performance or development speed requirements. (Flexible choice of programming language)
- **Fault Tolerance:** The failure of one microservice does not affect the entire system. This feature enhances overall system reliability.


### Use of Load Balancer:

- **API Gateway:** Provides security and routing as a central access point.
- **Load Balancing and Caching:** Distributes requests, stores frequently used data.
- **Security and Monitoring:** Provides features such as JWT authentication, rate limiting, and request tracking.

With microservice architecture, we can scale our services in a more controlled and flexible manner. This architecture provides greater flexibility to our system. This situation gives us advantages in traffic management, security, and many other areas.

As shown in the image, after an incoming request, we can route requests directly to the desired endpoints of our services through a load balancer (Load Balancer L4) and a Layer 7 component such as an API Gateway. This structure ensures security with JWT while allowing our service to continue operating unaffected in case any pod crashes. Thus, we can directly provide high availability.