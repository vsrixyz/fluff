---
title: Jobs to be done
date: 2022-09-14 15:35:22-07:00
date modified: 2022-09-20 22:29:34-07:00
---

# Jobs to be done

## TL;DR
Watch this 7 minute video for a story about McDonalds and milkshakes that explains Jobs to be Done (JBTD). <!-- .element: class="fragment" data-fragment-index="1" -->

For a deeper understanding of jobs theory, including a breakdown of key concepts come back to this deck after watching the video. <!-- .element: class="fragment" data-fragment-index="2" -->

[Clay Christensen: The Jobs to be Done (JBTD) Theory](https://www.youtube.com/watch?v=Stc0beAxavY) <!-- .element: class="fragment" data-fragment-index="3" -->


---

## Three concepts
 <!-- .slide: data-background="#ff0000" -->

- **Jobs to be done** (or JBTD) are your customer's goals. What they are trying to accomplish, avoid, maintain, or change.
- **Customer needs** are things (tasks, events, mindsets) that customer's need to solve to get their jobs done.
- A **Product** is what you build to solve customer needs (so they can get their jobs done.

Couldn't we call JBTD customer goals? Sure. They’re the same thing. This terminology comes from research by [Christensen](https://www.fullstory.com/blog/clayton-christensen-jobs-to-be-done-framework-product-development/) and [Ulwick](https://jobs-to-be-done.com/jobs-to-be-done-a-framework-for-customer-needs-c883cbf61c90).

---

## Concept #1: Jobs to be done

Jobs to be done are your customer's goals. What they are trying to accomplish, avoid, maintain, or change.

In Jobs Theory, customers "hire" **products** to solve **customer needs** so they can acheive their **jobs to be done**.

  ```js [1|2,3|4]
    let a = 1;
    let b = 2;
    let c = x => 1 + 2 + x;
    c(3);
    ```

---

## Concept #2: Customer needs

**Customer needs** are things (tasks, events, mindsets) that customer's need to solve to get their jobs done. Some customer needs are explicit, some are implied.

| Job to be done                     | Explicit need            | Implied need |
| ---------------------------------- | ------------------------ | ------------ |
| Establish a work-from-home station | A surface for work tasks | A stable object free of splinters and safety hazards             |

Customer needs must be agreed upon by everyone who makes products. This list includes:
design, engineering, product management, marketing, support, sales, and everybody else on the payroll.

---

## Concept #3: Product

> Upgrade your user, not your product. Value is less about stuff and more about what the stuff enables. Don't build better cameras, build better photographers.
> –Kathy Sierra

A **Product** is what you build to solve customer needs so customers can get their jobs done. Your product could be software, equipment, a service, a consumer packaged good, or even art. Customers will "hire" your **product** to solve specific **customer needs** related to some **job to be done**.

| Product                     | Job to be done                                       |
| --------------------------- | ---------------------------------------------------- |
| Customers hire **YNAB**        | to achieve **having enough money for a motorbike**       |
| Customers hire a **forklift**   | to achieve **a clear warehouse floor**                   |
| Customers hire **coaching**     | to achieve **feeling comfortable doing public speaking** |
| Customers hire **toothpaste**   | to achieve **a confident minty-fresh smile**                |
| Customers hire a **foreign film** |  to achieve **entertained teenagers on first dates**                                                     |

---

Jobs to be done should be product agnostic. That means, they have nothing to do with your product. In theory, customers could hire any number of products to acheive their jobs to be done.

| Product                     | Job to be done                                       |
| --------------------------- | ---------------------------------------------------- |
| Customers hire **an accountant**        | to achieve **having enough money for a motorbike**       |
| Customers hire a **4 burly dudes**   | to achieve **a clear warehouse floor**                   |
| Customers hire **rhinoplasty**     | to achieve **feeling comfortable doing public speaking** |
| Customers hire **a dentist**   | to achieve **a confident minty-fresh smile**                |
| Customers hire a **laser tag** |  to achieve **entertained teenagers on first dates**

---

## What if I don't want to use jobs to be done?

There are other approaches to figuring out what to build.

1. Customer requests
2. Sales requests
3. Feature requests
4. Technological capabilities

The following section describes the problems with each approach in ascending level of worse-ness.

### 1. Challenges with customer requests

Sometimes your customer will give you some one off feedback about what they need. And customers understand their needs better than anyone else, so this is a valuable opportunity, but there are some potential hazards with this info:

- Customers can't always articulate what they need because they don't have practice talking about it.
- Customers might not realize that their pain is caused by another [[Upstream thinking|upstream]] problem
- Customers aren't product experts: they can expect too much from your product or they might assume limits that aren't there

With jobs to be done, the process kicks off with open ended research that lets users talk at length about their needs and what is getting in their way. This is the most important part of the jobs to be done process.

---

### 2. Challenges with sales requests

Customers talking to sales have probably already been exposed to marketing offers that have shaped their vocabulary and perceptions about the problem

- "We need a CRM," "We need a multi-point jargon-based buzzword"

In actual fact, they may not know what they need at all (see above)

---

### 3. Challenges with feature requests

Feature requests aren't always bad. In many cases, it's possible to turn a feature request into a well-scoped, easy-to-build feature that vanquishes a clearly defined customer need. It's awesome when this happens.

Sometimes feature requests are a knee-jerk reaction to an acute need, and the final implementation misses the mark. 

| Feature request           | Acute need                 | Job to be done            |
| ------------------------- | -------------------------- | ------------------------- |
| A Porche 911              | Getting to school on time  | A passing grade in French |

It's certainly true that a faster car can solve this customer need of getting to school on time, and getting to school on time is useful for a passing grade, but the feature request misses the mark on the overall job to be done.

---

### 4. Challenges with technological capabilities

Customer, sales, and feature requests aren't ideal, but at least they come from the customer. Starting from technology ("What can be build?") is a bad move and leads to these outcomes.

- **You will never fail**! After all, if you don't know what customer needs to solve, you won't notice when you don't solve them them. No metrics, no failure. And of course, no success. You're building mostly for yourself.

- **You will build small**. There is no incentive to pursue risk when you're just building for yourself. Refining your product until the user can acheive their jobs to be done will increase the scope and timelines of your product. This is not a bad thing if you solve the problem.

* **You will learn less**. Imagine being given two options: "Paint a realistic flower" or "Paint something using all the paints in the box." The first provides a job to be done, and is of course, much harder. It requires technique. You might have to start over. But that's the only way to learn. It's messy. It's confusing. It's OK. The second is building based on technical capabilities.You simply do *stuff* and then say "tada." The result is a big brown blob that no one wants.

---

## OK I'm convinced how do we do it

![](https://i.imgur.com/pZyU7YV.png)



> On the product development timeline, jobs to be done sits fairly and squarely at the beginning of the research phase.
>A central tenet of **Jobs Theory**: customers do not buy products, they buy progress.
>Implementing Jobs Theory is simple, you're looking for customers who have recently hired your service or product. No more than 90 days is the standard.
>This is called a **switch event**.
>You need to reach out to the customers/users and conduct what is called a **switch interview**. These last about an hour and are not a typical, survey-style interview that are easy to plan for. They're reactive, investigatory style interviews that are detail hungry. You can listen to [the mattress interview](http://jobstobedone.org/radio/the-mattress-interview-part-one/) for a better grasp of what these kinds of interviews are like.
>The primary things you're looking for during switch interviews are the forces pushing and pulling at the customer from first thought through to actioning a switch event, such as hiring another product or service to get a job done in an improved way or more cost effectively or whatever else.
>You're also looking for emotional forces involved in their decision making.
>You plot these emotional and functional forces on a **switch timeline** and eventually, after conducting a number of switch Interviews, **job stories** begin to emerge. When you're confident that you have identified a job, and its associated forces, you're in a position to collate this data into what is called a **job card**.
>Think of a job card as you would a persona. You now have data, in the form of jobs cards, that can inform your design decisions or help you to ideate and innovate.


---

## Quiz #1

Drill bits vs holes
	- Customers don't want [product], they want [jobs to be done]
	- Customers don't want [Google Maps], they want to get to their destination on time
	- Customers don't want [Spotify], they want to discover new music that they might like
	- Customers don't want [Apple News], they want to know what's happening in the world today
	- Customers don't want [Calculator], they want to know what 2399 x 929 is
	- Customers don't want [FaceTime], they want to have a face-to-face conversation
	- Customers don't want [Dictionary], they want to know the defintion of ka·o·lin
	- Customers don't want [Figma], they want to be able to visualize software design before it is rendered into code
	- Customers don't want [Miro], they want to be able to brainstorm at a distance
	- And so on