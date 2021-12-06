# Introducing Revolution
_Created by Emily Freeman_

### Background

In many ways DevOps built on the foundation of Agile to become a default — a standard that we all reach for in our everyday work. When DevOps surfaced as an idea in 2008, the tech industry was in a vastly different space. AWS was in infancy, offering only a handful of services. Azure and GCP didn’t exist yet. The majority of companies maintained their own infrastructure. Developers wrote code and relied on sysadmins to deploy new code at scheduled intervals, sometimes months or even years apart. Container technology hadn’t been invented and applications adhered to monolithic architecture. Databases were relational, serverless wasn’t a thing.

Everything — from the application to the engineers — was centralized. Our current ecosystem couldn’t be more different. Software is still hard, but we continue to find novel solutions to consistently difficult, persistent problems. Now some of these end up being a rebranding of old ideas while others are a unique and clever take to abstracting complexity or automating toil or — perhaps most important — rethinking, challenging the premises we have accepted as canon for years, even decades.

In the years since DevOps attempted to answer the critical conflict between developers and operations engineers, DevOps has become a catchall term. And there have been a number of derivative works. DevOps has come to mean 5000 different things to 5000 different people. For some, it can be distilled to continuous integration and continuous delivery or CI/CD. For others, it’s simply deploying code more frequently, perhaps adding a smattering of tests. For others still it’s organizational — they’ve added a platform team, perhaps even a questionably named “DevOps” team. Or have created an engineering structure that focuses on the separation of concerns — leaving feature teams to manage the development, deployment, security, and maintenance of their siloed services. Whatever the interpretation, what’s important is there isn’t a universally accepted standard of what DevOps is or looks like in execution. It’s a philosophy more than anything else — a framework people can utilize to configure and customize their specific circumstances to modern development practices. 

### What's Next for DevOps?
The characteristic of DevOps that I think we can all agree on... is that it attempted to capture the challenges of the entire software development process. It’s that broad umbrella, that holistic view, that I think we need to breathe life into again. The challenge we face is that DevOps is an increasingly outmoded solution to a previous problem. Developers now face cultural and technical challenges far greater than how to more quickly deploy a monolithic application onto on-premises infrastructure. 

Cloud Native is the future — the next collection of default development decisions — and one the DevOps story can’t absorb in its current form. I believe the era of DevOps is waning. And in this moment, as the sun sets on DevOps, we have a unique opportunity to rethink, rebuild — replatform even. Now I don’t have a crystal ball. I’m not completely certain what the next decade of tech looks like. And I can’t write this story alone. I need you. But I have some ideas that can get the conversation started. I believe to build on what was, we have to throw away the assumptions we’ve taken for granted all this time. In order to move forward, we must first step back.

### Replacing the SDLC
The software (or systems) development lifecycle — what we call the SDLC — has been in use since the 1960s. And it’s remained more or less the same since before color television and the touchtone phone. Over the last 60 years, we’ve made tweaks, slight adjustments, massaged it, zhuzhed it if you will. The stages or steps are always a little different. With Agile and DevOps, we sort of bent it into a circle, even an infinity loop. We added colors. The SDLC has become an assumption. We don’t even think about it anymore. 

Universally adopted constructs like the SDLC have an unspoken permanence. They feel as if they’ve always been and always will be. I think the impact of that is even more potent if you were born AFTER the construct was popularized. Nearly everything around us is a construct, a model, an artifact of a human idea. The chair you’re sitting in. The desk you work at. The mug from which you drink coffee (or wine). Buildings, toilets, plumbing, roads, cars, art, computers, everything. The SDLC is a remnant. An... artifact of a previous era.

**A linear, single-threaded model designed for the manufacture of material goods cannot possibly capture the distributed complexity of modern sociotechnical systems. It just can't.**

And these two ideas aren’t mutually exclusive: that the SDLC was industry-changing, valuable, and extraordinarily impactful. And that it’s time for something new. I believe we are strong enough to hold those two ideas at the same time — showing respect for the past while envisioning the future. I don’t know about you, I’ve never had a software project go smoothly in one go. No matter how small. Even if I’m the only person working on it and committing directly to main like a maverick. **Software development is chaos. It’s a study in entropy.** And it’s not exactly getting simpler. 

The model with which we think and talk about software development must capture the multi-threaded, nonsequential nature of our work. It should embody the roles engineers take on and the considerations they encounter along the way. It should build on the foundations of Agile and DevOps and represent the iterative nature of continuous innovation. When I was thinking about this, I was inspired by ideas like extreme programming and the spiral model. I wanted something that would have layers, threads even, a way of visually representing multiple processes happening in parallel. What I settled on is the Revolution model.

### A New Approach

I believe the visualization of Revolution is capable of capturing the pivotal moments of any software scenario. And I’m going to dive into the discrete elements, but I want to give you a moment to have a first impression. To absorb my idea. 

<img src="https://user-images.githubusercontent.com/12585856/136832537-9b8104d2-1490-4ec1-a5e6-4899ea50fbb7.png" alt="Revolution Model" width="500px" >

I call it Revolution because, well, for one, it revolves. It’s circular shape reflects the continuous and iterative nature of our work. But also because it is revolutionary. I am challenging a 60 year old model that is embedded into our daily language. And create a model that I think more accurately reflects the complexity of modern cloud native software development. 

The Revolution model is constructed of five concentric circles describing critical roles of software development: 
1. Architecting
2. Developing
3. Automating
4. Deploying 
5. Operating 

Intersecting each loop are six spokes that describe the production considerations every engineer must consider throughout any engineering work: 
1. Testability
2. Securability
3. Reliability
4. Observability
5. Flexibility
6. Scalability

The considerations listed are not all encompassing. There are of course things not explicitly included. But I figured if I put 20 spokes, some of us might get a little overwhelmed. Now let’s dive deeper into each element.

### Roles Replace Personas
We’ve long used personas as the default way to divide audiences and tailor messages. To group people. Every company in the world right now is repeating the mantra of “developers, developers, developers.” But personas have always bugged me a bit. Because this approach typically either oversimplifies someone’s career or needlessly complicates it. Few people fit cleanly and completely into persona-based buckets like developers and operations anymore.

The lines have gotten fuzzy. On the other hand, I don’t think we need to tailor messages so specifically as to call out the difference between a DevOps Engineer and a release engineer or a security administrator vs. a security engineer. But perhaps most critically, I believe personas are immutable. A persona is wholly dependent on how someone identifies themselves. It’s intrinsic, not extrinsic. Their titles may change, their jobs may differ, but they’re probably still selecting the same persona on that ubiquitous dropdown we all have to choose from when registering for an event. I was a developer and I will always identify as a developer, despite doing a ton of work in areas like DevOps and AIOps and DevRel. In my heart, I’m a developer. I think about problems from that perspective first. It influences my thinking and approach. 

Roles are very different. Roles are temporary, inconsistent, constantly fluctuating. If I were an actress, the parts I played would be lengthy and varied. But the persona I would identify as would remain an actor, an artist, a thespian. Your work isn’t confined to a single set of skills. It may have been a decade ago, but not today. In any given week or sprint you may play the role of architect, thinking about how to design a feature or service. A developer, building out code or fixing a bug. An automation engineer, looking at how to improve the manual processes we often refer to as a toil. A release engineer, deploying code to different environments or releasing it to customers. Or an operations engineer, ensuring an application functions in consistent, expected ways. 

### Engineering Considerations
**Testability**

And no matter what role we play, we have to consider a number of issues. The first is testability. All software systems require testing to assure architects that designs work... developers that code works, operators that infrastructure is running as expected, and engineers of all disciplines that code changes won’t bring down the system. Testing, in its many forms, is what enables systems to be durable and have longevity. It’s what reassures engineers that changes won’t impact current functionality. A system without tests is a disaster waiting to happen, which is why testability is first among equals at this particular roundtable. 

**Securability**
Security is everyone’s responsibility, but few understand how to design and execute secure systems. I struggle with it. Security incidents, for the most part, are a high impact, low probability events. The really big disasters, the one that end up on the news, and cause us all to get free credit reporting for a year don’t happen super frequently. And thank goodness. Because you know there are endless small vulnerabilities lurking in our systems. Security is something we know we should dedicate time to but don’t often make time for. And let’s be honest, it’s hard and complicated and scary. 

DevSecOps, the first derivative of DevOps, asked engineers to “move security left.” This approach meant that security was a consideration early in the process, not something that would block a release at the last moment. This is also the consideration under which I’m putting compliance and governance. While not perfectly aligned, I figure all the things you have to call lawyers about should just live together. But in all seriousness, these three concepts are really about risk management. Identity, data, authorization — it doesn’t really matter — the question is who has access to what, when, and how. And that is everyone’s responsibility at every stage. 

**Reliability**
Site reliability engineering or SRE is a discipline, a job, an approach for good reason. That said, availability is often mistakenly treated as a synonym for reliability.  If a system is available, but customer data is inaccurate or out of sync, the system is not reliable. If a system is available, but customer data is inaccurate or out of sync, the system is not reliable. Reliability has five key components: availability, latency, throughput, fidelity, and durability. Reliability may be the end result, but resiliency, for me, is the journey, the action, engineers can take to improve reliability. 

**Observability**
Observability is the ability to have insight into an application or system. It is the combination of telemetry, monitoring, and alerting available to engineers and leadership. There is an aspect of observability that overlaps with reliability, but the purpose of observability isn’t just to maintain a reliable system — though that is important — it is the capacity for engineers working on a system to have visibility into the inner workings of that system. The concept of observability originates in linear dynamic systems. And is defined as how well internal states of a system can be understood based on information about its external outputs. It is critical that when companies move systems to the cloud, or utilize managed services, they don’t lose visibility and confidence in their systems. The shared responsibility model of cloud storage, compute, and managed services require that engineering teams be able to quickly be alerted to, identify, and remediate issues as they arise. 

**Flexibility**
Flexible systems are capable of adapting to the meet the ever-changing needs of the customer and market segment. Flexible codebases absorb new code smoothly, embody a clean separation of concerns, are partitioned into small components or classes, and are architected to enable the now and the next. In flexible systems, chained dependencies are reduced or eliminated; database schemas accommodate change well, components communicate via a standardized and well-documented application programming interface (API). The only thing constant is change. And in every role we play, creating flexible solutions that will grow as the applications grow is critical. 

**Scalability**
Finally, scalability. Scalability refers to more than a system’s ability to scale for additional load. It implies growth and a system’s ability to grow over time. Scalability in the Revolution model carries the continuous innovation of a team and the byproducts of that growth within a system. For me, scalability is the most human of the considerations. It requires each of us, in our various roles, to consider everyone around us: our customers who use the system and rely on its services. Our colleagues — current and future — with whom we collaborate. And even our future selves. 

Software development isn’t a straight line, nor is it a perfect loop. It is an ever-changing, complex dance.  There are twirls and pivots and difficult spins. Forward and backward engineers move in parallel, creating truly magnificent pieces of art. We need a modern model for this modern era. And I believe it's just this revolution that will get us started.
