## Node.js Certified Developer

In December 2016, the Node.js Foundation held an in-person development workshop
after Node.js Interactive North America to accelerate work on its new Node.js
Certified Developer program.

The certification program aims to establish a baseline for competency in
Node.js. While not an expert in all areas, developers who pass the certification
will be able to hit the ground running with Node.js professionally.

The Job Task Analysis (JTA) working group determined specific topics for the exam
and the skills, knowledge, and abilities a certified candidate should be able to
demonstrate to become a Node.js Certified Developer.

The process for our workshop is explained below. We’ll start with a few
premises!

**Please see [this repo](https://github.com/nodejs-certified-developer/certification) for activity specific to certification development.**  
  
------------

#### We are certifying early Intermediate level developers.

Developers who certify cannot do everything, but hit the ground running with a
Node.js job.

Considering the constraints of the exam environment (isolated and proctored), we
 needed to address concerns around security, exam item exposure, and cheating.
 Discussions spanned the full gamut of what we use on a day to day basis as
 Node.js developers. Amongst resources considered to have available/unavailable:

- Google search
- Lodash, underscore
- JavaScript frameworks
- Node.js frameworks
- Testing frameworks
- A white list of modules
- Keeping resources within VM
- Potential of developers to create npm packages that have answers pre-coded and
this can be logistically taxing to monitor by the Certification team.

The issue of the programming environment candidates would encounter as part of
the certification was discussed at length as well. Considerations included:

- Important to be vendor-neutral, no lock-in
- Tiers of support for Node.js were talked about: Linux, Mac, Windows. Ways to
provide a single environment but account for those who develop outside of OSX
so they are not penalized.
- Make sure we're covering the approximate quirks that different operating
systems have in the answer logic/testing  
- Write agnostic JavaScript/Node.js items
- Infrastructure may be provided by a third party with constraints as yet
unknown

### Scope

Participants individually attempted scope statements in writing and then
presented them aloud while transcribed. The critical elements of each were
highlighted, captured, and combined into a single scope statement.

>Node.js Certified Developers can work proficiently in JavaScript with the
Node.js platform to build, debug, test and maintain secure framework-independent applications and CLI tools.  

>They are capable of handling asynchronous I/O effectively and efficiently
to manipulate, transform and persist various data using HTTP, files,
streams, and multiple processes.  They can leverage and integrate 3rd party
modules effectively.  

### The Topics!

The next order of business was to determine the primary domains of performance.
Participants named many topics, which were then transcribed and posted on large
(24” x 36”) Post-It sheets.  As we converged on ideas, it was realized that some
topics were out of scope, others could be captured under another domain.  The
determined Domains are:

Below is the final blueprint.

|  # 	| DOMAIN                                                        	| WEIGHT 	|
|:--:	|---------------------------------------------------------------	|:------:	|
|  1 	| **Unit Testing**                                                  	|   5%   	|
|  2 	| **Diagnostics** (Basics, Debugging, Performance)                   	|   5%   	|
|  3 	| **http(s) TCP**                                                 	|   11%  	|
|  4 	| **Events**                                                        	|   9%   	|
|  5 	| **Child Processes** (Basics, no IPC/fork)                          	|   7%   	|
|  6 	| **Buffers and Streams**                                           	|   9%   	|
|  7 	| **Error Handling**                                                	|   7%   	|
|  8 	| **File System**                                                   	|   7%   	|
|  9 	| **Control flow** (Async tasks, Callbacks)                          	|   10%  	|
| 10 	| **CLI** (-E, -R, etc)                                             	|   3%   	|
| 11 	| **Package.json**                                                  	|   5%   	|
| 12 	| **Javascript Prerequisites** (Closures, prototypes, var/let/const) 	|   6%   	|
| 13 	| **Security** (Basics only)                                         	|   5%   	|
| 14 	| **Module system** (Scope)                                          	|   6%   	|
| 15 	| **Process/Operating System** (no IPC)                            	|   5%   	|
|    	|                                                         Total 	|  100%  	|

The most valuable and heated discussions of this workshop was in determining
these weights. The diversity of roles that were giving input to the
weights--hiring managers, trainers, teachers, and developers of a wide range of
experience levels is key in finding confidence in the selected weights. It is
important to note that we will monitor the performance of candidates in alpha
and beta testing to determine whether these need to be adjusted for setting a
passing score.

Individual tasks were written for each domain and subtopic, however the working
group did such a great, detailed job that we risk exposing potential questions
for the exam. These tasks will the foundation of the Item Writing development
phase.

### Testing Details

A test length of 3 ½ hours was deemed appropriate for the scope of the exam and
for human comfort/attention span. The test time includes introductory material,
practice items, instructions regarding control structure, as well as final
instructions regarding results reporting.

The test will consist of approximately 30 items, depending on the results of
Beta testing.  The test will be comprised of one form with item variants for
security purposes.

Writing, editing and testing code are going to be the assessment mechanisms used
in this exam.  In some items, partial code will be provided to the candidate to
reduce the time required to demonstrate the skills to be evaluated.  In other
contexts, the candidate would write an entire program.

No prerequisites or credentials are required to take the examination.  This has
to be stated for those who are not familiar with certification programs.

### Recertification Interval

Recertification requirements and interval:

1. Regulatory requirements:  there are no regulatory requirements for Node.js.
2. The exam will reflect changes to normative documents annually with LTS cycle.
3. The exam will reviewed and updated every 2 years   
4. The LTS release support cycle reflects the nature and maturity of the industry or field in which the certified person is working.
5. The risks resulting from an incompetent person include the following:  bad hire; lost recruitment money; incremental training costs; missed deadlines.
6. Ongoing changes in technology, and requirements for certified persons are reflected in ES releases
7. Requirements of interested parties were taken into account in formulating the task force, and will be included in guiding bodies for updating and revision of the exam. Interested parties include:
 - Programmers  Training companies  Foundation  Consultancy companies
 - Organizations using Node  Hiring managers
8. No surveillance activities are planned to evaluate certificants on an ongoing basis.

### Test Retake Interval

In order to maintain current certification, certificants will be required to
retake the Node.js certification exam every two years.  

### Exam Review Interval

Because of changes to the Node language, every two years the exam will be
reviewed for content appropriateness and accuracy.  If it is determined that the
exam needs substantial revision, then another JTA will be undertaken.

### Recommended learning materials
(to be refined and moved to a separate document)

A subset of these will be provided as part of the isolated exam environment.

- Node docs
- node_modules readme files
- MDN JavaScript docs
- Package.json docs

#### Books
- [Eloquent Javascript](http://eloquentjavascript.net/)
- [HTTP – the Definitive Guide](http://shop.oreilly.com/product/9781565925090.do)
- [HTTP Developer’s Handbook](https://www.amazon.com/gp/search?index=books&linkCode=qs&keywords=9780672324543)
- [Node Cookbook](https://www.packtpub.com/web-development/node-cookbook-second-edition)
- [Node Up and Running](http://chimera.labs.oreilly.com/books/1234000001808/index.html)
- [Node.js in Action](https://www.manning.com/books/node-js-in-action-second-edition)
- [Node.js the Right Way](https://pragprog.com/book/jwnode/node-js-the-right-way)
- [You Don’t Know JS](https://github.com/getify/You-Dont-Know-JS)

#### URLs

- IETF
  - [RFC 2616](https://tools.ietf.org/html/rfc2616)
  - [RFC 7230](https://tools.ietf.org/html/rfc7230)
  - [RFC 7231](https://tools.ietf.org/html/rfc7231)

#### Training Materials

- [NodeSchool.io](https://nodeschool.io/)
  - [learnyounode](https://github.com/workshopper/learnyounode)
  - [scope-chains-closures](https://github.com/workshopper/scope-chains-closures)
  - [stream-adventure](https://github.com/workshopper/stream-adventure)
