# Coursework Assessment Details

## Coursework Proforma

| | |
| --- | --- |
| Module number | SET09803 |
| Module title | DevOps |
| Module leader | Kevin Sim |
| Tutor with responsibility for this Assessment. Student's first point of contact. | As above. |
| Assessment | Project |
| Weighting | 60% of module assessment |
| Size and/or time limits for assessment | See description below. |
| Deadline of submission | Your attention is drawn to the penalties for late submissions.  See details below. |
| Arrangements for submission | Coursework to be submitted via GitHub. |
| Assessment Regulations | All assessments are subject to the University Regulations |
| The requirements for the assessment | See below. |
| Special instructions | N/A |
| Return of work and feedback | Face-to-face via code reviews and via Moodle. |
| Assessment criteria | See below. |

## Coursework Specification

You will work on the project as a Scrum team.  Details on Scrum are provided in [The Introduction](../units/unit00/ScrumAndTeamForming.md), including an FAQ on how to apply Scrum in the module.

You work for an organisation that requires reporting on population information.  You have been tasked with designing and implementing a new system to allow easy access to this population information.  The organisation has provided you with an SQL database to work from available [here](https://dev.mysql.com/doc/index-other.html).
 

The organisation has asked for the following reports to be generated:

- All the countries in the world organised by largest population to smallest.
- All the countries in a continent organised by largest population to smallest.
- All the countries in a region organised by largest population to smallest.
- The top `N` populated countries in the world where `N` is provided by the user.
- The top `N` populated countries in a continent where `N` is provided by the user.
- The top `N` populated countries in a region where `N` is provided by the user.
- All the cities in the world organised by largest population to smallest.
- All the cities in a continent organised by largest population to smallest.
- All the cities in a region organised by largest population to smallest.
- All the cities in a country organised by largest population to smallest.
- All the cities in a district organised by largest population to smallest.
- The top `N` populated cities in the world where `N` is provided by the user.
- The top `N` populated cities in a continent where `N` is provided by the user.
- The top `N` populated cities in a region where `N` is provided by the user.
- The top `N` populated cities in a country where `N` is provided by the user.
- The top `N` populated cities in a district where `N` is provided by the user.
- All the capital cities in the world organised by largest population to smallest.
- All the capital cities in a continent organised by largest population to smallest.
- All the capital cities in a region organised by largest to smallest.
- The top `N` populated capital cities in the world  where `N` is provided by the user.
- The top `N` populated capital cities in a continent where `N` is provided by the user.
- The top `N` populated capital cities in a region where `N` is provided by the user.
- The population of people, people living in cities, and people not living in cities in each continent.
- The population of people, people living in cities, and people not living in cities in each region.
- The population of people, people living in cities, and people not living in cities in each country.

Additionally, the following information should be accessible to the organisation:

- The population of the world.
- The population of a continent.
- The population of a region.
- The population of a country.
- The population of a district.
- The population of a city.

Finally, the organisation has asked if it is possible to provide the number of people who speak the following the following languages from greatest number to smallest, including the percentage of the world population:

- Chinese.
- English.
- Hindi.
- Spanish.
- Arabic.

### Country Report

A country report requires the following columns:

- Code.
- Name.
- Continent.
- Region.
- Population.
- Capital.

### City Report

A city report requires the following columns:

- Name.
- Country.
- District.
- Population.

### Capital City Report

A capital city report requires the following columns:

- Name.
- Country.
- Population.

### Population Report

For the population reports, the following information is requested:

- The name of the continent/region/country.
- The total population of the continent/region/country.
- The total population of the continent/region/country living in cities (including a %).
- The total population of the continent/region/country not living in cities (including a %).

## Group Submission

The coursework **must** be delivered by a group.  The aim of the module is to assess your ability to work as a team to deliver a product.  Therefore, the majority of your coursework grade will be based on your team's ability to work together using the methods defined in the module.

The submission is assessed at two assessment points.  Your submission is delivered via your GitHub repository which should also be submitted to Moodle.

## Individual Assessment

Individual contributions to the team will be assessed by your peers and the module teaching team based on contributions towards each code review, and via the metrics gathered from tools such as GitHub.  **Individual contributions will lead to a scaling of the overall coursework grade if the module team have evidence that illustrates a lack of contribution to the team deliverable.**

#### Groups must maintain a spreadsheet detailing individual team members contribution at each of the assessment points

We wish to determine the individual contribution to the team project.  To do this, the team have to submit a single spreadsheet to Moodle defining the agreed contribution of each team member to the individual delivery points.  This should be submitted in percentages with the total sum of individual contributions adding up to 100% at each point of assessment.  For example:

| Matriculation Number | Code Review 1 | Code Review 2 |
| ---- | ------------- | ------------- |
| 4000xxxx | 25          | 50          |
| 4000xxxx | 25          | 50          |
| 4000xxxx | 25          | 0         |
| 4000xxxx | 25          | 0           |
| **Total** | **100**   | **100** |
The team need to agree these scores.  **If the team cannot agree, or a team member believes the spreadsheet submitted does not represent the actual contributions, then contact a member of the teaching team.**  In these circumstances, the metrics and other information provided on GitHub will be used.

The data supplied in this spreadsheet will be used to weight each team members final mark for each assessment point.

For example, if the group received 35 out of 50 for code review one then all 4 members would get the full 35 marks as all had contributed equally. For code review 2 Members 1 & 2 would get the full group mark but Members 3 & 4 would receive zero

## Disciplinary Procedures

The coursework **must** be delivered as part of a team.  **If anyone is dismissed from their team this means they cannot deliver the coursework and will fail.**  Dismissal from a team involved the following process:

- An individual is evidenced as breaching the code of conduct as set-out by the student team.
- Evidence is presented to a member of the module delivery team.
- The individual evidenced will have the opportunity to evidence mitigating circumstances either to the group or privately to a member of the module delivery team.
- The module delivery team retains the right to the final decision of whether the dismissal is warranted.

Any dismissed team member has a week to appeal the decision to the module team with suitable evidence provided.


## Code Review Meetings

Each group will undertake **two** graded code reviews:

1. Week 6 Code Review 1 (50% of CW mark).
2. Week 13 Code Review 2 (50% of CW mark).

The code reviews will take place during the live academic sessions.  Each group will be given **10 minutes maximum** for the code review.  Your group will be **allocated a time for the code review**.  The details of the individual review points are below.  These meetings **must be attended** at the **stated time**.  Guidelines for grading the group:

- **Being late** for the meeting or **not being ready** when the meeting starts will result in the grade for that review being capped at 40%.
- **Not attending** the meeting will mean the code review will be marked at 0%.

**All team members** should attend the code review, however time zones, work commitments and other considerations will be taken into account.  **Individuals attendance at reviews will be monitored** to ensure the team is contributing collectively to the project.

**Being ready** means that you are ready to present the points for the code review.  This means that you have a computer with the various tools logged into (e.g., GitHub, etc.) and a building version of the application in IntelliJ.

### Code Review 1

#### REVIEW MEETING:  Week 6

The aim of this code review meeting is to check that the project workflow is set-up for the team, task management is set-up and that the initial requirements gathering has taken place via user stories and use cases. 

#### Checklist Submission 1 (30% of CW mark)

The following must be in place:

- [ ] GitHub project for coursework set-up.
- [ ] Product Backlog created.
- [ ] Project builds to self-contained JAR with Maven.
- [ ] Dockerfile for project set-up and works.
- [ ] GitHub Actions for project set-up and build is working using JAR, and Docker on GitHub Actions.
- [ ] Correct branches for GitFlow workflow created - includes `master`, `develop`, and `release` branches.
- [ ] First release created on GitHub.
- [ ] Code of Conduct defined.
- [ ] Issues being used on GitHub.
- [ ] Tasks defined as user stories.
- [ ] Project integrated with Zube.io.
- [ ] Kanban/Project Board being used.
- [ ] Sprint Boards being used.
- [ ] Full use cases defined.
- [ ] Use case diagram created.

#### Graded Criteria Submission 1 (20% of CW mark)

The following criteria will be assessed for overall quality:

- Metrics from GitHub.  Also used to assess individual contribution.
- Code quality including comments.
- Correct usage of branches.
- Continuous integration working.
- Use cases well defined.

### Code Review 2

#### REVIEW MEETING: Week 13

The aim of this code review is to check that testing and deployment has been correctly specified.  

#### Checklist Submission 2 (20% of CW mark)

The following must be in place:

- [ ] Quality and coverage of unit tests.

- [ ] Suitable integration tests defined.

- [ ] Continuous integration working. and tests running on GitHub Actions.

- [ ] Deployment working.

- [ ] Bug reporting system set-up.

- [ ] Badges for 

  - Build status for `master`.
  - Build status for `develop`.
  - Code coverage of tests for `master`.
  - Release name.
  - License.

#### Project Requirements Met  (16% of CW Mark)

There are 32 requirements in total. See point 3 below for details.

#### Graded Criteria Submission 2 (14% of CW mark)

The following criteria will be assessed for overall quality:

- Correct use of GitHub and Kanban board and frequency of commits. 
- Code quality including comments.


### Final Delivery Checklist 

**You must follow these steps to receive a coursework grade for the module.**  We require a copy of your submission for moderation, and therefore you will have to submit your work as defined below.  You will also receive your final 20% grade for final delivery based on the completeness and quality of your submission.

**Step 1: Ensure You Have Submitted Your GitHub Repository Clone URL to Moodle**

We will be performing a pull of your repository at the time of submission using an automated script.  **If you have not provided your GitHub link do so now.**  If you miss the cut off date for link submission your repository will not be pulled and it will be counted as a none submission.  This is a one minute task.

**Step 2: Ensure Your Main Repository Readme Contains Correct Badges**

We require the following badges on your GitHub repository to determine the status of your submission:

- Build status for `master`.
- Build status for `develop`.
- Code coverage of tests for `master`.
- Release name.
- License.

These badges will be examined to ensure they are correct.  Incorrect badges provided will be penalised appropriately.

**Step 3: Your Main Repository Readme Details the Requirements Met**

There are 32 requirements in total.  Your readme (markdown file) should state how many out of 32 have been met, and a percentage.  For example:

> 20 requirements of 32 have been implemented, which is 62.5%.

We then want evidence of each feature being met.  This will be in the form of a table (written in Markdown) with a screenshot from your application showing output that meets the requirements.  We require the following columns:

1. ID of the requirement.
2. Name of the requirement.
3. Has the requirement been met (Yes or No).
4. Screenshot.

For example:

| ID    | Name | Met  | Screenshot |
|-------|------|------|------------|
| 1     | All the countries in the world organised by largest population to smallest. | Yes | image |
| 2     | All the countries in a continent organised by largest population to smallest. | No |   |
| 3     | All the countries in a region organised by largest population to smallest. | Yes | image |

**Your submission will be checked to ensure this information is correct.  If incorrect information is provided this will be considered an act of academic misconduct by the group and dealt with accordingly.**

**Step 4: Ensure All the Above is on `master`**

We will only assess your `master` branch.  Make sure that branch contains the version of your code you wish to submit.

**Step 5: Submit your final Individual Contribution Spreadsheet**

| Matriculation Number | Code Review 1 | Code Review 2 |
| ---- | ------------- | ------------- |
| 4000xxxx | 25          | 50          |
| 4000xxxx | 25          | 50          |
| 4000xxxx | 25          | 0         |
| 4000xxxx | 25          | 0           |
| Total**** | **100** | **100** |

The team need to agree these scores.  **If the team cannot agree, or a team member believes the spreadsheet submitted does not represent the actual contributions, then email the teaching team.**  In these circumstances, the metrics and other information provided on GitHub will be used.

