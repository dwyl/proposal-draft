# Communications Platform *Proposal* (*draft*)

![messaging-ios-apps](https://cloud.githubusercontent.com/assets/194400/10747146/d153f7ae-7c49-11e5-8899-72ae80fb0da6.png)

## Why?

**Team communication** ***pain*** is a ***real problem***
*many* people face; the loss of personal productivity
and revenue from ineffective systems is felt *universally*.
We plan to solve the problem by implementing
a *light-weight*, *low-latency*, *simple* & *scalable* solution.

### Situation

**The Client** (a London-based Commodity Brokerage
  & Market Making Firm)
needs a way to *easily* and *securely* share
information both within their teams and
externally with clients based in several regions.

This is *currently* done by *manually* transcribing or copy-pasting data from price display terminals to a variety of internal & 3rd party messaging tools ranging from Microsoft Messenger / Skype to WeChat (*in Asia*). The *existing* process is both time-consuming and does not allow the broker's clients to act on the price data in a timely manor. Furthermore, given that the *current* process is *manual* it is subject to *occasional human error* which results
in lost revenue.

#### *Estimate* of Lost Revenue due to Inefficiency of *Current System*

A *rough estimate* of the ***wasted time*** for the current system is ***10 minutes per broker per day***.  
If the average Broker is paid £60 per hour,
we calculate ***£10 lost per broker per day***.  
If the firm has **100 brokers** its ***£1,000 per day lost***
due to having an *ineffective information sharing system*.

> *Therefore the* ***Payback Period*** *for undertaking this project*
(*to streamline the price communications*)  
*could be as low as* ***One Month*** *in the proposed scenario below*.

### *Proposed Solution*

The proposed solution is to build a *bespoke* information sharing application that will allow brokers to select precise data to be shared with their clients.

Our team has experience building real-time,
fault-tolerant & distributed systems
and understand *Risk* in Financial Services so we can meet any/all
requirements for data security, privacy and system integrity
for both internal & external audit compliance.

## *What*?

We propose to build the fastest way for brokers to
***securely share time-sensitive pricing data with clients***.

### *Highlights*

+ Mobile-first solution - *securely* share data from anywhere
+ Industry-leading Technology - no proprietary solutions or "vendor lock-in"
+ Ultra-low Latency - time-sensitive data should be sent as fast as possible so it can be acted upon.
+ End-to-End Encryption - data is always securely transmitted & stored
+ Built-in Analytics/Tracking - tie revenue to the exact data shared

### *Detail*

+ Display price spread, volume and timeframe for each commodity.
+ Allow broker to select a row or multiple rows of data to be shared.
+ When a row is selected automatically copy the pre-formatted data
to clip-board (*excluding*) supplier info so that it can be shared
with clients.
+ Role-based Access Controls prevent un-authorised people from viewing
sensitive data while still letting them see what is relevant to them.
+ Broker can define what data gets shared in settings definitions
+  ... *Additional requirements to be defined in future iterations*.


## *Who*?

### The Client

As a successful commodities brokers,
**Company XYZ** provides the latest/best prices to their clients
in a time-sensitive marketplace.
The communication system being used has inherent
inefficiencies and requires a refresh to keep up
with the demands of clients based in several geographic regions.

### *Implementation Team*

We are a *community* of people passionate about using technology to solve real problems.   
In addition to the ***London-based team***
we have people contributing *remotely* to our project(s) from Argentina, Australia, Brazil, Canada, China, Colombia, Estonia, New Zealand, Portugal, South Africa & USA
(*the list grows daily*).

![dwyl who](https://cloud.githubusercontent.com/assets/194400/10739317/9966f0ac-7c13-11e5-8ff1-3c1ffa78a401.png)


We have experience in the Finance, E-Commerce and Telecoms
which will be relevant to successfully delivering this project.

Each project we undertake is staffed by a small team of people
based in the same location as the client to ensure clear communication and rapid iteration. We augment this team with remote expertise as required e.g. to test our output or provide over-night code-review (*while A-Team sleeps*).

> We expect to have a **team of 5 people** (*London-based*) working on this project:
+ ***System Architect*** - defines the overall project
+ ***Scrum Master/Project Manager*** - tracks team progress, liaises with client on requirements and ensures features are *tested* when delivered.
+ ***User Interface Designer*** - ensures minimal responsive design to achieve the desired goal (*avoids complex/complicated UI*)
+ ***Developers*** - build the bulk of features as specified
in *close collaboration* with the client/end-users

## *How*?

![communications-platform-diagram-1](https://cloud.githubusercontent.com/assets/194400/10749631/8ca40020-7c64-11e5-8d75-8bf8cfd3fec3.png)


+ Industry-standard (*fast + encrypted*) messaging processing between data-centers.
+ Light-weight user interface components display latest prices/spread data in real-time.
+ HTML5 ClipboardEvent simplifies experience (*tap-to-copy data on mobile device*)


### How Long Will it Take to Build an *Initial Version*?

We estimate that it will take ***4 weeks*** (*20 working days*)
to build a ***Minimum Useable Product***.

#### Week 1 - Requirement Gathering & Analysis
+ Understanding & ***Documenting*** the ***Existing Systems*** being used.
  + Where does price/availability data come from?
  + Do we need to interact with an API? is it a stream or batched?
  + What is the existing latency? (*so we can demonstrate improvment*)
  + How much *time* are people *wasting* with inefficient systems?
+ ***Clarifying Requirements*** (*ensuring we are solving the underlying problem not just treating a symptom*)
+ ***Defining Acceptance Criteria*** (*what defines success for the project*?)
+ Creating the Development, Testing & Deployment **Environment**

#### Week 2 & 3 - Build Phase

+ Specify Unit + Acceptance Tests for initial features
+ Building initial features continuously delivering value to The Client.

#### Week 4 - Testing, Feedback & Iteration

+ Customer Testing and UI Improvements
+ Feedback collection for further development



## *When*?

As soon as terms agreed the team can be assembled.
(*Start date to be agreed*)


## Learning Opportunities

Team members working on this project can expect to learn:

+ Root-cause Analysis (*don't take the initial symptoms/problems as the only ones ... discover why the underlying issues exist*)
+ Client relationships + end-user perspective/understanding
+ Distributed + fault-tolerant real-time messaging architecture
capable of processing millions of messages per second.
+ Data Security, Encryption and Role-based Access Control
+ How to Scale a Node.js Application for Thousands of Concurrent Users
+ Light-weight User Interface Design
+ Testing on Multiple Devices
+ Continuous Integration & Deployment
