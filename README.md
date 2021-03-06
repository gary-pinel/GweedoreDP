# GweedoreDP
Gweedore Development Project - Team Assignment

Table of Contents

       Table of Contents
        Preamble
            Product Owner
            Team Members
        Project Deadline
        Project Specification
        Considerations
        Useful Links
            For more information visit our other sections
        Risk Register
        Tenants of Design
        Social Contract

Preamble

This is the online repository for the GweedoreDP. Due to Covid they find that they suddenly need a fast solution to provide online services to small local business and startups.  Services include administrative, funding, room booking and so on. In addition the InishowenDP have offered to supply online meeting rooms and other online resources. Your team has been requested to design a solution to be provided to the customer in seven weeks time. You should use slack, jira, github (repository to follow) and AWS to work out your solution.


Our product will be delivered using an Agile methodology that embraces the DevOps culture. Please note that our culture embraces change and these documents are treated as living, breathing artefacts that will be continuously updated.
Product Owner

Ruth G. Lennon
Team Members
Brandon
Jeremy
Lisa
Sowmya
Eric
Lakshmi
Gary


Project Deadline

23rd June 2020 at 23:59 UTC/GMT
Project Specification
    
    Clean and simple design
    User access levels (client, administrator)
    Includes at least one self developed api and one webservice
    To be run over Amazon AWS

    Frameworks
    Database
    Database persistence technology
    Define the buisness Requirements
    Named queries and database triggers for security
    Regex for cleansing and validation of data before sending to the database.

Useful Links

    DC Slack: https://lyit.slack.com/archives/G01317VQNH2
    Jira: 
    GitHub: https://github.com/rlennon/ConnachtUni
    Buy-Out Presentation: 
    Project close out presentation: 

For more information visit our other sections
Section 	Description
Process 	Describes the companies process
Project Log 	Log of project activities
Costings 	Overview of the project cost
Architecture 	Outlines the architecture
Environments 	Overview of the environment set-up
DR Plan 	Disaster Recovery Plan and procedures
Requirements 	Overview of the requirements for the project
SLAs 	Service level agreements
Risk Management 	How we manage risk
Security 	Overview of security
Project Log 	Team log for the project
Risk Register

These are the current Risks on the project, re-aligned on a weekly basis

    Infrastructure proving to be a real problem, may block being able to release software
    Team is finding itself to be running short on time due to other work and study commitments
    No PO feedback on software
    Unknown technology choices has led to a lot of upskilling required
    Changing / ambiguous requirements
    Talk of the company being bought out has raised concerns
    Lack of rights for toolsets chosen has hindered progress and ability to deliver

Tenants of Design

    Dedication to clean, secure, performant and self documented code
        code Frameworks used
        code coverage tool used
        Secure code: Regex for cleansing and validation, Named queries and database triggers
        performance testing tool to be used
    Documentation / code commenting (javadoc)/seperate branch
    Datastore for persistance
    Testing:
        Unit testing
        integretation testing
        UA
    Environments:
        staging and production
        tight configuration management for consistency and reproducibility
        automated creation and deployments
        integrated and automated pipeline (commit -> test -> deploy)
    Github version control:
        branches used
        version/release management
    Agile project management methods/principles (jira)

Social Contract

Meetings

    Stand-ups will occur "<enter date/times here>".
    The order that people give their updates will be based on alphabetical order of those present at the meeting.
    Updates will be in the form: What I've done, What I plan to do, Impediments
    Sprint planning will occur every "<enter date/times here>".
    Please add and update items within Jira prior to the sprint planning session.
    Sprint retro will occur "<enter frequency of retros here>", "<enter the date and time here>".
    The order that people present their sprint retro updates will be based on alphabetical order of those present at the meeting.
    Points raised in the sprint retro will be noted and posted on the slack channel by the Scrum Master.
    Backlog refinement?
    Task estimation will be done using <enter method here> 
    Come prepared to meetings.
    Be on time for Stand Ups and meetings.
    Mobile phones on silent.
    Everyone has equal voice and valuable contribution.
    Keep your language and tone professional at all times.
    Be honest.

Communication

    Slack is the preferred method of communication.
    If a demonstration is required use "<enter chosen media: zoom/collab/skype>", record the session and upload to the Slack channel.
    No Slack communications between "<Time and Timezone>".
    Raise a problem as soon as you see it.
    Respect each other and understand differences in knowledge.
    All team documents are to be created using Markdown language and shared on GitHub.
    There are no silly questions, if you don’t understand, ask.
    Share success stories.
    Focus on the positives.
    Don’t make assumptions.
    Don’t interrupt and cut another person off while they are talking.
    Listen when someone is talking, don’t interject.
    Zero tolerance for bullying.
    Communication in this order: "<Choose and reorder to suit the team: Slack, Zoom, Blackboard>".
    Agile way of working.
    If are assigned a job, take ownership of it and keep it up to date.
    Stick to your agreed working patterns. Let the team know when you are late or going early.
    Keep JIRA board updated at all times.
    Update the Scrum Board as you progress the story i.e. don’t update at standup.
    Don't be afraid to ask for help.
    Don't be afraid to give constructive critism, as long as it is constructive.
    Solve roadblocks within the team. If the impediment can’t be solved within the team then give it to the Scrum Master.

Other

    Sprints will start "<Day of week and time>"
    The Scrum Master role rotates each week, the schedule is available on the on the process section
    Jira will be used for task management and planning.
    Each member of the team will work "<X hours>" per week, unless they are on vacation.

Estimating Story Points Within Jira

The teams team's velocity is calculated by dividing the the number of points burned each sprint divided by no of sprints. The Velocity chart from Jira (below) is used for this calculation.

The teams current story point velocity is "<Choose the number!>".
