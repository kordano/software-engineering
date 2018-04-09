# software-engineering

## Key Performance Indicators
- requirement gathering process via design thinking workshop took place to capture all necessary tasks and requirements resulting in a requirements document (software requirements specification)
- software requirements specification (IEEE 830, https://en.wikipedia.org/wiki/Software_requirements_specification) is defined that is understood by all stakeholders and developers
- developers have the required experience for the given tasks and technologies (only short domain familiarisation phase) -> if not, how long is the familiarisation phase?
- development process is defined that describes code guidelines, individual feature development process and team communication and is understood by developers and managers
- execution plan with buffers for each feature is defined for each sprint by developers and stakeholders
- developers are on schedule for each task -> if not, how much is the delay and how many future tasks are affected?
- contingency plans for development delays are defined for developers and managers
- testing process is defined for both user interface and server API with goals on documentation process and coverage rate
- number of bugs in each phase found by tests / number of bugs in each phase by test users / number of bugs fixed in each phase
- maintenance plan after the development phase is defined
- review is performed on each phase against plan described in software requirements document regarding estimation and quality of features


## Development Process

### planning
#### overall
- once before project start
- discuss roadmap with customer
- define milestones based on requirements
- identitfy stakeholders
#### milestone
- collect features / bugs
- identify developers
- define tasks
- estimate time
- document in github as milestone
- assign tasks
#### task / bug
- create issue on github
- describe feature
- attach to milestone
- assign developer
#### daily standup
- discuss progress daily at same time
### requirement analysis
#### user stories
- identify user stories based on customer's feature requests
- write down user stories
- derive tasks from user stories
#### bug
- identify problem space
- assign developer
### design
- design architecture based on user stories
- propose different solutions
- let customer decide
### coding
- create branch based on your issue number and task
- work work
### unit testing
- create API tests
- create integration tests with foreign APIs
### acceptance testing
- create pull request
- make paired code review
- adjust changes
- merge pull request after successfull change
