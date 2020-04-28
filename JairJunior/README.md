# Product Review - Fullstory
https://www.fullstory.com/

FullStory is a customer experience data app that captures customer experience data in one powerful and easy-to-use platform.

![Fullstory Hero](./fullstory-hero.png)

## Introduction

Data analytics is difficult. Today, product __builders__ have powerful tools to help measure and develop digital products, such as Google Analytics, Mixpanel, Heap, and Hotjar. But for precise use, it requires efforts doing an appropriate setup and to invest much time querying and analyzing pieces of information. In a startup context, as fast as we can learn, test, and release new solutions can be decisive to drive customer adoption and make a product valuable for final users. 

When I heard about Fullstory for the first time, I thought immediately: “One more analytics tools.” But Fullstory surprised me in a very good way, allowing me to get great insights working just one portion of the time that I have to work using typical tools, like the ones mentioned above. For me, sharing my time and energy doing different tasks, I can well analyze and get better insights working less than usual on data analytics. 

## Best parts

Fullstory simplifies a lot of work for builders. My two favorite features:
 
### Feature 1: Fast search and querying methods

The starting point for analyzing data is an actionable dashboard showing information about the last users' sessions. Some widgets are displaying information about frustrated sessions, slowest pages, error clicks, top users, and more. At the top of the page, we can find a box to search and filter sessions as we want to. We can save these searches as segments in the platform, to not be necessary to set all filter conditions again.
This easy-to-find information probably has a big impact on how builders use Fullstory appropriately.

![Feature Searching](./feature-1-searching.gif)
[Video Link](https://www.youtube.com/watch?v=ZPy9EvrRt2c)

### Feature 2: Troubleshooting panel 

Fullstory provides many features such as events tracking, user sessions replay, and a development console to simulate and understand bugs, saving time trying to reverse engineer discovering how the customer bumped into some error. The benefit of an “All-in-one” user analytics platform is a worthwhile alternative to not use many platforms, decreasing the complexity to take actions fastly and make improvements to engage more users.

![Feature Troubleshooting](./feature-2-troubleshooting.gif)
[Video Link](https://www.youtube.com/watch?v=HpM4qua9tK0)

### Metrics

To think about metrics, I like to think about questions. Here I could ask: 
- How builders are increasing the good metrics and decreasing the bad ones affecting their users?
- How can builders understand what they have to change to make their products better and offer a delightful user experience to their users?

These questions can help to understand which input and output metrics are important for product success. For general context I would like to watch the following metrics: 
- Users activation time. How long builders take to perform a key growth metric at Fullstory? The key metric can be, for example, a number of user sessions watched. 
- Frequency. How many times per week, builders come back and use Fullstory?

These metrics can tell us how relevant the product is for builders. But we need to identify how the features above mentioned are relevant for the product, individually.

Looking to __Feature 1__ specifically, I would like to monitor:
- Which percentage of sessions, builders prefer to use the __search panel__ as a starting point?

Considering __Feature 2__: 
- How often builders interact with the troubleshooting panel while replaying user sessions?

Thinking about this feature, it’s a good idea to tag the developers in the team because this can be the only feature used by them. 

## Could be better

Fullstory groups users by segments. It allows builders to look just for a specific group of users sharing the same characteristics. When we use a specific filter searching, we can save this as a segment. The problem is that many times I’m guessing about which behaviors and events to track with a stake in the customer’s success. The reverse sounds more interesting for me.  Why not ask:
- What my best users are doing?
- What are the main barriers to users completing key activities in my product?

## Feature planning: Smart Segments

Many companies don't have the resources to do data analytics appropriately. And many teams face the same problems building products in similar contexts. So, why not try to automate part of the job and help their customers achieve success?

My approach to solving this problem is to build an engine to analyze information and to define segments by itself. This way, Fullstory can help builders to look to the right user groups and focus to help them complete the expected behaviors. 
An additional idea is to build a simple, straight to the point timeline to understand typical behaviors from these groups, how they perform actions, and when exactly. Using this resumed information, builders can, for example, plan campaigns to engage users in the right moment, and help them break the barriers to get more active users. 

![feature Proposal Smart Segments](./feature-proposal-smart-segments.png)

To build a feature like this can be challenging. How hard can it be to define rules and predictive models to effectively suggest segments? I think we can start asking builders what kind of product they are building and automatically define key actions based in a generic product context. We can start asking simple questions, like:
What is the success of your product?
- Users use it every day.
- Users accomplish a purchase.
- Users submit a form.

Starting simple can be decisive to execute this feature, learn from users, and iterate fast. We can implement a simple decision model to help classify user groups and allow for builders to change these segments and help us improve our classifications rules.

If the feature proves itself valuable to users, we can make it better and apply better methods using machine learning techniques to accurate the suggestions. 

### Step-by-step

To successfully plan and build what I propose before, I would follow these steps:
- A 5-day Design Sprint to align the team and understand user needs.
- Recruit and establish a small beta group to help, giving us constant feedback in the design process. 
- Classify product types, typical behaviors and growth metrics to help builders auto-tracking successful users.
- Prototype fast and validate some assumptions.
- Define a roadmap based on time constraints.
- Run sprints and release gradually.
- Go live for a small portion of builders. 

### Metrics

Besides the general metrics for product success, the correct approach to test this feature is to compare with today’s alternatives in the platform.
- Time spent analyzing data and watching sessions replay by groups:
    - Users not clustered by segments.
    - Typical segments.
    - __Smart segments.__ (I expect this group will be the better one)
- Compare typical product metrics between builders who have access to the Smart Segments feature, and those who haven't.

## Final thoughts 

To finish my review, I just would like to share a vision and curiosity about a feature I would love to explore. :)

Tools like Google Optimize allow us to run A/B tests and compare alternatives to improve product variants. But to set up different A/B tests can be complex and hard to measure when using many variants. An alternative approach could be to train an AI model to do A/B tests on auto-pilot, and define which patterns and improvements can be done to generate a better interface for each user. During this product review, I recalled an interesting article I found a few months ago: [The Third Generation of Interfaces](https://www.interfaces3.com/)

Probably, soon we will customize interfaces and experiences to evolve and change according to each user’s specific needs. And this is going to be a big shift in the way of how we design and build software.