# User Story: a Placeholder for a Conversation

### Key Takeaways:
* A user story is a placeholder for a conversation, not simply a ticket describing a task.
* Conversation is essential to an effective software development process and the key points 
where it is easy to inject conversation. 
* Recent trends take us away from these valuable conversations and put emphasis on 
documentation for the wrong reasons.
* User stories are great ways to encourage these conversations and share understanding.
* There are techniques to slice stories to avoid task-based tickets and maintain cohesiveness.


In this article, I'd like to discuss user stories and the recent trends in their transition 
towards task-based tickets, highlighting some areas of improvement. Some of the key elements 
of user stories are being lost but there are some easy ways to restore their value. I think 
the best way to do this is to go back to the origins of user stories to understand where they 
came from.

## What are User Stories?
A user story is a description of a discrete piece of user value written from the perspective 
of the user and often includes the user’s motivations and problems they are experiencing. It 
includes how a feature will provide value to the user.

## What are Tickets?
In contrast, tickets represent the work to be completed. A ticket is a task. Because they 
focus on the work, they are often aligned with the individuals or teams doing the work.

For example, if the work involves frontend and backend work, there will often be tickets 
created for each of those pieces. If an individual is responsible for a certain area of the 
code, a ticket may be created just for that area and assigned to that individual.

The idea of a ticket is to be efficient from the workers’ perspective and to enumerate a 
solution upfront to save time during implementation.

## The Story of User Stories
The software development process hasn’t always existed the way it does today. Before the 
advent of Agile, the Waterfall process was widely in use. Waterfall is a sequential process 
of steps for developing a product, beginning with analysis and requirements gathering, 
followed by software development and ending with testing and release (oversimplified for 
this discussion).

The early phases consisting of analysis and requirements gathering produced (often large) 
specification documents detailing the exact system requirements consisting of many detailed 
statements such as "The system shall store the customer’s credit card details." What often 
happened is that the requirements were "met" but the product didn’t deliver on its promised 
value.

The process of breaking down a user’s needs into detailed requirements was extremely lossy -- 
important details were lost along the way. They also interweaved "solution" details, 
resulting in lengthy and convoluted documents that hindered creativity and limited the 
exploration of innovative solutions.

Then Agile and XP came along. A key tenant of XP is to have an on-site user or to "sit with 
the customer". This makes it easy to understand the customer through storytelling. Agile 
attempts to solve the requirements document problem by introducing user stories to reduce 
wasted time and effort -- just enough written details are included to understand the story.

This focus on the user eliminates the need for extensive requirement definition. With user 
stories, we embrace flexibility in our roadmap, avoiding the sunk cost fallacy. We might 
find we’re going in the wrong direction or run into an unforeseen technical obstacle. By 
defining just enough to get going, we can keep our options open and avoid overly investing 
in a direction that may change quickly due to changes in the business.

Instead of investing a lot of time documenting requirements, user stories allow the sharing 
of knowledge to happen right when it’s needed -- during the story. We resolve ambiguities 
through conversations, ensuring a shared understanding of desired outcomes.

Note that this doesn’t mean we eschew all documentation, but it is important to remember 
the Agile Manifesto’s value of "Working software over comprehensive documentation". 
Documentation may be a requirement in certain situations so write down what is necessary. 
But remember the primary goal of conversation is shared understanding and working software, 
not the generation of documentation.

### The Conversation
Back in the day, Ron Jeffries described stories as being composed of "3 C’s":
* (Card - This is a brief description that was originally (and often still is) written on 
an index card. The small size of the card is intentional - only a brief description can fit!
The beauty of this is that it leads nicely into the next C ...)

* Conversation - Ron says it best: "The requirement itself is communicated from customer 
to programmers through conversation: an exchange of thoughts, opinions, and feelings."

* Confirmation - Originally described as the acceptance tests done by the user, 
confirmation may now include other types of testing as appropriate to confirm the story 
delivers what is needed.

The parts I want to draw your attention to are the Card and Conversation. Notice that the 
Card is the documented portion and it is very small. As Alistair Cockburn said in 1998, 
"A user story is a promise for a conversation."

What does the conversation look like? It’s the story of the user told from the user’s 
perspective. It is not a one-way presentation or list of requirements. It is a 
collaborative discussion that encourages questions and takes a meandering path. It includes 
what a user’s motivation is, what problems they have, and how they currently solve it. It 
helps develop compassion for the user and helps understand their point of view.

Conversations occur not just one time, but over the period of time it takes to create, 
estimate, implement and test the story. Having the conversation close to the time of the 
user story also avoids losing the big picture and forgetting the details during 
implementation.

Picture a conversation between a product owner and a developer that starts with the product 
owner describing a business problem they’d like to solve. The developer asks the product 
owner questions to fully understand the problem. They work together to form a common 
language, refine the vision, and break down the solution into smaller pieces that each 
deliver incremental value.

As the developer begins the work, the conversations continue as finer grained details 
emerge. The product owner may use these new learnings to re-prioritize future stories or to 
adjust scope. Through conversations between product and development exciting solutions 
emerge that are simpler to use, faster to implement, and more elegant overall.

## They’re Stories, not Tickets

Unfortunately, it’s becoming increasingly rare for teams to operate this way. The 
conversations have turned into specifications of product features. Stories are being 
replaced by tickets and the work becomes directed to developers. We’ve reduced or 
eliminated the Conversation, and over-focused on the Card. The Card has become mini-specs 
rather than a headline and a couple sentences.

Why are teams moving away from Stories and the conversations that are part of them?

One potentially contributing factor may be the trend since Covid towards more asynchronous 
and remote work.

With the more distributed nature of teams across time zones and geographical regions, the 
desire for independent work has increased. People want flexibility in their working hours 
and location. People working in different locations and time zones increases the challenge 
of synchronous communication which leads to asynchronous communication, usually in a written 
form.

This has led to the use of documentation as the main form of communication. This 
documentation may come in several forms: fully detailed requirements documents, long Slack 
threads, Google docs, Notion pages or even a long library of Zoom recordings. These 
asynchronous conversations can go on for days or weeks when a quick video call could clarify 
a question.

The practice of documenting every conversation is counterproductive. Instead of 
increasing communication, the signal of important details is lost in the noise in the 
abundance of documentation and recordings. The burden of ensuring the accuracy of all 
documentation can become a significant time drain.

Each form of documentation should have a purpose. Are you writing this down to share with 
others not in the meeting? Then perhaps documenting just the outcome is appropriate. Has a 
decision just been made that might be counter-intuitive or confusing later? Writing down the 
why of the decision can be enough.

Consider other forms of documentation: executable documentation is amazing because it can 
never get out of date. Code and tests can be used to clarify how the software functions and 
because it is the system, it is always accurate. There are creative ways to make code 
self-documenting. Extracting hard coded values to a readable configuration can help easily 
answer questions about how a system works. BDD (Behavior Driven Development) testing 
frameworks can also be used as executable documentation.

At times the act of writing something down is beneficial in itself: it helps clarify 
understanding and commit details to memory. Drawings and diagrams are an invaluable 
tool for communicating a vision. Make it easy to write down and throw away when its purpose 
has been achieved.

Documentation serves a useful purpose but should not replace conversations. Documentation 
may also be a valid desired outcome in addition to working software, produced with or after 
the code has been written. Document just enough to achieve your goal.

What are the impacts of replacing conversations with documentation?

With documentation comes an increase in the chance for misunderstanding and errors. This in 
turn leads to developers wanting even more detailed documentation to eliminate room for 
errors.

Collaboration between developers becomes more challenging when working asynchronously. 
Developers want more independent work and will often split work by layer.

We try to save time by writing down more details, breaking the work into tasks, and even 
assigning them to individuals. Tickets promote tasks as if they were independent work items.

Delivering a single capability may require several teams to deliver pieces. Planning 
becomes more complicated when fitting these pieces together.

## The Case for Stories and Conversations

This all leads to what previously was a coherent user story becoming a list of tasks 
divided by technical layers and spread across multiple developers and teams. There may be 
no one focused on ensuring the entire feature works together. The cohesive story that tied 
together the tickets has been lost, as has the full picture of the desired outcome.

When we move from stories to tickets, we lose the opportunity to tell the story. The story 
of the user provides context and breadth beyond just a ticket. Understanding the big picture 
allows for creative alternatives and problem solving. It’s a chance for individuals to:
* seek additional context
* better understand the work
* suggest improvements
* save time and money by preventing errors

Presenting work to developers as task-level tickets misses out on this conversation that 
comes from storytelling and creates tickets that are too isolated.


Let’s say the Product Owner is presenting a new feature to allow purchases by the user. When 
the feature is first introduced early in the ideation phase, a typical conversation would 
include the reason for the feature, the motivations of the user, and a general sense of what 
success looks like. Documentation at this point may not even look like a user story yet. A 
user journey map or some other way to convey the high-level vision may be appropriate.

Later, when the feature reaches the top of the priority list, Planning may include 
conversations about the best way to split the work into small, incremental pieces. 
Conversations at this point could help identify the highest value slice to work on first, or 
even possible de-scoping opportunities if the need should arise.

This is where the user story may first be created with only lightweight one-liners to 
indicate the slices. Some questions to ask here might include: "How will we determine 
when this feature is successful?" and "What is the minimum value required to release this to 
the user?" Stories may be split, removed, or re-prioritized.

At the point when work is ready to begin, this is the perfect opportunity to have a 
discussion about the details of the story. What credit card payment methods need to be 
supported? Any constraints that would prevent integration of a 3rd party payment processor? 
Fill in the user story with acceptance criteria and/or testing examples as needed. A few 
great questions to ask at this point are: "How will we know when this story is done?" and 
"How will we determine if this story is successful?"

Finally, when the work is ready for acceptance, one final conversation might be part of the 
transition into testing. What issues came up during implementation? What decisions were made 
that need confirmation or separate stories?

Of course conversations should occur whenever necessary, but these are some key points to 
consider.

There is a tangible negative impact to business value when work is split into tickets.

Think of each ticket as a piece to a puzzle that needs to be assembled fully before it 
reveals the whole picture. Each puzzle piece has to be placed in the right location and 
aligned correctly. All the pieces must be printed and cut perfectly ahead of time. All of 
the pieces must be in place before the whole is complete.

Some implications when applied to tickets:
* Each ticket often lacks the ability to be tested and deployed independently.
* Customers are unable to provide feedback on a ticket; they need the entire feature to see value and validate the direction.
* Each ticket is a mini-integration that may involve a handoff.
* Each handoff causes delays and context switching which slows down development.
* Bugs are more likely with so many integration points.

Software design includes a good bit of "discovery" of the system. The design is constantly 
evolving. When work is broken into tickets, it limits our ability to discover the system. 
This causes a fragmented codebase that is difficult to refactor, makes future development 
slower, and bugs more likely.

### User Story Templates

User story templates have widely been adopted as the prescriptive method to be more 
efficient, communicate clearly with engineers and leave nothing to chance.

Two widely adopted formats are Connextra and Gherkin:
* The Connextra format of "As a ... I want to ... So that ..." can be helpful to frame the motivation of the user.
** Appropriate Connextra usage includes specific user traits that help distinguish this user story from other similar ones for different types of users.
** Abuse of Connextra looks like every story starting exactly the same way with user types that aren’t useful to provide context. Or redundant  "I want ... So that": "I want to see a report so that I can see the report".

*The Gherkin format of "(Scenario), Given, When, Then" clarifies what the system should do in response to certain events and is useful for examples to specify examples of system inputs, triggers and expected outputs.
** Appropriate usage of Gherkin includes a few examples for acceptance criteria in addition to a general description of the story.
** Abuse of Gherkin can look like attempts to reword every story into this shape without specific examples.

Use a template if it proves useful in driving conversation or understanding the user story. 
But there is no magic recipe for success. The conversation is the key. Avoid the trap of 
overly specifying user stories in an attempt to bypass the need for conversation.

## Easy Fixes

Conversations should take place any time they are needed for clarity, but there are some 
key points during the software development process that are the most beneficial at which to 
apply conversations. An important note that these conversations may be in-person or virtual 
and do occur real-time.

#### Creation
At the very beginning of the product development process, a story about what problem is 
being solved is valuable. This is where the high-level Why of the work is shared and many 
questions are asked. Alternate solutions may be proposed. Product owners can help identify 
the most valuable areas to focus on and developers can point out the riskiest areas to 
deliver first.

#### Planning 
As the planning phase begins, problems are broken down into stories for estimation and 
prioritization. Developers can raise technical concerns pertaining to the implementation. 
For example, a feature that comes with a security concern could have a slightly different 
user experience that alleviates the security risk.

#### Delivery 
When developers start work on each story, it’s a great opportunity to review and discuss 
any changes that have occurred, the desired outcome of the story and ways to break down 
the work further. It’s also a great time for those deferred questions that didn’t previously 
affect the estimation but need a decision before implementation.

#### Acceptance
When development on an individual story is complete, there’s one final chance to touch base 
and create follow-up stories based on new learnings.

The diagram below outlines these stages and include useful prompts to help trigger each 
type of conversation: (insert photo here)

A technique to help shift the conversation in the right direction is to encourage Why and 
What questions and avoid How questions. Why questions take the conversation to a higher 
level and help share context and understanding of the desired outcome. How questions bring 
the conversation to a lower level and often get stuck in implementation details.

For example, a conversation about implementing a purchase feature in a system might include 
discussion of the different payment methods. A How question of "How do we show the user the 
payment options?" could lead to a discussion of the exact details of a form on the page that 
overly specifies placement location, size of text fields, etc.

These details often aren’t necessary to nail down before implementation and can anchor a 
solution prematurely. In contrast, a Why/What question of "What does the user want to 
accomplish by making a payment at this point in the flow?" Could provide useful information 
about goals of streamlining the checkout process or might even bring up alternatives of 
deferring payment until later to keep the user engaged. Perhaps it brings to light the 
option of implementing an integration to an external payment system instead of writing a 
custom one.

Answers to How questions provide important details but deferring them until the last 
responsible moment allows for more flexibility in the solution. If everyone is on the 
same page about the Why of the story, you increase the chance of success if later obstacles 
are encountered.

A note of caution! Asking Why could be perceived as a lack of trust. Use caution when 
phrasing the question, or stick to starting your question with What.

### Story Slicing
To avoid large features from being split into task-based tickets, there are few techniques 
to employ. The INVEST (Independent, Negotiable, Valuable, Estimable, Small, Testable) 
acronym can be used as a measure of well-sliced stories. Each letter in INVEST is a criteria 
of well defined stories:
* Independent stories can be prioritized independently so that the most user value can be delivered first (instead of focusing on the development tasks’ needs first).
* Negotiable indicates a collaborative working relationship amongst the team so that stories are not dictated, but arrived at together.
* Valuable stories deliver some value, ideally to a user, but there are other recipients of value as well.
* Estimable indicates a story has enough resolution for the team to arrive at a rough level of effort.
* Small encourages the smallest piece (that satisfies all of INVEST) to have short feedback loops.
* Testable indicates there is actionable criteria to measure the successful completion of a story.

Let’s walk through an example of splitting stories using the INVEST model.

A team is considering a story that everyone agrees is too large. During conversation, a 
possible slice of the story between the front-end work and the back-end work is rejected 
because it violates the I in INVEST. The front-end work couldn’t be delivered independently 
without the back-end work being completed. Reversing the order of the stories may solve this 
problem, but it’s not ideal as the team feels the back-end story alone isn’t valuable enough 
nor easily testable, violating the V and T in INVEST.

The team thinks more about how to slice the story vertically, like a piece of cake with a 
little bit of each layer in every slice. After discussion, they agree that there is one 
element on the form that is more complicated than the rest. They decide to split the story 
into two by moving the complicated text field into its own story. Now each story is a full 
vertical slice with a little bit of both front-end and back-end. Each story delivers a small 
increment of value to the user. They’ve accomplished independent, valuable, small and 
testable stories. By the nature of the conversation, they’ve proven the original stories to 
be negotiable and the new stories are more easily estimated.

There are a myriad of ways to slice a large feature and maintain the independence and value 
of each smaller user story. I’ve yet to see a better reference for making user stories 
useful than Paul Rayner’s Stories for Design and Delivery. See the section "Common patterns 
for splitting stories" as a quick reference for story splitting.

### Conclusion
I hope it was helpful to share the differences between user stories and tickets. A story is 
a placeholder for a conversation. And conversations can improve understanding and 
collaboration. Despite trends taking us away from stories and conversations, there are many 
different opportunities for these valuable conversations. Pausing for conversations at key 
points during the development process can be especially effective.

I found it interesting to revisit the history of user stories; so many of the underlying 
principles are still valuable. I hope we can avoid the pitfalls of the past of overly 
detailed technical specifications and instead use well defined user stories and 
conversations to help us create more valuable software.

Good luck and have fun!

# ChatGPT response

This comprehensive article discusses the importance of user stories in software development 
and the recent trend of transitioning towards task-based tickets. It emphasizes that user 
stories are placeholders for conversations rather than just descriptions of tasks, and these 
conversations are crucial for effective collaboration and understanding.

The article traces the evolution of software development processes from Waterfall to Agile 
and explains how user stories emerged as a way to focus on delivering value to users. It 
highlights the three components of a user story: Card, Conversation, and Confirmation, with 
a particular emphasis on the Conversation aspect, which involves collaborative discussions 
to understand user needs and desired outcomes.

However, the article points out that recent trends, such as remote work and asynchronous 
communication, have led to a shift towards more documentation-heavy approaches, which can 
undermine the value of conversations. It argues that over-specifying user stories as tickets 
can lead to a loss of context and hinder creativity and problem-solving.

The article provides practical suggestions for maintaining the focus on conversations 
throughout the software development process. It recommends having conversations at key 
stages, such as during the creation, planning, delivery, and acceptance of user stories. 
Additionally, it advocates for story slicing techniques to avoid creating overly large and 
task-focused tickets.

Overall, the article underscores the importance of conversations in software development and 
encourages teams to prioritize understanding user needs and collaborating effectively to 
deliver valuable software.
