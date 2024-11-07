## underpin  `to give support, strength, or a basic structure to something`
Observability doesn’t stop at the telemetry and analysis; it’s an organizational practice, similar to DevOps. 
In many ways, observability is the foundation of modern software development practices—it `underpins` everything we do, 
from continuous integration and deployment to chaos engineering, developer productivity, and more. 

## extrapolate `to guess or think about what might happen using information that is already known`
A big part of observing real systems involves identifying patterns of bad behavior and then `extrapolating` to figure out how certain patterns of transactions and resource consumption cause these patterns. 

## silo `a large, round tower on a farm for storing grain or winter food for cattle`
This is the primary problem with the traditional three pillars approach: these signals are all kept in separate data `silos`. This makes it impossible to automatically identify correlations between changing patterns in our transaction logs and changing patterns in our metrics. Instead, you end up with three separate browser tabs, and each one contains only a portion of what you need.

if your telemetry data is `siloed`, unstructured, and inconsistent, then the assistance computers can offer you will be very limited.

## instrumentation `the particular combination of musical instruments that are used to play a piece of music`
instrumentation is the process of adding observability code to a service or system. Broadly, there are two ways to perform this. The first is through a “white-box” approach that involves directly adding telemetry code to a service or library, and the second is a “black-box” approach that utilizes external agents or libraries to generate telemetry without requiring direct code changes. 

## fiendishly `extremely`
These tasks can be fiendishly difficult at scale

## staggering `very shocking and surprising`
the amount of money large enterprises spend on performing even simple tasks, such as enumerating the amount and criticality of various services, is staggering

## downsampling  `a data processing technique that reduces the resolution or granularity of data`
Traces can be transformed into other signals, such as metrics, allowing for downsampling of the raw data without losing key performance information

## ubiquitous `seeming to be everywhere`
Metrics are often the first port of call for developers trying to understand overall system health. They’re ubiquitous, fast, and inexpensive for what they do

## concomitantly `at the same time`
Fundamentally, the OpenTelemetry model seeks to unify this signal by enriching log statements with trace context and links to metrics and traces recorded concomitantly

## gamut  `a range of different things or people`
These semantics run the gamut from metadata (to represent resources such as server hostnames, IP addresses, or cloud regions) to specific naming conventions for HTTP routes, serverless execution environment information, and pub-sub messaging queue directions
## cardinality `the number of elements (= separate items) in a mathematical set`
There are two ways to manage attribute cardinality. The first is to use observability pipelines, views, and other tools to reduce the cardinality of metrics, traces, and logs as they’re emitted and processed

## masquerade `behaviour that is intended to prevent the truth about something unpleasant or not wanted from becoming known`
Masquerading is a special type of SNAT in which one computer rewrites packets to make them appear to come from itself

## stymie `to prevent something from happening or someone from achieving a purpose`
we are still stymied by a basic fact: software has to run on hardware

## Syntactic sugar  `In computer science, syntactic sugar is syntax within a programming language that is designed to make things easier to read or to express`

## Milieu `the people, physical, and social conditions and events that provide the environment in which someone acts or lives`
The Internet Milieu of the Twenty-first Century

## watershed  `an event or period that is important because it represents a big change in how people do or think about something`
The most obvious watershed event was the creation and subsequent intense commercialization of the World Wide Web starting in the early 1990s. 

## synergistically  `in a way that causes or involves synergy (= the combined power of working together that is greater than the power achieved by working separately)`
As we shall see, NAT can also be synergistically combined with firewalls to produce combination devices that have become the most popular types of routers used to connect end users, including home networks and small enterprises, to the Internet.

## tailor `someone whose job is to make, repair, and adjust clothes`

**tailored**
```
They prefer a tailored approach.
Tax havens increasingly aim to provide specific tailored benefits for users.
```

## brittle  `delicate and easily broken`
A very brittle type of NAT overloads not only addresses but also ports (called port overloading)
