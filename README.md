# Script Genie

Outline:
- [Introduction](#Introduction)
- [Requirements](#Requirements)
- [Technologies Used](#Technologies-Used)
- [New Technologies](#New-Technologies)
- [Technical Approach](#Technical-Approach)
- [Risks and Challenges](#Risks-and-Challenges)
- [Outstanding Issues](#Outstanding-Issues)

## Introduction
Sports announcers have to spend hours of work to prep an outline of events, or script, for their upcoming sports event. This process is usually quite tedious and repettive with similar things being done or said with slight changes. Script Genie seeks to solve this issue by providing a web application to streamline the process of making these scripts and downloading a pre-formatted script right to a user's device!

## Requirements
- **Functional Requirements**: 
    - A user is able to create an account
    - A user is able to log in to their prexisting account
    - A user is able to recover their password if lost
    - A user is able to create organizations within their account
    - An organization consists of a roster of players
    - A user that is logged in will be able to access the their existing organizations and edit or delete them should they choose.
    - A user that is logged in will be able to access a better version of the Script Genie generator and access their organization data to autofill input fields for the Script Genie.
    - Once submitted, the user's data is processed and then a script is downloaded to their machine
    - A user can still use the application without an account, only the features will be limited and they are not able to create organizations.
- **Non-functional Requirements**:
    - User passwords will not be stored in plain text in the database, they will follow base-256 encryption

## Technologies Used
- **Technologies**:
    - .NET Core
    - VueJS
    - PostgreSQL
    - Vuetify
    - Pinia
- **Industry Best Practices**:
    - Completed the full SDLC Documentation:
        - Project Proposal
        - Requirements Documentation
        - Technical Requirements Documenation

## New Technologies
- **Learning**:
    - Before this project I had never played with any frontend framework at all. In my studies I knew that I was going to be learning React and Angular and since I knew I had to learn those later down the line, I wanted to learn something outside of my school's program: VueJS. So not only did I learn frontend frameworks for the first time, but I learned a framework that my school wasn't even going to teach me.
    - I had never used PostgreSQL before this project either.

## Technical Approach
- **Design Diagrams**:
    - The logical diagram for this site highlights the different classes and components that were going to be needed to be crafted in order for this full stack project to come to life.
![Logical Diagram for Script Genie](/pictures/CST451_LogicalDiagram_DanielThompson)
    - The physical diagram highlights the physical technology that will be needed in order to make this project.
INSERT PICTURE HERE
    - The wireframe for the site showcases a rough skeleton of the site and how it will work together.
INSERT PICTURE HERE
    - Below is a UI storyboard that was crafted to provide a rough idea of what the goal was for what the site was to look like by the end.
INSERT PICTURE HERE

- **Class Diagrams**:
    - Below is the Database Schema showcasing the small and simple design of the database.
 INSERT PICTURE HERE
    - Below is the UML diagram for the entire backend REST API developed in .NET
INSERT PICTURE HERE

## Risks and Challenges
- **Risks**:
    - I had never used frontend technologies before
    - I had never used Vue before
    - I had never downloaded a PDF to an individuals device before from a web application
- **Overcoming Challenges**:
    - Persistance
    - Getting help when needed
    - Utilizing tools like StackOverflow and ChatGPT in a productive manner where deep learning was occuring
- **Risk Management**:
    - Risks were tracked in a log
        - Dates were provided on when the risk was noticed
        - Severity levels were asigned
        - Possible solutions were written down
        - And once resolved, the date was tracked for the date the problem was solved

## Outstanding Issues
- **Current Issues**:
    - The script is not fully formatted when downloaded, this needs the hands of someone actually in the industry to complete.
    - The site does have some security vulnerabilities should it be deployed.
