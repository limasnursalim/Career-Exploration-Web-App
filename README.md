# STEM Career Exploration Web App

## Introduction
STEM professionals are well compensated and highly in demand. Yet, the STEM training
pipeline appears to be leaky. Many students who start out in pursuit of STEM degrees end up
switching majors, or dropping out of college. Even STEM graduates often do not continue along
a STEM track in pursuit of a STEM-related career. [add REF - expected job vacancies in
STEM]. The issue of persistence is most particularly pronounced among traditionally
underrepresented stakeholder groups in STEM. One of the high-impact practices that can
promote STEM retention, of a broad cross section of students, in a STEM path is participation in
an undergraduate research experience (URE). In UREs, students conduct research with a
faculty mentor in the field in which they are studying, either during the academic year, or during
the summer. There is a large - and growing - body of research describing the benefits of URE to
students. Yet, the mechanism explaining how UREs generate positive outcomes is not well
understood. Our goal is to understand how specific aspects of UREs are related to positive
student outcomes. To achieve this goal, we are characterizing URE structure using theoretical
framing from the domain of work psychology, with specific emphasis on the implications of job
characteristic theory and the work design model. According to the work design model
(Morgeson and Humphres, 2006), work can be characterized along four dimensions: task
characteristics, knowledge characteristics, social characteristics and work context. In our
project, URE participants will report on their experience in terms of these four dimensions, and
on the perceived benefits of having participated. Participants will receive feedback on their
responses, and encouraged to interact with the web-based exploration database to: 1) reflect
on their research experience, 2) compare it to the experiences of other URE participants, 3) and
to a sample of STEM-related occupations with attributes coinciding with students’
URE-anchored preferences drawn from professional occupational databases (O*NET).

The anticipated benefits of the project fall into three broad categories: benefits for individuals,
benefits for society and benefits for our participants in our research group:

1) *For individuals:* Individuals pursuing a STEM-related degree will have the opportunity to
explore a curated, comprehensive set of STEM-related occupations drawn from the Occupation
Information Network (O*Net). O*Net is a free, online database that contains almost a thousand
job definitions, designed to enhance students’ and job seekers’ understanding of the
occupational landscape in the United States today. Systematic, curated exposure to the O*Net
will help students currently pursuing STEM degrees to explore career options directly coinciding
with their academic interests, to identify a subset of matching occupational tracks, and to find
professional occupations they will find fulfilling based directly on their STEM-related preferences
and interests.

2) *For research group:* This research focuses on relationships between the structure of
undergraduate research experiences (UREs) and a range of positive STEM-related outcomes.
In this research we use a survey-based approach to collect data bearing both on students’
research experience, as well as their preferences for various aspects of this research
experience. We are developing a comprehensive STEM-occupational database to allow
research participation to directly benefit from their participation by using their survey responses,
and their preferences/likes/dislikes to explore a range of STEM-related career options.
Importantly, because students will be able to access the interface being developed for this
project again and again, they can engage in more refined occupational search as their research
preferences and interests mature over time.

3) *For society:* Broad work-force involvement in STEM-related careers is recognized as a priority
by a number of governmental agencies. The curated exposure to STEM-related occupations
the process described in this proposal facilitates should systematically increase students’
persistence in both STEM-related college degrees, and following graduation subsequent
persistence toward and into STEM-related careers.

## Database E-R Diagram
![E-R Diagram](https://github.com/limasnursalim/Career-Exploration-Web-App/blob/main/docs/img/Final%20ER%20diagram.PNG)

## UI Screenshots
![Login Page](https://github.com/limasnursalim/Career-Exploration-Web-App/blob/main/docs/img/LoginPage.png)
![Fresh Job Search](https://github.com/limasnursalim/Career-Exploration-Web-App/blob/main/docs/img/Fresh%20JobSearch.png)
![Profile Page with Freshly Added Profiles](https://github.com/limasnursalim/Career-Exploration-Web-App/blob/main/docs/img/ProfilesPage%20with%20freshly%20added%20Profiles.png)
![Desired Profile Match](https://github.com/limasnursalim/Career-Exploration-Web-App/blob/main/docs/img/DesiredProfileMatch.png)
![Desire Profile Creation Page](https://github.com/limasnursalim/Career-Exploration-Web-App/blob/main/docs/img/Desired%20Profile%20Creation%20Page.png)

## Methods (sources of data)
There will be four types of data stored in the database:
Job Characteristics, Job Title and descriptors from O*NET database and User Profiles.
1. **“Job characteristics”** are characteristics of a job generated by the user “Professional”
based on their individual experiences (STEM Professionals take a survey describing their work
experience in terms of the 4 dimensions of work structure, training and years of experience, and
job title corresponding to title in O*NET).\
These records can be of 3 types based on the source of data and each have status “provisional” or “reviewed.”:
  - Survey
  - Interview
  - Survey and interview
  
> The data can be added by the database administrator as a file upload or by users
“STEM Professional.” The Administrator also has the ability to review “provisional” records, and
change their status to “reviewed.”
The survey data can be entered by the users “STEM Professionals” who complete the
survey on the database website or upload a data file that was previously generated by
completing the survey and saving results by the user. Every time the user uploads the survey
results from a file or completes the survey, they are asked if they would like to add their data to
the database.
Provisional self-reported record can be reviewed by the database administrator and
provisional status changed to “reviewed.” “Administrator” may also upload “job characteristics” records as a file with record tagged “interview and survey” or “interview.” In addition, special
user “interviewer” may also upload these types of records under status “provisional.”
2. **URE characteristics** - compiled from individual student survey responses
contributing data regarding the structure of their UREs, discipline and institutional context.
3. **O*Net job titles** and occupational descriptions drawn from O*NET, labeled as STEM
and non-STEM. When retrieving job titles, the user has the option to look only at STEM jobs or
non-STEM jobs or both.
4. **User accounts** for people interested in exploring careers and saving their history, as
well as sharing their history with researchers. User account may contain:
> 1) One or more individual experience profiles (a job, an undergraduate research
experience) that includes results from survey for one or more jobs or undergraduate research
experiences (users may label each set of results with a label of their choice, for example “Cal
Poly 2021-22 URE,” Amgen summer URE, “Galapagos URE,” “lab tech for Amgen,” Postdoc,
etc.),
> 2) For each descriptor from the survey, the user may indicate and store preference rating
and importance rating. The preference rating is on a 5-point scale for liking and disliking
specific attribute e.g.1 = strongly dislike, 5 = strongly like), the importance rating is on three
point scale (very important, somewhat important, not important).
> 3) User accounts may also contain job title lists from searches of O*NET occupations
based on specified criteria.
> 4) User notes

Additional data that will be used, but not stored:
- URE description based on survey (uploaded into active session from a file)
- Individual preference and importance ratings for users who wish to use the database
without creating an account.

### For complete documenation, please check ```docs/```
