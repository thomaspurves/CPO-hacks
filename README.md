# CPO-hacks
Practical hacks for leading product, particularly in Fintech. In no partucular order, just as I remember to collect them here.

## What does a CPO do
A Chief Product Officer (CPO) for a fintech company is responsible for managing the development and launch of financial products and services. They must ensure the product is compliant with regulations, meets customer needs, and generates revenue. This involves developing the product roadmap, managing the product team, conducting market research, collaborating with other departments, and setting product pricing. A CPO does all this by helping to shape culture, organizational structures (just the right amount of) effective process to enable not just their people, but all the dependant & partner organaizaiont orgs within the the company to be suceessful. Which, btw, is just about all of them. Lastly, it's about leading from the front. Leading from the front means being alsways ready to roll up sleeves and jump in hands-on to help with any challenge within and without of your team. Lastly you've got to absolutely pationate about your problem space and about solving those problemes for your current and future customers. 

## AI Product hacks

Focus of much of my attention right now so getting a special section

### Using openAI safely and confidentially
Remember that anything you put into a chatgpt prompt essentially becomes public and may violate company principles for leaking proprietry information. Instead you can use the API mode, a dedicated azure instance or a 3rdparty tool based on same that will be safer. OpenAI only keeps rights to (re)use your inputs on the consumer public-facing version of ChatGPT.

A couple of prompts I've run across that could be of value to a product team in daily work. Of course PMs using these kinds of prompts strictly as first drafts. Or better yet _after_ writing a spec or ticket asking GPT to write a similar ticket and then compare. The tool may give additional ideas or areas/gaps of requirements that are worth adding.

### AI and Finance resources
* [FinGPT: Open-source for Open-finance](https://github.com/AI4Finance-Foundation/FinGPT)
* [6.8Bn Market sizing estimate] (https://www.globenewswire.com/en/news-release/2023/04/03/2640032/0/en/Generative-AI-in-Fintech-Market-Size-to-Exceed-US-6-2-Bn-by-2032-Report-by-Market-us.html) - undoubtaly an underestimate

### Ticket Writing Prompts
"You will act as a consultant for tech product managers. Your primary function is to generate a user story and acceptance criteria, given a high level feature description. The user story should be catered to the specific mode of user interaction (e.g. web, mobile), using best-practice UX design guidelines. If you need additional details to provide a good answer, you will continue asking for more context until you have enough to make your user story. Ready to start?"

"As a product manager, I'd like ChatGPT to create Jira tickets for me in the context of a project focused on Enter software description. For each ticket, I will provide specific information about the bug or feature, and ChatGPT should include this context, along with any other relevant acceptance criteria. As more tickets are requested within the same chat, ChatGPT should remember the context of previous tickets to develop a stronger understanding of the platform over time. I can also provide a list of previous tickets to establish an initial knowledge base. "

First, you should ask me to provide you some examples of previous tickets so you can understand the structure of our tickets and some base knowledge about what has been built already."

## Talking to customers
* [How to Talk to Users- ycombinator](https://www.ycombinator.com/library/6g-how-to-talk-to-users)
* [Customer discovery - Lean Startup summary](https://www.joyfulbikeshedding.com/blog/2018-06-30-customer-discovery-according-to-the-lean-startup-methodology.html)
* Tools: [Gong](https://www.gong.io/) - I LOVE this tool for being able to replay, share, annotate and learn from customer service/success or sales calls. At my last company we had a ritual weekly friday meeting where we'd replay a topical customer conversation of the week and drove an enormous number of actionable insights and ideas from those. 

## Building trust between product and engineering
It all starts with trust. Too often I see product and engineering teams quick to throw each other under the bus for missed dealines, quality or expectations. The first job in fixing most cultures where there is disfuction, is by rebuilding trust. But you can't build trust by edict. As a product leader, you have to demonstrate taking personal ownerships of problems and failuers ... what ever the proximate causes, you've got to show that you step up and own them. At the same time delegate responsibility for successes, saves and delivery to engineering. Have engineerings back, and they'll have yours.  

## Building trust between product, design, engineering and the rest of the org

## Working with Designers

Develop an appreciation for the design process and emphasize the importance of user experience. Earn trust by encourage constructive feedback, involving design in product strategy discussions. Pick your battles, but follow through by helping designer stand their ground, sometimes even on small details, that impact the user experience.  Foster a supportive environment that allows designers to showcase their creativity and ensure their work is valued and respected.



## Working with engineers

Building strong relationships with software engineers is essential. Start by fostering open communication, understanding their pain points, and establishing clear goals and expectations. Encourage a collaborative environment that promotes knowledge sharing and continuous learning. Be open to their ideas and provide them with the resources and support they need to excel in their roles. See also Building Trust with Engineers.
* Ask for forecasts over commitments
* Understand where the risks and uncertainties are early and what's driving them
* Understand your realistic effective velocity
* Take acountability for roadmaps and expectations for engineeing execution
* Create realistic evidence-based roadmaps
* Be specific in requirments, give reasons why, be open (or sometimes push for) alternate solutions
* Engage engineers in business goals and metrics
* Help your engineers see and appreciate the direct contribution of their work on user outcomes and business success



## There is NO perfect software development process for all projects

The road to hell is paved with dogmatists for 'the one true agile method' that works for everything. Remember that most agile methodologies were developed by professional services shops that primarily tackled projects of a constrained range of scope, complexity and client profile. The reality is that as a CPO, you have projects -all critical- that will range greatly in complexity, certainty of inital requirements, and time sensitivity. You need to understand (and predict) the relative density of different work profiles. Then you need to ensure that you have a well-socialized agreement with your tech partners on the set of processes and team structures that will best set up the teams for success. An SDLC process could be super well optimized for a typical medium sized feature effort. But that same process would be gross overkill for a quick low-risk bug fix. At the same time as being dangerously underkill for a larger epic project like a risky major platform migration.

Let your project priorities dictate the SLDC processes your organization needs. Never the other way around!

## Project Management and Planning

## Architecture

You don't need to be an experienced architect to be a product manager, but it doesn't hurt. If nothing else, experience in product management will inevitably bring you no shortage of hard lessons over time in the value of good architecture. Not that you'll *ever* have the perfect software architecture. At the very least, you'll have a better time if you and team are at least somewhat aware of what an ideal solution might look like. Know the rules before you break them and all that.

Goals for architecture. It's not just about engineering a solution that works. It's about a solution that's also going to be sufficiently scaleable, extensible, maintainable, secure, reliable, resuable etc. Think through all of these considerations, but then also remember the key is 'sufficiently'. Unfortunately, expediency or realworld constraints will force you and your tech partners to make architectural tradeoffs. You're are doing well though when you are making those tradeoffs intentionally. 

### Architecture resources

* [Best Practices for Designing a Pragmatic RESTful API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* NFRs and templates
* Security for PMs
* 

## Pricing

## Distribution

## Strategy

## Product Tools

https://canny.io/
https://www.gong.io/
Notion vs google docs vs wikis
Roadmunk, product board
Ticketing systems
Figma / Figjam
Slack

## Executive level communication

## Board level communication
## People
### Career paths in product
The best and hardest thing about product it that there is no one path to PM. You can't really go to school for product management at most colleges. In fact the best teams are often formed by diverse teams with different backgrounds and 'first careers' before switching to product. You have to be generalists as a PM team but the best teams will often be composed of generalists with complimentary superpowers eg. previously coming from engineering, design, customer service etc. Yes it is important to have some technical backgroud (and/or be ready to learn). But only recruiting from eng->product will also not get you the strongest overal team. Some of my best early PM mentors had esoteric backgrounds like degrees in philosophy or agriculture. 

### Carreer ladders in product
## Interviewing

## Evaluating Product Managers

## Organizational Politics
