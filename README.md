# voyage-project-tier1-expense-splitter

## Table of Contents

* [Overview](#overview)
* [General Instructions](#general-instructions)
* [Requirements & Specifications](#requirements-specifications)
* [Acknowledgements](#acknowledgements)
* [About Chingu](#about-chingu)

## Overview

Welcome, Chingus!

Are you ready to simplify the way you split expenses with friends, family, or roommates? Experience the convenience of managing shared costs effortlessly.

From casual dinners to group vacations or birthday parties, splitting expenses has always been a part of our social interactions. Over time, the need for an efficient and fair way to manage shared costs has grown, especially in our increasingly interconnected world.

![Friend Sitting Out](./assets/friends-sitting-out.png)

In this voyage, your team will create a user-friendly expense splitting application that takes the headache out of shared finances. Get ready to combine your problem-solving skills and creativity to build a tool that makes group expense management a breeze!

Happy splitting!

![Example Expense Splitter App](./assets/example-expense-splitter-app.png)

## General Instructions

This project is designed to be worked on by a team rather than an individual
Chingu. This means you and your team will need to thoroughly read and
understand the requirements and specifications below, **_and_** define and
manage your project following the _Agile Methodology_ defined in the
[Voyage Handbook](https://github.com/chingu-voyages/Handbook/blob/main/docs/guides/voyage/voyage.md#voyage-guide).

As you create this project make sure it meets all of the requirements, but once
it reaches MVP, start implementing the optional features or get creative and
extend it in ways we haven't envisioned. In other words, use the power of
teamwork to make it distinctive and unique.

Take note that we haven't given specific direction on what your UI/UX should
look like. This is another area where you and your team can put your creativity 
to work! 

## Requirements & Specifications

### What You Need to Do

The following define the minimum requirements and ideas for features you may
implement to enhance this app, if time permits.

#### Structure

- [ ] This is a purely frontend application. No backend is required.
- [ ] You may use any languages, tools, or libraries you prefer when designing and building this app.
- [ ] You may **_NOT_** use AI-based solution generators like GitHub Copilot.

#### Styling

- [ ] Surprise us!!! Use your team's creativity to make this app distinctive.
- [ ] Add a footer containing a link to your team's GitHub repo.
- [ ] In general, you will find these [UI design principles](https://www.justinmind.com/ui-design/principles) helpful.
- [ ] Recommend using this resource for [clean CSS](https://israelmitolu.hashnode.dev/writing-cleaner-css-using-bem-methodology).

#### Functionality
- Overview

  - [ ] Develop a single-page application (SPA) that simulates an expense splitting system.

- Expense Group Management

  - [ ] Users should be able to create an expense group with the following details:
    - Group ID
    - Group Name
  - [ ] Ability to add/update/remove member/participant to expense group utilizing
    - Member/Participant ID
    - Member/Participant Name

- Expense Management

  - [ ] Add expenses with the following details:
    - Name of expense
    - Description
    - Amount
    - Participant name
    - Date (captured automatically)
  - [ ] User should be able to edit and delete an existing expense (Date should remian Immutable)

- Calculations

  - [ ] Automatically calculate and display who owes what to whom within the group
  - [ ] Update calculations in real-time as expenses are added, modified, or deleted

- Summary and Visualization

  - [ ] Provide a summary view of total group expenses and individual balances for each participant in the group

- Data Persistence

  - [ ] Implement local storage to save expense group data in the browser
  - [ ] Add ability to export data (e.g., PDF, Excel)

- User Interface and Experience

  - [ ] Ensure the application provides a seamless user experience for managing expenses and viewing balances
  - [ ] Implement intuitive UI/UX elements to guide users through the expense splitting process
  - [ ] Use responsive design techniques to ensure the application is accessible and functional across various devices and screen sizes

### Extras (Not Required)

- Expense Group Management

  - [ ] Allow creation of multiple expense groups (optional)

- Summary and Visualization

  - [ ] Implement simple charts or graphs to visualize expense distribution (e.g can be a bar chart which shows each participant expenses in relation to the average owed amount of the group)

- Multi-currency Support

  - [ ] Allow expenses in multiple currencies

- Data Persistence

  - Add ability to export data as Chart

## Acceptance Criteria

- Expense Group Management

  - [ ] Each group can have multiple members

- Expense Management

  - [ ] Users can add new expenses with all required details
    - Name of expense
    - Description
    - Amount
    - Participant name
    - Date (captured automatically)
  - [ ] Existing expenses can be edited and deleted
  - [ ] Date of expense is automatically captured

- Calculations

  - [ ] The app accurately calculates balances within the group
  - [ ] Calculations update in real-time when expenses change

- Summary and Visualization

  - [ ] Users should be provided with a clear summary of total expenses and individual balances.

- Data Persistence

  - [ ] Expense data persists across browser sessions using local storage

- User Interface and Experience

  - [ ] The application provides an intuitive and seamless user experience
  - [ ] Responsive design ensures functionality across various devices and screen sizes

- Export Functionality
  - [ ] Users should have the ability to export the data as (e.g., PDF, Excel)

## Acknowledgements

We extend our heartfelt gratitude to the wider developer community, whose invaluable insights and expertise consistently inspire and elevate our projects. We are also deeply thankful for the powerful tools and services provided by [Google](https://google.com), [Cloudinary](https://cloudinary.com), and [AWS](https://aws.amazon.com), which play a crucial role in making our journey possible. Your contributions and innovations drive our success, and for that, we are sincerely grateful.

## About Chingu

If you aren't yet a member of Chingu we invite you to join us. We help our
members transform what they've learned in courses & tutorials into the
practical experience employers need and want.
