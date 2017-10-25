## Week4: Mental Models, Human Abilities, Cognition

### Mental models & Cognitive Frameworks
- Why look at __cognition__?
    - Part of doing good design is understanding how people __reason__ and __react__ to interface experiences 
    - __cognitive frameworks__ helps us do this
        - theoretical models that provide __predictive__ and __explanatory__ power for understanding user behaviour 
        - based on theories of cognition
    - __internal frameworks__: about the mental process inside users head 
        - eg. mental model
    - __external frameworks__: account for interactions with technologies, environment, context 
Define __Mental Models__ and describe their characteristics (LG)
- Give examples of how a mental model can be acquired
- __Mental Models__
    - ppl form internal, mental models of themselves and of the things which they are interacting
    - ppl use mental models to 
        - reason about a system
        - figure out what to do when things go wrong
    - characteristics
        - incomplete
        - constantly evolving
        - not accurate representation (contains errors/ uncertainty measures)
        - provide a simple representation of a complex phenomena
        - can be represented by a set of _if-then-else_ rules
    - __mental models: something that user has (forms)__
        - users "__see__" the system through mental models
        - users __rely__ on mental models during usage
        - there are various __forms__ of mental models
        - mental models can __support__ users' interaction
    - conceptual models and conceptual design: what the __designer__ does to foster good mental model formation by the user 
        - design concepts all inform a user's mental model 
        - eg. scissors: object that helps form a mental model
            - affordance: holes for something to be inserted 
            - constraints: big hole for several fingers, small hole for thumb 
            - mapping: holes-for-fingers suggested, constrained by appearance
            - positive transfer and cultural idioms: learnt when young, constraint mechanism 
            - mental model: physical object implies how the operating parts work
                - reasonable mental model can be formed by looking at/ holding the object
    - Acquiring mental models: done by the __user__
        - during system usage, user's own activity leads to a mental model
            - explanatory theory is developed by the user
            - often used to predict future behaviour of the system
        - observing others using the system
            - casual observation of others working
            - asking someone else to "do this for me"
            - formal training sessions
        - reading about a system
            - documentation, help screens, "for Dummies" books
    - Object that hinders mental model formation: eg. "old style" digital watch
        - mental model must be _taught_ or learned by trial/error
Explain what __Norman's 7 stage model__ is good for (LG)
- Models are often "runnable"
    - includes notion of __causality__
    - used for __explanation__: to understand why the system responded as it did, _interpretation_ in Norman's model
    - used for __prediction__: to select an appropriate action, _intention_ in Norman's model
- __Norman's seven stage model__
Use gulf/stages to analyze interactions with a system 
    - Gulf of execution ->
    1. Establish goals
        - what do I want the system to do next?
    2. Form intention to act
        - what can I do next?
        - what if I do this?
    3. Decide on sequence of actions
        - to do it, I'll do this then this.
    4. Execute the action sequence
    - "the difference between the intentions and allowable actions"
    - The world ->
    - "the difference between actual system state and user's understanding"
    - Gulf of Evaluation ->
    5. Perceive the state of the world 
        - what will I see as a result?
    6. Interpret perceived state
        - what am I now seeing?
    7. Evaluate system w.r.t. goals
        - what did the system just do?
        - after: what did I do to make the system do that?
- Norman's seven stage model is good for...
    - internal framework: best for __exploratory learning__
    - less applicable to highly learned, semiautomatic behaviour

Be able to identify a mismatch in mental models (LG)
- __misconceptions__ happen when user's model differs in critical ways from how the system actually works 
- Give examples of situations or interfaces where mismatch occurs
    - "more is more" belief about interactions
        - high oven temp makes oven heat faster
        - pressing walk button repeatedly will make light change faster
    - folk theories and remedies for computing
        - reboot when computer "gets slow"
        - reboot computer to make projector work
- Mismatch, why does it happen?
    - sometimes, a poor model is fostered
        eg. Norman's fridge

Explain the difference between __internal and external cognitive frameworks__ (LG)
- Information processing: another way of thinking about internal cognition
    - ordered processing stages (with input/output)
    - useful for making predictions, identifying bottlenecks
    - human processor model (combines information processing with perceptual senses for input + output)
- Give examples of the types of factors or representations that could be important when analyzing distributed/external cognition
    - __External cognition__: the use of _external world_ to achieve cognition (use external representations to work with your internal representations)
        - external cognition frameworks is concerned with how _representations and factors in environment help/hinder cognition_
    - __Distributed cognition__: the idea that cognition happens _across_ individuals, artifacts, and time, is _embodied_
    - __Embodied interaction__: concerned with how someone's experience of the world and the meaning they create is shaped through physical/social interactions
- Give examples of __external representatons__ that help with memory load reduction, computational offloading and cognitive tracing 
    - Benefits of external representations
        - externeralizing info is very helpful for _remembering_
        - _computational offloading_: using tools and devices to carry out computations and other tasks 
            - eg. doing math problems on paper -> allows you to see the change, come back to it later, share with others
    - modification: reflecting changes or intention by modifying external representations by: annotation, cognifive tracing
        - _cognitive tracing_: manipulating objects into new orders and structures
    - Why do we use external representations?
        - often used _naturally_
        - can often be set up in very personal ways
    - Downsides to using external representations
        - ppl may start to ignore them when reminders are too frequent

### Human Abilities: Memory and Perception
__List__ and __describe__ models we have of human abilities (cognitive resources and memory, sensory processing)
- Modular model of mind - simplest (_serial_ aspect of the pipeline)
    - 3 stage model of human information processing
    - processing time: associated with each block
    - function happen in neurologically separate parts of brain, connected by electrical pathways
    - attention provides backwards pathway
    - PERCEPTION (sensory) -> DECISION (cognition) -> RESPONSE (motor)
- __Perception & action subsystems__
    - _input (perception modalities)_: 
        - _visual_ subsystem for what we see
        - _echoic_ subsystem for what we hear
        - _haptic_ subsystem for what we feel through touch
    - _output (action)_
        - _motor_ subsystem for how we move
            - _vocal (articulartory)_ subsystem for what we speak
- __Analogies to a computer system__
    - perception, audition, motor control as __system I/O__
        - each has associated memory ("cache")
        - limits on input speed ("sample rate") and throughput capacity
    - cognition = CPU
        - includes multi-level main memory
        - multithreading?!?! 
- The Memory pipeline: __stage theory__
    - working memory is small (temp. storage: decay, displacement)
    - maintenance rehearsal
        - role repetition
        - information must be meaningful to learn information well
    - answer to problem is organization
    - Human memory: __types__
        - Model Human Processor(MHP): PERCEPTION -> MEMORY -> COGNITION
        - Perceptual Processors -> Visual, Auditory, Haptic Stores -> WOrking Memory -> Long Term Memory
        - _Sensory Memory_: 
            - buffers: iconic(visual), echoic(auditory), haptic(touch)
            - allowed into short-term memory by _attention_ (filtering)
        - _Working Memory_: short-term
            - rapid access and decay
            - limited capacity
            - "flush" when finished with a task
            - move into long-term via conscious _rehearsal_
        - _Long Term Memory_: slower, larger
            - virtually unlimited capacity
            - slower access time with little decay
            - access: complicated operation that depends on recent past
            - causes for not remembering an item (forgetting)?
                - never stored (encoding failure)
                - gone from storage (storage failure)
                - can't get out of storage (retrieval failure)
                - interferance model of forgetting: one item reduces the ability to retrieve another
                    - forward (proactive) interference (3)
                    - backward (retroactive interferance (3 & 2)
        - Attention: _process_ of excitation and inhibition
Describe implications for design that results from these models, and that consider both _visual_ and _physical_ attributes
- Example 1: Change blindness
    - Images will blink/flicker, will change with each blink
    - Vision system: is more like _touch_
        - model is built up serially (over time)
- Example 2: Stimulus Response (S-R) compatibility
    - task difficulty determined in part by:
        - the particular sets of stimuli and response used
        - OR, the way in which individual stimuli and responses are paired with each other
    - Going through colours (written in different coloured texts)
    - spatial pairing, directional, limb to limb, sensory/motor channels
- Example 3: Perceptual Causality
    - How soon must red ball move after cue ball is reached?
    - Two distinct stimuli can fuse if the first event appears to _cause_ the other
    - Events must still occur in the same perceptual cycle
    - eg1. lip synch: is the voice really coming from that person?
    - eg2. touchscreen button: did my touch really make that click?
    - _Perceptual fusion_: stimuli that occur within one perceptual processing cycle _fuse_ into a single percept 
- Our initial perception has many limitations
    - _conveyance of info_ from perceptual to cognitive centers is constricted
    - _attention and external factors_ are central to what we finally "perceive"
    - Our "mental image" of a scene, object or situation is a _constructed model_
    - ignoring roles of perception and attention can cause problems during interface design and testing

### Translate Models into Implications for Design
Give __examples__ of interface features that illustrate these implications; critique interfaces using them

Give __examples__ of impairments and individual differences that impact human abilities (visual, motor, cognitive, etc)
- Visual cues
    - visual proximity and separation: _whtiespace_ to indicate grouping
    - visual differentiation: vary the visual characteristics of groups to make them distinctive
    - visual progression: rely on visual and cognitive cues to guide order in which users perceive info
    - support/impede finding and seeing
- Physical (touch) attributes
    - physical cues: shape (eg. remote controller - fit to hand, location of controls, which end is active, button findability/purpose)
        - when it can change, why is it changing?
    - findability and status feedback
        - spatial stability (stays in the same place, muscle memory), physical constraints (allow to move only in acceptable way), physical feedback (engagement, completion)
- Individual differences and impairments
    - accomodate diversity: human abilities are different
    - limitations in these abilities afford performance 
        - abilities include: short-term memory, long-term memory & learning, problem solving, decision making, attention & set (scope of concern), search & scanning, time perception
    - kinds of human diversity to accomodate:
        - physical abilities (ergonomics)
        - cognitive & perceptual abilities 
        - personality differences (eg. extroversion VS introversion, sensing VS intutition, perceptive VS judging, feeling VS thinking)
        - cultural & internatinal origins
        - disabilities
    - ex. older adults: aging often comes with a decrease of abilities in
        - visual functioning, attention, working memory, learning
- Human capabilities dictate that we _perceive_, _remember_, and _control_ things in particular ways
    - How design should take this into account depends on task context and goals 
