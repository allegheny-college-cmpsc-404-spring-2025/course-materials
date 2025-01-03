# CMPSC 404: Web Applications


## Important Resources

* [Office Hours schedule](https://chompe.rs/office-hours)
* [Course Calendar](https://chompe.rs/404-schedule)

## Syllabus

> "I am Oz, the Great and Terrible. Why do you seek me?"
>
> Dorothy asked, “Where are you?” 
>
> "I am everywhere,” answered the Voice, "but to the eyes of common 
> mortals I am invisible."
>
> -- L. Frank Baum, _The Wizard of Oz_

### Course information

#### Meeting times

|Day(s) of Week            |Time          |Purpose     |Location                        |
|--------------------------|--------------|------------|--------------------------------|
|Monday, Wednesday, Friday |11:00 - 11:50 |Activities  |Alden 101                       |
|Thursday                  |14:30 - 16:30 |Lab session |Alden 109                       |


### Contact

* Instructor: Douglas Luman
* Email: dluman@allegheny.edu
* Telephone: `+1 814 332 2136`
* Office: Alden Hall, 112 (next to the copier)

### Office hours

|Day(s) of Week            |Time           |Place     |
|--------------------------|---------------|----------|
|Monday                    |10:00 - 11:00  |Alden Hall|
|Wednesday                 |10:00 - 11:00  |Alden Hall|
|                          |15:00 - 16:30  |Alden Hall|
|Thursday                  |10:00 - 12:00  |Alden Hall|
|Friday                    |10:00 - 11:00  |Alden Hall|
|                          |15:00 - 16:30  |Alden Hall|

To reserve a 15-minute slot during the above times, visit my office hours calendar [listed above](#important-resources).

### Canonical course description

An exploration of technologies and data relationships which power modern web applications. Participating in hands-on activities which require teamwork, students build web applications that incorporate the "full stack," including databases, application programming interfaces (APIs), and public-facing web pages or mobile applications. Students develop a broad knowledge of different development approaches, languages, and design paradigms to learn advantages and disadvantages of technologies and frameworks. During weekly laboratory sessions, students participate in iterative design processes and report progress and technical details through written documents and oral presentations. Students are invited to use their own departmentally approved laptop in this course; a limited number of laptops are available for use during class and lab sessions.

Prerequisite: `CMPSC 203` or `CMPSC 302`.

Distribution Requirements: `QR`, `SP`.

#### Distribution requirements

##### `QR`

Students who successfully complete this requirement will demonstrate an understanding of how to interpret numeric data and/or their graphical or symbolic representations.

##### `SP`

Students who successfully complete this requirement will demonstrate an understanding of the nature, approaches, and domain of scientific inquiry.

### Course learning objectives

|Objective |Related Distribution Requirement(s) |
|:---------|:-----------------------------------|
| Define the structure of the web application "stack" and describe the meaning and implications of implementing a "full stack" application. | `SP` |
| Explain the layers of the Transmission Control Protocol/Internet Protocol (TCP/IP) and describe their relationship to server-side and client-side web applications. | `QR`, `SP` |
| Develop secure, reliable application programmer interfaces (APIs) using the Representational State Transfer (REST) or Simple Object Access Protocol (SOAP) specification(s). | `QR`, `SP` |
| Model industry standard server security practices such as, but not limited to, firewall, web server, and database configuration. | `SP` |
| Select solution-appropriate open-source software to implement a “full stack” web application project using server-side and/or client-side rendering frameworks. | `SP` |

### Required materials

#### Course technologies

The technologies underlying this course are all hosted and provided free of charge. The follow list attempts an exhaustive catalog of the various
tools used:

- Docker
- Github Codespaces
- Github Actions
- Django
- PostgreSQL
- Python
- node.js
- Apache Web Server 2.0
- Network File-Sharing (NFS) protocol

Not every student will need to use all of these at one time, and students may not receive equal time learning all of the platforms and products listed
above. However, this course provides exposure to inputs and outputs of processes using these technologies. Those students interested in learning more
about any of the tools used in the platform(s) developed for this course are free to explore all available codebases and resources written for the
project.

#### Platforms

This course relies on your regular use of:

* [GitHub](https://github.com)
* [Discord](https://discord.com)

### Evaluation

This course develops a _persistent_ and _real-world_ product with _users_. This means that the emphasis of evaluation in this course is less on technical
proficiency gained in a given tool and more about two key concepts:

* meeting project deadlines
* working functionally as a team

Despite (or, perhaps _because_ of) these priorities, high-quality, workable code is a _given_.

The parameters defining your evaluation live in our shared [course code of conduct](CODE_OF_CONDUCT.md). These involve both _client-side_ feedback
and team self-evaluation in addition to instructor appraisal of that feedback. While more on the mechanisms of this system is included in the course
code of conduct, the general definition of the phases and weights of those phases is defined below:

|Module       |Weight |Point value |
|-------------|-------|------------|
|Module 1: Project planning and design                   |20%    |200 pts.    |
|Module 2: Building Web Applications                     |20%    |200 pts.    |
|Module 3: Building a minimum viable product (MVP)       |20%    |200 pts.    |
|Module 4: Testing and finishing your release candidate (RC)  |20%    |200 pts.    |
|Presentation                                            |20%    |200 pts.    |
|Total        |       |1000 pts.   |

#### Class participation

The major vehicle for class structure is your participation. This can mean attending class sessions, but also encompasses attending group meetings 
or contributing to group communication. You will receive five (5) participation scores through the semester: one (1) for each Module and one (1) 
for the Presentation. These scores will be the result of you and your group’s assessment of your participation in a given module and count 
toward individual Module grades earned.

#### Cycles

The semester is composed of four (4) Modules, each running roughly three-and-a-half (3.5) weeks long:

|Module     | Dates            |
|:----------|:-----------------|
| Project planning and design  | 17 Jan. - 9 Feb. |
| Building Web Applications    | 12 Feb. - 1 Mar. |
| Building a minimum viable product (MVP) | 11 Mar. - 5 Apr. |
|Testing and finishing your release candidate (RC)  | 8 Apr. - 29 Apr. |

"Modules" are defined periods of time during which students (organized into semester-long teams) contribute to their version of the client project 
while fulfilling the obligations of one (1) of three (3) roles. Each student will occupy any of the following three roles, assuming a new one at the start of each 
Module which they have not occupied in a previous Module.

Team members are allowed to be _cross-functional_, meaning that they are able to assist with tasks for which another role is responsible.

Team members _must_:

* assign a Technical Manager
* assign a Writer
* assign a Developer/Designer

Team members _may not_:

* assign more than one Technical Manager
* completely take on responsibility for two roles

##### Technical Manager

Students serving the Technical Manager role develop and implement testing protocols for ensuring that developed code meets the needs of the original client request. This role includes, but is not limited to:

* Guiding the requirements-gathering process
* Developing and maintaining a testing protocol
* Developing appropriate testing via best-suited methods
* Managing team deadlines and deliverable statuses
* Conducting complete and thorough testing according to developed testing protocol
* Facilitating communication between the Writers and Developers

In addition, Technical Managers are responsible for charting the team's progress and maintaining the GitHub Project Board assigned to their team.

##### Developer/Designer

Students in the Developer/Designer role are responsible for implementing solutions to either bugs or feature requests documented by the team during requirements-gathering. This role includes, but is not limited to:

* Developing code to solve an issue or implement a feature 
* Conducting initial, shallow testing of developed code
* Providing adequate inline documentation per the standards of the community to which contribution is being made
* Collaborating with team members to implement and conduct thorough requirements-gathering
* Creating wireframes or other planning assets

##### Writer

Writers manage external communication between the team and the client. In addition, a student serving as a writer for a given Module maintains the overall repository for the duration of a given Module. This role includes, but is not limited to:

* Corresponding with the client using GitHub's issue tracking system
* Documenting overall progress for the team–Compiling and submitting the Module’s final technical report using a GitHub Wiki
* Creating, maintaining, and organizing project documentation describing features, APIs, or other relevant information
* Developing diagrams or other technical aids to communicate technical complexities and/or interactions

Each Module will be concluded by submission of a Final Technical Report (FTR) which will require input from all team members. It will be distributed through and should be turned in via GitHub.

#### Assignment deadlines

This is a project for a client; it's more like life after school than life _during_ school. Like post-academic deadlines, deliverables developed for each Module is due by the end date of the Module. This means that the end dates listed above are _hard deadlines_.

The modular nature of course design contemplates that we need to _keep moving_. Instruction will continue regardless of a single team's incomplete work. If there's unfinished work from a prior Module, it hinders your performance on all following Modules and may jeopardize your ability to complete the project to client standards. 

### Course preparation

I expect students to arrive to class prepared. Here, "prepared" means having completed reading assignments, compiled questions, 
and being ready to engage thoughtfully with course material. In order to assist students' preparedness efforts, I will provide a 
[schedule](https://chompe.rs/404-schedule) with assignments and accompanying materials or readings.

### Allegheny College Statement of Community

Allegheny College also expects students and faculty to act according to its Statement of Community:

> Allegheny students and employees are committed to creating an inclusive, respectful and safe residential learning community 
> that will actively confront and challenge racism, sexism, heterosexism, religious bigotry, and other forms of harassment and 
> discrimination. We encourage individual growth by promoting a free exchange of ideas in a setting that values diversity, trust 
> and equality. So that the right of all to participate in a shared learning experience is upheld, Allegheny affirms its commitment 
> to the principles of freedom of speech and inquiry, while at the same time fostering responsibility and accountability in the 
> exercise of these freedoms. This statement does not replace existing personnel policies and codes of conduct.

### Honor Code

All students and faculty at Allegheny College are bound by the Honor Code. Everyone expects that your behavior reflects this commitment. Given the eminently shareable and reproducible nature of code, the Department of Computer Science adds the following statement to the general college policy:

> It is recognized that an important part of the learning process in any course, and particularly in computer science, derives from 
> thoughtful discussions with teachers, student assistants, and fellow students. Such dialogue is encouraged. However, it is necessary 
> to distinguish carefully between the student who discusses the principles underlying a problem with others, and the student who 
> produces assignments that are identical to, or merely variations on, someone else’s work. It will therefore be understood that all 
> assignments submitted to faculty of the Department of Computer Science are to be the original work of the student submitting the assignment. 
> Appropriate action will be taken when assignments give evidence that they were derived from the work of others.

The above statement, of course, also applies to solutions derived from discussions on Stack Overflow and other similar resources.

#### AI tools

I fully expect that many of you will use tools like OpenAI's GPT code completion, GitHub Co-pilot, and others on assignments. These are professional, industry-grade tools. However, there is a marked difference between implementing the solutions these tools suggest and copying their suggestions wholesale. In many cases, these tools will lead you to either incorrect or significantly advanced answers. As one might say in the consumer trade, _caveat emptor_.

One of the goals of your time in this class, much less at Allegheny, is to learn how the subjects discussed in classes relate and impact your future work. While there are many ways that your assignments will test your understanding of the concepts underlying our coursework, I ask a few of things from you, completely aware that you are fully on your own honor with any of these:

* be prepared to explain a detailed understanding of the code you're offering for review, documenting where and how you used an assistant tool in:
  * technical reports
  * code comments, specifically labeling the portions of code derived from use of AI tools
* consider how you might improve an assitant-generated solution, documenting this in reports and implementing your improvements in code
* keep an operating assumption that I'm not reviewing your solutions for a "gotcha"; I only assume the best of your effort

### Classroom ethics

The discipline of computer science, like many others, encourages its members to act according to discipline-specific ethics. I encourage you to take time to review the Association for Computing Machinery (ACM) [Code of Ethics](https://www.acm.org/binaries/content/assets/about/acm-code-of-ethics-booklet.pdf).

### Seeking assistance

#### Assistance with course concepts

Students who struggle to understand knowledge and skills defined in this course are encouraged to seek assistance from instructional staff. To meet with me, consult my available office hours (above) and make an appointment.

Historically, students who are successful in my courses visit and discuss course concepts with instructors or TLs early and often. See [above for my office hours](#office-hours) or go to [this schedule for Technical Leaders' office hours](https://www.cs.allegheny.edu/teaching/technicalleaders/).

#### Assistance outside of the course

If you find yourself in difficult circumstances which affect your ability to participate in or complete course work, let me know immediately. Full stop.

Do not wait until the end of the semester. 

*It is part of my job* to make sure that students receive the assistance they need. Do not hesitate to let me know if there is anything I can do with respect to your ability to handle your work. This is especially true of our current circumstances. Again, let me remind you -- __**it is part of my job**__ to help you access Allegheny College resources that will enable your safety and success.

In many situations, the following list of resources may help:

* [The Maytum Learning Commons](https://sites.allegheny.edu/learningcommons/)
* [Allegheny College Counseling Center](https://sites.allegheny.edu/learningcommons/)
* [The Winslow Health Center](https://sites.allegheny.edu/healthcenter/)
* [Student Life](https://sites.allegheny.edu/studentlife/)

### Special needs and disability

Students with disabilities who need accommodations in this course are encouraged to contact Disability Services at `+1 814-334-2898`. Disability Services is part of the Learning Commons, located in Pelletier Library. Should you need accommodations, contact this office as soon as possible to ensure that approved accommodations are communicated and implemented as quickly as possible. This serves both you and me in providing the best environment for learning and support.
