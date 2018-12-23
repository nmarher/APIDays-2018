# Presentations APIDays 2018

The purpose of this repository is to include the different resources and presentations of the APIDays in Paris that took place on December 11, 12, 2018 (https://www.apidays.co/paris).

If you have any of the presentations and it is not on the list please add a comment to include it or contact me on [LinkedIn](https://www.linkedin.com/in/noelia-mart%C3%ADn-hern%C3%A1ndez-9bb12960/).

Of course if you want to improve the information or find an error feel free to include what you consider.

## API design & API Architecture

### [Event-Driven APIs](https://www.slideshare.net/EricHoresnyi/2018-1210-apidaysio-eric-horesnyi-streamdataio-eventdriven-ap-is?qid=f7c0efa1-6537-44ad-847f-fbf1b5c428a9&v=&b=&from_search=5)
- **Author**: Eric Horesnyi, CEO Streamdata.io
- **Abstract**: Traditional software was based on batches and databases for decades. But the real world is a system of agents changing states based on events sent by other agents, not records updating each other once in a while. To provide better UX, frontends have started to react to events with reactive frameworks. Data hubs too have moved from lakes to streams. AI also is updating its models based on events with streaming algorithms. And finally dear HTTP/2-3 is now based on streams. Since APIs are -by definition- the interface between domains, successful API strategies by most mature API providers are adding webhooks, and streaming, on top of their existing request and response approach to deliver APIs. Let's take a moment to learn from the API rockstars like Slack, Twitch and Nest, as well as the growing number of API pioneers who have invested heavily on their event-driven infrastructure in 2018.

### [How do you back up and consistently recover your microservice architecture?](https://speakerdeck.com/pautasso/how-do-you-back-up-and-consistently-recover-your-microservice-architecture)
- **Author**: Cesare Pautasso. Professor Software Institute, USI Lugano
- **Abstract**: Microservices by definition let each service manage its own database independently using the most suitable data management technology. In this talk we explore the ultimate consequences of the Polyglot persistence principle, which can be summarized using the BAC theorem: ¨When Backing up a microservice architecture, it is not possible to have both Consistency (after recovery) and full Autonomy (while backing up the system).¨ In other words, loosely coupled Microservice architectures are doomed to become inconsistent after disaster strikes. Only tightly coupled Microservice architectures adopting a synchronized backup strategy can achieve a consistent recovery. We will discuss how the trade-off between consistency and autonomy implied by the BAC theorem impacts the monolith decomposition process and the corresponding service API boundary design.

### [Autonomous APIs](https://speakerdeck.com/zdne/autonomous-apis-paris-2018)
- **Author**: Zdenek Nemec. Founder, Good API
- **Abstract**: The exponential growth of APIs, further accelerated by IoT, micro-services, and FaaS, brings many technical and economical challenges. On one side, businesses are racing to establishing API programs to connect with their customers and to gain upper hand on competitors. On the other side, engineering teams are facing growing demand for new APIs and soon out-of-the-scale complexity managing existing deployments. In this talk, we will explore the challenges of past and current APIs, both with regards to their technical aspects and the API economy. We will discuss the possible solutions to these problems, and introduce Autonomous APIs. In the second part, we will take a closer look at Autonomous APIs and how they reshape our current world and how they can existing problems for both businesses and engineering.

### [Balancing your latency budget: on the future of applications at the edge](https://www.slideshare.net/OriPekelman/api-days-2018-balance-your-latency-budget)
- **Author**: Ori Pekelman. Co-Founder & CPO, Platform.sh

### [Balancing your latency budget: on the future of applications at the edge](https://www.slideshare.net/OriPekelman/api-days-2018-balance-your-latency-budget)
- **Author**: Ori Pekelman, Co-Founder & CPO, Platform.sh

## API Product Management, API Lifecycle Management

### [API theory vs practice, an honest review of ARTE’s API strategy](https://speakerdeck.com/mbreen/api-theory-vs-practice-an-honest-review-of-artes-api-strategy)
- **Author**: Matthieu BREEN, Project Manager in ARTE
- **Abstract**: When designing an API, we often believe we precisely know what we want, and that our first release will be a success. In reality, it turn out that API design is more of an iterative process. As the Project Manager in charge of APIs at ARTE, I will give you my feedback on the challenges we have faced and the choices we have made, from the launch of our first API in 2012 to our 3rd generation in 2018.
  
## Open Banking, API Security and Monitoring

### [Implementing security requirements for banking API system using Open Source Software (OSS)](https://www.slideshare.net/YuichiNakamura10/implementing-security-requirements-for-banking-api-system-using-open-source-software-oss?qid=f7c0efa1-6537-44ad-847f-fbf1b5c428a9&v=&b=&from_search=4)
- **Author**: Yuichi Nakamura, Senior Engineer Hitachi
- **Abstract**: OAuth is commonly required for open API systems for banking. However, OAuth is only a protocol to convey authorization information. Therefore, authentication and access control around OAuth have to be designed and implemented separately. In the presentation, authentication and access control requirements around OAuth are clarified, and how we achieved these requirements using OSS such as Keycloak and 3scale(apicast) including collaboration with OSS community, will be introduced.
  
## The State of GraphQL, GraphQL on the field

### [Samplin GraphQL](https://speakerdeck.com/bdougie/samplin-graphql)
- **Author**: Brian Douglas, Developer Advocate GitHub
- **Abstract**: The move to GraphQL marked a larger shift in GitHub's Platform strategy towards more transparency and more flexibility in our API. Over the past year, GitHub has been iterating on their schema to bring it closer towards feature completeness and strengthening the use for 3rd party integrators. Join me in walking through some of the newer ways developers are leveraging our API primitives and benefiting from GraphQL adoption into their development workflow.

### [Discover AWS AppSync, the gateway to your data in the cloud](https://www.slideshare.net/sebsto/0-to-60-with-aws-appsync)
- **Author**: Sébastien Stormacq, Developer Evangelist in AWS Amazon Web Service
- **Abstract**: AWS AppSync is a serverless back-end for mobile, web, and enterprise applications. AWS AppSync makes it easy to build data driven mobile and web applications by handling securely all the application data management tasks like online and offline data access, data synchronization, and data manipulation across multiple data sources. AWS AppSync uses GraphQL, an API query language designed to build client applications by providing an intuitive and flexible syntax for describing their data requirement. Upon attending this talk, you will learn how to define your GraphQL service in AWS APpSync, how to integrate with backend data sources, such as database or your custom code and how to easily integrate AWS ApSync GraphQL APIs in your client code in iOS, Android or React applications.
  
## DevOps Culture and Approach (Microservices, Containers)

### [Cyber Security in Continuous Delivery](https://www.slideshare.net/mobile/estelleinomniaparatus/cyber-security-in-continuous-delivery)
- **Author**: Estelle Auberix, Practice Manager in Umanis
- **Abstract**: In a context of persistent threats and sophisticated attacks, how to manage your Cyber Security with Continuous Delivery. What do you have to watch out for? What are the errors to avoid? What are the possible solutions?

### [Just a Spoonful of Agile Makes The Transformation Go Down](https://speakerdeck.com/punkstarman/just-a-spoonful-of-agile-helps-the-transformation-go-down)
- **Author**: William Bartlett, DevOps Consultant
- **Abstract**: Everyone has a story. The Next-Big-Thing comes along and you must transform the team, the department, nay the whole company. So you draw up the plan, drill down the tasks, hand them out to everyone, ask for estimates. You calculate the ROI, print out the Gantt chart and hang it up for all to see. Then a year later, the budget bursts its banks, the landing strip seems smaller and smaller, and the fuel reserves dwindle. Old habits bring back the old routine.

## APIs for a Programmable Society

### [The impact of decentralization on APIs and clients](https://rubenverborgh.github.io/Slides-APIdays-2018/#decoupling)
- **Author**: Ruben Verborgh, 
- **Abstract**: Many of todays’s online business models focus on data harvesting. Whether we open a Facebook account, wear a smartwatch, or go shopping, we generate data that is captured through APIs. This data is then stored in a limited number of centralized places, outside of our control. The Solid ecosystem inverts this relationship by enabling every user to store their own data, independently of central parties. This decoupling of data and applications will have a major impact on the way we build Web APIs and clients. In this talk, I will explain the Solid ecosystem and a query-based design of APIs and clients, covering technologies as diverse as HTTP, Linked Data, and GraphQL.
  
## The new API stack

### [What Comes Next? Beyond API Products](https://www.slideshare.net/LauraHeritage/api-days-paris-2018-axway-keynote?qid=f7c0efa1-6537-44ad-847f-fbf1b5c428a9&v=&b=&from_search=1)
- **Author**: Laura Heritage, Director Solution Management Axway
- **Abstract**: It has been approximately 7-8 years now that we've been speaking about APIs as a product and kick started the API economy frenzy. It surely doesn't end here. What comes next?

### [The Open Source Impact on Digital Transformation](https://www.slideshare.net/harsha89/open-source-impact-on-digital-transformation)
- **Author**: Harsha Kumara. Associate Technical Lead, WSO2
- **Abstract**: Digital transformation is key for an organization to evolve and remain competitive in the market. It is about building digital experiences that make the life of your consumers easier and more efficient. With digital transformation, organizations are required to adopt to rapid technology changes. This requires support from both the organization and vendors who provide tools to build enterprise systems. Software vendors also face major challenges to build software tools as fast as the market demands it. Open source software has the power to speed up rapid adoption of technology changes with the support from the community. In this session Harsha will be discussing benefits of open source software including: Rapid adoption of new technologies and speed to market with wider collaboration; limitless resources that comes as a benefit of the community; wider thinking and wider intellectual input that comes from the community; open standards enabling easy integrations to other systems; better security due to the ability to know what's inside; working with best in the software industry as software giants embrace open source technology.

## The State of OAI, Industry example of Open API Specifications

### [OpenAPI Tooling Discovery and Marketing](https://gitpitch.com/mikeralphson/talk-openapi-tool-discovery/master)
- **Author**: Mike Ralphson, Technical Steering Committee Member, OpenAPI Initiative
- **Abstract**: A personal journey through the brief history of OpenAPI 3.x tooling discovery and marketing, from markdown lists to static sites and beyond.

## Workshops

### [Ping Identity Workshop: Standard based API security, access control and AI based attack detection](https://www.slideshare.net/PingIdentity/standard-based-api-security-access-control-and-ai-based-attack-api-days-paris-2018/PingIdentity/standard-based-api-security-access-control-and-ai-based-attack-api-days-paris-2018?hootPostID=d185a3650a51081c582e26a586a676c0)
- **Author**: Philippe Duboc. Solution Arquitect, Ping Solution. 
- **Abstract**: As APIs continue to drive digital transformation efforts in the enterprise and support innovative customer experiences, securing them has never been more important. During this workshop Ping Identity will introduce how to leverage the OpenID Connect, OAuth2 and new emerging standards to protect the APIs. Ping Identity will show how the Intelligent Ping Identity Platform can be used to protect APIs in a pro-active way and how AI can help to protect against attacks.

### [Tyk Workshop: Taming your monoliths & microservices](https://gallery.mailchimp.com/0017851599c78a746bf0197d5/files/98e00ec5-96ae-402d-9313-40efa4430b64/API_Days_Paris_2018_compressed.pdf?utm_source=API+Days+Paris+2018+Thank+you+and+link+to+webinars&utm_campaign=c540d3aa56-EMAIL_CAMPAIGN_2018_11_14_03_28_COPY_01&utm_medium=email&utm_term=0_b3c753ba68-c540d3aa56-514005261)
- **Author**: Ahmet Soormally. Software Engineer,Tyk.
- **Abstract**:



