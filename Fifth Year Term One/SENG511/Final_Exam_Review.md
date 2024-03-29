# Final Exam Review

## Lecture 2

A project manager identifies project tasks and builds a work breakdown structure. They develop the project schedule and coordinate activities of team members and sub teams.

On the other hand, product manager is more on developing the project. This includes gathering and prioritizing product/customer requirements. Additionally, defining the product vision & working closely with engineering is a part of it.

A lot of projects fail because of poor project management. This includes bad planning and insufficient communication, ineffective management, and failure to follow proper methodologies.

There are four core entities of software projects:

- Intent - What is the project trying to achieve?
- Product - What is the outcome of the project?
- Work - How to build the targeted product?
- People - Who is available to perform that work?

Here are some types of lifecycle models:

1. Code and fix - Starts with an informal general product idea. You develop code until the product is ready, but no really order/plan in place.
2. V-Model - More similar to waterfall methodology.

## Lecture 3

There are different ways to classify software development.

They can be highly predictive in the way as follows:

- Requirements are specified during initiation and planning
- Risk and cost are controlled by detailed planning based on an in-depth analysis of requirements and constraints prior to development
- Key stakeholders are involved at scheduled milestones

They can also be highly adaptive:

- Requirements are elaborated at frequent intervals during software development
- Risk and cost controlled as requirements and constraints emerge
- Key stakeholders are continuously involved

Project management life cycle is a sequence of processes that includes the following:

- Scoping
- Planning
- Launching
- Monitoring and Controlling
- Closing

Oftentimes, what the client want is not necessarily what the client needs.

There's also the idea of the "imbalance of functionality usage", known as the pareto-principle. Almost two thirds of all features are almost never used. This implies

- Wasted development effort
- Increased maintenance effort
- Customers overwhelmed from user features

What are requirements?

A requirement is a desired end-state whose successful integration into the solution meets one or more needs and delivers specific, measurable, and incremental business value to the organization.
There are functional requirements and non-functional requirements (quality) requirements.

The following are the purposes of having a Minimum Viable Product (MVP):

- To allow the product to be deployed
- To target market opportunities
- To create a viable product for the customer
- To test the fundamental business hypothesis
- To meet needs of early adopters
- To gather feedback
- To accelerate sales to first customers

## Lecture 4

There are five functions of SPM (Software Project Management):

1. Planning - Establish future course of action at all levels of the organization
2. Organizing - Structure efforts that involve collaboration and communication
3. Staffing - Acquire, develop, and retain staff resources
4. Directing - Energize, motivate, and guide staff
5. Controlling - Activities conducted to determine whether or not progress is made according to the plan

There are several things to plan in a project.

1. Effort -> Effort Estimation
2. Time/Duration -> Time Management
3. Schedule -> Time Management
4. Resources -> Human Resource Management
5. Functionality/scope -> Product (release) planning
6. Quality -> Quality Management
7. Risks -> Risk management

There are several reasons why planning is so important.

- Planning reduces uncertainty
- Planning increases understanding
- Planning improves efficiency
- Planning is more important than the plan

What is the Work Breakdown Structure (WBS)? The Work Breakdown Structure (WBS) is a hierarchical description of all of the work that must be done to meet the needs of the client.

Here are some WBS completion criteria:

- Status and completion are measurable
- The activity is bounded
- The activity has a deliverable
- Time and cost can be estimated
- Activity duration is within acceptable limits
- Work assignments are independent

## Lecture 5

- Prioritization is an activity that rearranges items or activities in order of importance relative to each other.
- Prioritization of features, tasks, processes, defects, resources, modules, requirements.
- Feature prioritization: Selection and ranking of most valuable features from a set of candidates
- Multi-criteria decision-making. Sample criteria as below:
  - Value
  - Risk
  - Cost
  - Benefit
  - Difficulty
  - Volatility
  - Satisfaction
  - Dissatisfaction

There are several prioritization methods.

- Functional Approach
- AHP
- Kano Method

There are different stakeholders who can partake in prioritization processes.

- Management
- Customers
- Quality Assurance
- Competitors
- Board of Directors

In the functional approach, evaluations of alternative **x** in all criteria must be normalized in order to make them comparable. Then, each criterion is associated with a weight **w**. An aggregation function is used to obtain the global evaluation of alternative **x**. Basically we weigh everything against a certain criteria, give that criteria a weight, and then aggregate all the values.

The other process is called Analytics Hierarchy Process (AHP). In this process, you decompose the goal into a hierarchy of criteria and sub-criteria. Pair-wise comparison is used to determine relative weights of criteria, sub-criteria, as well as the evaluations of alternatives. Weights or priorities are not arbitrarily assigned.

In this scenario of AHP, you need to do matrix multiplication. Each stakeholder/criteria has their own weight - and we match it against scores against each requirement. In the end, we get a score against each requirement while taking into consideration all the criteria.

The Kano method revolves around the fact that satisfaction does not necessarily mean dissatisfaction. There's the functional form of the question (positive) and the dysfunctional form of the question (negative). There are several categories of the Kano method:

- Must be (M): The prerequisite features that the user assumed to be granted
- One dimensional (O): The fulfillment of these features will increment the degree of customer satisfaction
- Attractive (A): These features are not explicitly requested
- Indifferent (I): The customer feels indifferent towards the availability or unavailability of these features
- Reverse (R): Stated that the customer not only does not want this feature but even expected the feature not to be in the product
- Questionable (Q): This category is the indicator of a problem in the phrasing of the question or understanding the question

## Lecture 6

The number of planning releases for increment development always goes up the moment we just have a major release coming out.

In a software product, a feature is a set of logically related requirements that provide a capability to the user and enable the satisfaction of business objectives. The way we select criteria for feature selection is through the following:

- Customer satisfaction
- Customer dissatisfaction
- Risk of implementation
- Risk of acceptance
- Financial value
- Cost
- Time to market
- Volatility
- Frequency of use
- Ease of use

There are eight types of feature dependencies:

- Coupling - They both need to be done together
- Either or - You do either or
- At most one
- At least one
- Weak precedence - I think one can be done before other
- Strict precedence - One must be done before the other?
- Value dependency
- Effort dependency - Group by effort??

Also, there are times where the resource or budget will be constrained.

In terms of resource constraints, we can see resource class 1: A resource type r belongs to class 1 if the feature related consumption of the resource is limited to exactly the release in which the feature is offered. Resources of this class are called local based on its spending mode.
Resource class 2: A resource type r belongs in class 2 if the feature related consumption of the resource can be distributed across different release periods. Resources of this class are called global based on its spending mode.

The diversification principle is an idea that a single solution to a cognitive complex problem is less likely to reflect the actual problem when compared to a portfolio of qualified solutions being structurally diversified.

## Lecture 7

A project schedule is a plan that links the tasks to be done with resources that will do them. Oftentimes, they are represented using Gantt charts.

Some terminology:

- Critical path - The sequence of project activities which add up to the longest overall duration. The critical path determines the shortest time possible to complete the project. For each project, we determine the following:
  - Earliest Start Time (ES)
  - Earliest Finish Time (EF)
  - Latest start time (LS)
  - Latest finish time (LF)

These are the following dependency relationships between tasks:

- FS: B can only start after A has finished
- FF: B may finish not earlier than A has finished
- SS: B may not start earlier than A has started
- SF: B may finish not earlier than A has started

There are different paths through a network. There is a forward pass which is left to right and determines the early start and early finish. This is ES + duration = EF.

There is also the backward pass, which is right to left. This is the latest start and latest finish.

## Lecture 8

This lecture is about staffing.

It's important to assign tasks to human resources based on skill and productivity.

Since software is developed in teams, soft skills are very important. They complement hard skills, and additional soft skills refers to active listening, negotiating, conflict resolution, problem solving, reflection, critical thinking, ethics, and leadership.

Here are some examples of soft skills:

- Communication
- Self-motivation
- Leadership
- Responsibility
- Teamwork
- Problem solving
- Decisiveness
- Ability to work under pressure and time management
- Negotiation and conflict resolution

Here are some strategic positions in the communication network

- Between-ness centrality
- Reveals brokers and privileged actors in the information flow

Organizations which design systems are constrained to produce designs which are copies of the communication structures of these organizations (Conway's Law). System development is more of a communication problem than a technical problem.

## Lecture 9

Software measurement is the process by which values are assigned to attributes of entities in the real software world. A measure of an attribute associates a value to each entity, in such a way such that our knowledge/intuition about the attribute is not contradicted.

An entity may be an object or an event. Software measurement entities are the following:

- Processes - Any activity related to software development and/or maintenance - these can be at different levels of granularity
- Products - Any artefact produced or changed during the software development process
- Resources - People, hardware, or software needed for the processes

Here are examples of software metrics:

- Lines of code
- Number of linearly independent paths through a function
- Code churn - The number of lines that were modified, added, or deleted in a specific period of time

Here are examples of the measurement scales.

Ordinal Scale

1. It places the elements in an ordered classification scheme
2. Consists of classes that are ordered in respect to the attribute
3. Any mapping that preserves the ordering is acceptable

Interval Scale

1. It preserves orders like the ordinal scale
2. It preserves the differences but not in ratio
3. For example, like calendar time

Ratio Scale

1. It is a measurement mapping that preserves ordering, size of intervals, and the ratio between entities

## Lecture 10

All events or conditions that may occur in a project that have negative consequences are known as risks.

Here is some terminology:

- Risk Impact - Loss associated with risk
- Probability - CHances that an event will occur
- Risk Mitigation - Set of actions intended to reduce or eliminate the risk
- Risk Threshold - Maximum degree of risk that an organization is willing to take
- Risk plan - List of all risks that threaten a project, along with a mitigation plan

Here are some ways to identify risks

- Fishbone chart - A visual way to look at cause and effect.
- Monte-Carlo Simulation - Uses a representation or model of a system to analyze the expected behavior or performance of a system. Uses statistical analysis to provide guess on the distribution of results.
- Decision Tree - Is a map of possible outcomes of a series of related choices. A decision tree typically starts with a single node, which branches into possible outcomes. Outcomes lead to and branches out to other outcomes.
- Sensitivity analysis - The technique used to determine how variable values change when other changes. Basically change the model and observe the behavior.

## Lecture 11

Software estimation is the act of approximating the significance of a piece of software.

There are different ways for us to estimate software.

1. Estimation by analogy - In this scenario, a case is a former experience of a solved problem. A case base is a collection of such cases.
2. Empirical factor models - I think this is some sort of equation?
3. Function point analysis

## Lecture 12

Here are some key performance indicators:

- Estimate time to project completion
- Time to respond to user request
- Issues found in QA
- Issues found in code review

Six sigma is the idea of focusing on continuous improvement. It's based on the key underlying principles:

- Everything is a process
- All processes have inherent variability
- Data is used to understand variation

## Lecture 15

The basic concept of system dynamics is systems thinking. This is characterized by the following:

- Thinking in cause-effect mechanisms
- Considering the multi-casual conjunctions
- Taking feedback into account
- Considering the dynamic complexity

What-If analysis is the following:

- Investigation of the impact of changing parameters
- Based on optimization and simulation methods
- Assumption: Conceptual models are known and fixed

## Lecture 16

The Capability Maturity Model (CMM) - FIrst process assessment methodology. It provides a roadmap for organizational software process improvements.
