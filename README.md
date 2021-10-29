# team4-p2
Project 2 repo for team 4



# Project-2 Requirements
Within groups of 4, you are required to develop an application using the following mandatory technologies.
#### Presentation Date: Monday Oct 18th, 2021
You will present this application as if you were pitching it to a board or to investors.
When you're presenting, you're welcome to provide a brief slideshow demonstrating the technologies involved in the app, it's features, and the Agile Development Process you undewent to develop it.

## Required Technologies for RESTful Wep Application
- Spring Boot (With Spring Data and Spring Web)
- Angular
- Consume a RESTful API
- Amazon RDS
- AWS CodePipeline for CI/CD
- GitHub (*Each team must maintain a repository to which all members contribute*)
- Unit Tests & Logging
- Roadmap Presentation
  > Present your app with a slide show (Roadmap) and talk us through any extra technologies you implemented either within your application or to track the progress of your sprint.

## Required User Stories
- Login/Logout
- Register
- Anything else

<br>

## ⁉️ ⁉️ What's Due Monday Oct. 4th by 10am? ⁉️ ⁉️
- **Project Proposal** - you're welcome to use the word document provided in this directory or make a copy of [this google doc](https://docs.google.com/document/d/1F2UKzwIcsxWdGlY5bIsM6XfOyx2NAPiL0VXWOLcLTkk/edit?usp=sharing)

  > Slack this document to me.  The proposal is a brief description of your application, team members, and Team Lead.
  > The *Team Lead* represents the point of contact for the team and will be reporting updates in every morning's standup.

<br>

## Agile Scrum Guidelines
For software teams, the stand-up is like the team’s huddle. It’s even commonly known as the daily scrum, and reinforces “we” to keep everyone aware of the team’s landscape and progress.
- Every day you should have a stand-up meeeting with your team.
- Each morning at 10:00am, your Team Lead will present on the current status of the project and any blockers you're facing or have resolved the day before and what you're doing that day.

### In your Team Standups Use the 3 question agenda:
*Lead asks each attendee to answer these questions.*
  1. *What have I done since the last meeting?*
  2. *What do I plan to complete before the next meeting*
  3. *What problems am I likely to face?*
*Don’t spend too much time on status updates. Focus on what needs to be done and the problems or impediments that may arise.*
> Of course, your team is responsible for holding additional planning and collaboration meetings -- stand-ups are simply a check-in.

## Suggestions:
- Use a [Kanban Board](https://www.atlassian.com/agile/kanban/boards) like [Trello](https://trello.com/?&aceid=&adposition=&adgroup=105703214328&campaign=9843285532&creative=437184392320&device=c&keyword=trello&matchtype=e&network=g&placement=&ds_kids=p53016490704&ds_e=GOOGLE&ds_eid=700000001557344&ds_e1=GOOGLE&gclid=Cj0KCQiA2af-BRDzARIsAIVQUOfgZifIwr-ClvNLXs4m9zn7VFhTU4bXoVdq1iBVe7SNfiXGeVVNKlgaAsHAEALw_wcB&gclsrc=aw.ds)
- Use a [Burndown Chart](http://www.agilenutshell.com/burndown)

* All curriculum end points are available at /curriculum/...
  - /add : insert a curriculum by sending a curriculum object in the body of a post request
  - / : finds all curricula and returns a list
  - /findId/<id> : finds a specific curricula by its id number in the path variable
  - /findName/<name> : finds a specific curricula by name as a path variable
  - /update : updates a curricula object from a post request body
  - /deleteById/<id> : deletes a curricula by its id as a path variable
* All topic end points are available at /topics/...
  - /add : inserts a topic by taking an object in the body of a post request
  - / : finds all topics returned as a list
  - /<id> : finds a specific topic by its id as a path variable
  - /search/<name> : finds a topic by name as a path variable
  - /<id> : updates a topic by taking its id as a path variable and topic object in the body of a put request
  - /<id> : delete a topic by id by sending a delete request with id as a path variable
* All technology end points are available at /tech/...
  - /add : inserts a technology object from the body of a post request
  - / : finds all technologies returned as a list
  - /<id> : finds a specific technology by its id in a path variable
  - /search/<name> : finds a technology by taking its name as a path variable
  - /<id> : update a technology by sending a patch request with id in the path and object the body
  - /<id> : delete a technology by sending a delete request with the id as a path varible
