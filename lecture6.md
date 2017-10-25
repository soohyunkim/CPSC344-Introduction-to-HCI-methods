## Week6: Defining User Needs
Task Examples & Requirements
- probably going to be asked to write task examples on the midterm

## Task Examples

### Task Driven Design
- Double Diamond
- User Interface Design Process graph
- task centered view of process/project
    - Identification (pre-design) -> Requirements (finishing up pre-design) -> Conceptual Design (early design) -> Task walkthroughs (earliest evaluations of designs)

### Task Examples
- Definition: a __story__ about a _specific user_ performing a _specific task_ in as interface-independent way as possible
- includes a _persona_ and a _scene_ (persona + scene)
    - persona:
        - must haves: name, background, goals, needs/values, real data as input
        - could include: job titles, demographics, relationships, quote, pictures
    - scene:
        - must haves: setting (place, time, where action happens), action (problem, task, and set of subtasks the persona enacts), real data as input
        - could include: artifacts/objects, setting/environment details, multiple characters

1. Identification
    - contact real ppl who will be potential users of the system 
        - specific end users
        - prototypical categories & extremes
    - spend time with them discussing how system might fit in 
        - who would be willing to talk to you about this?
        - who will actually buy/use system if no one is interested
    - learn about user's tasks (and potentially _model_ with task analysis
    - __task examples__ articulate __concrete, detailed examples__ of tasks they perform or want to perform that your system should support
        - routine
        - infrequent but important
        - infrequent and incidental
2. Test design using Task Examples
    - develop _designs_ to fit specific users and tasks
    - use task examples to:
        - make design candidates concrete and debug them
        - consider how design features work together to help a person accomplish real work
        - consider the real world contexts of real users
    - _Scenarios_ show how each task is handled by design
        - what the user would see/do step-by-step when performing the task 
        - task example + design = "scenario"
        - scenario: design-specific
        - task example is design-independent
3. Walk through evaluations

### Good task examples
- describe a complete job 
- say what the user _wants_ to do, but does _not_ say _how_ they would do it
    - no speficic assumptions about the interface
    - can be used to compare differetn design alternatives in a fair way
- are very __specific__
    - says _exactly_ what the user wants to do
    - specifies actual inputs the user would eventually want
    - tasks can be hierarchical 
- describe a __complete job__
    - not just a _list_ of simple independent goals
    - forces designer to consider _how different steps will work together_
- say __who__ the users are
    - design success strongly influenced by what users know
    - use real-ish names
    - reflect real interests of real users
    - helps find tasks that illustrate functionality in a person's real work context 
- as a set, identify a broad coverage of users and task types
    - typical "expected" user: typical routine tasks
    - occasional but important user: infrequent but important tasks
    - the unusual user: unexpected or odd tasks
- are __evaluated__ (final and very important step)
    - circulate descriptions to users, and rewrite if needed
        - ask users for (omissions, corrections,clarifications, suggestions)
- Grocery List Task Example (written down)

### Limitations of task-centered design
- Tasks almost always embody a process even if they are not specific to a specific technological implementation
    - may not encourage consideration of alternate ways to do tasks
    - may be hard to produce 'pure' system or 'process' independent tasks

## Requirements and Metrics
- Describe the problem we are solving
    - what is required to fix it
    - arrive systematically at a solution approach

### What are __requirements__?
- __functional__ requirements: what the interface must do 
    - usefulness - scope, features, etc
    - NOT usability!!
        - meeting usability requirements will/should often influence functional requirements
- __non-functional__ requirements: _many_ kinds
    - usually constraints that development must live in
        - delivery time, max cost, delivery platform ,supportability, sustainability
        - usability/UX: what it should be like to use -- a primary focus of HCI design
- All clear, specific, defined in a __MEASURABLE__ way

- Can requirements change?
    - requirements should be _stable_ (if based on good data)
    - but not _rigid_
        - they may shift overtime (as design reality dictates what is possible/feasible given other constraints)

### Three steps to requirements
1. Identify and model the __human activity__
    - Situation of concern: context for the design problem (course of action that will result in a _change_ that resolves the situation is required)
    - __Task objects__: dependencies among tasks
        - "task objects" are resources required by tasks
            - artifacts, people, other processes, equipment of tasks
        - most tasks focus on a single resource
            - task cannot be accomplished without the resource
            - once resource is available, the task can be completed
        - processes have multiple dependencies
            - focus shifts as different tasks are performed
            - activity is suspended when resources are not available
2. Identify __all__ the __users & other stakeholders__
    - General human needs (eg. physical and cognitive abilities, social/cultural environments, use models of human behaviour to test ideas)
    - Specific human needs (eg. diff. skills and requirements, responsibilities and authority in organizations, level of training, specific access to tools and resources)
3. Set __Focus__ and __levels of support__
    - Quantitative metrics (what happens when ppl user the interface)
        - Performance (speed, error rate)
        - Learning to use the system (eg. how much time will it take, how much background is required, etc), Satisfaction (subjective)
    - Qualitative metrics (why it happened)
    - Choice of usability metrics affects the solution
        - prioritize most important facets based on goals
        - establish metrics by deciding on what constitutes success
