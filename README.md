# Job Placement Dashboard Retrospective
## Introduction
## Front-End Stories
* Style Changes to Navbar
* Style Changes to JPBulletins/Index View
## Back-End Stories
### Add Display Names to JPApplication Model Properties
### Create Constructor Method for JPApplication Model
### Create Controllers for JPMeetupGroups and JPOutsideContacts with Scaffolded Views
### Edit DeleteConfirmed Method on the JPStudentController: Deletion of JPStudent Also Deletes Associated JPChecklist
### Edit HTTP:POST Method in JPChecklistController: Create Notification When More Than 5 Checklist Items Have Been Completed
This story was multi-part: it was first necessary to create the JPNotificationsController with scaffolded views around the existing JPNotifications model. From there, I wrote code to count the amount of items marked off in a checklist after it has been edited; if more than 5 items have been marked as completed, a new JPNotification entry would have been created and appear in the JPNotification view for the Job Placement administrator. 

While working with my project managers, we realized that the table was created incorrectly during the project initialization and it required us to shift gears, create a new table, and the code was re-written for JPMessages.

### Limit JPApplications/Create View to Authenticated Users Only
My task was to limit the JPApplications/Create View authenticated users only.

### Remove About and Contact Views and Functions from Views/Home Folder and Controller
I removed unnecessary About and Contact views and functions from the home folder and controller.

## Additional Skills I Learned
* How to work on a team of developers using Azure DevOps, Slack, and Visual Studio.
* How to debug with a remote team member.
