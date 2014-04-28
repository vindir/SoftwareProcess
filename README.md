## Requirements: Gathering and Sharing


### The Basic Idea:
* Every new customer engagement begins with an overview document and a brown cow model (BCM) document.  
* The overview document is a living document that gets updated every with every project iteration
* A BCM document is created for every project iteration with a customer and acts as the intro for anyone who needs an entry point or 1000-foot view into either the current or any past projects with a customer.
* The person who is going to create the design for a project becomes involved at the requirements gathering stage.  Any later and they'll never be as effective as possible.
* After every interaction, whether via phone; in-person; or otherwise, pivotal is updated with any new information immediately while it's fresh.


### Bonus Wins:
* For every project we should understand and make use of at least the two primary requirement types:
  * Functional - things the software must do
  * Non-functional - qualities it must have
* In addition to making the best use of the requirement types, a distinction between "system design" and "system architecture" should be made and documented as well as possible given time constraints.
* A simple check-list should be made to tick off the maintenance chores of keeping the overview/BCD/etc documentation up to date and used at regular intervals.


## The Trifecta
The three layers of documentation below are possible to implement with minimal time investment, but provide a great deal more insight into our projects.  

### Overview Document

The overview document is something we can keep for every customer.  It can be easily kept in an internal repo in markdown format and is the first stop any time we begin actively working on a project or need a quick reference of the current "state of the world" for a customer.

An overview document:
  * Gives a basic description of the customer's company
  * Describes any technical implementation currently in place to solve their needs that we have insight into
  * Outlines any technology currently in use by the customer
  * Describes any architecture we're aware of and if possible links to visual documentation for further information


### Brown Cow Model:
Alongside the overview document a **new** Brown Cow Model should be implemented for every customer project that moves forward.  Whether we're working in ongoing sprints or in more spread out SOW style projects, we should keep a separate BCM for each iteration or SOW.  In addition to the existing template (pdf linked below) for how a BCM works, our BCM should begin with a succint description of the iteration and/or SOW goals that it is defining.

http://www.volere.co.uk/pdf%20files/howNowBrownCow.pdf

So the BCM is basically our 1000-foot view and a simple reference for snapshotting any given period of time as well as planning for the immediate future.  The brown cow model is taken from volere, but it's a good idea because it gives a very simply quantified visualization of current project state and the "what and how" of how a project will change for any given project phase.


### Requirements Documentation:
The requirements in this lifecycle concept aren't much changed from how they're laid out in pivotal or any agile tool today.  The basic idea of a requirement, or story in this case, is to break down each component need of a project.  The vital change with requirements handling here is to decide early who will be handling system design and architecture and make them a part of the requirements gathering process.

Overall, Requirements Should:
  * Define the boundaries of the system.
  * Define the inputs and outputs.
  * Provide an easy to understand description of the desired behavior of the system.
  * Be unambiguous.
  * Be black-box testable.
  * Be easy to understand.
  * Be written for any individual story as a core requirement rather than an implementation definition.

