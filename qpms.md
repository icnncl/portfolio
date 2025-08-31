# QPMS : Quality Project Management System  

<img width="963" height="684" alt="image" src="https://github.com/user-attachments/assets/ade082d9-efb2-4e04-a6b2-d5c67ac5ff81" />

<img width="1520" height="891" alt="proj mgmt" src="https://github.com/user-attachments/assets/6de1a657-0135-49c2-948f-3963443e2bf0" />

<img width="1526" height="921" alt="task mgmt (2)" src="https://github.com/user-attachments/assets/8cd53ff8-ab59-49bb-81c3-3ac3f36badbb" />

<img width="1527" height="887" alt="issue mgmt (2)" src="https://github.com/user-attachments/assets/1d9ab950-bcbd-47c6-a71b-0be8980ec735" />


<img width="1619" height="953" alt="forum mgmt" src="https://github.com/user-attachments/assets/184924a3-7753-4276-a095-4c337ebffc11" />

<img width="1278" height="1226" alt="doc repo" src="https://github.com/user-attachments/assets/93003662-9b60-4f13-bfcf-033481f58b2f" />

<img width="1270" height="1201" alt="qms doc list" src="https://github.com/user-attachments/assets/6c49eb1b-01d6-49f8-acef-68697085d294" />
<img width="1278" height="808" alt="proj docs" src="https://github.com/user-attachments/assets/4ba5fc44-cdbf-4c19-b769-9bbd0464368c" />

<img width="1253" height="669" alt="timesheets" src="https://github.com/user-attachments/assets/c077756f-22c9-4664-9d0e-7267940fabe5" />

<img width="1271" height="670" alt="timesheet entry" src="https://github.com/user-attachments/assets/731f64dc-958b-4e32-a305-e331e0489529" />

<img width="1339" height="626" alt="chat" src="https://github.com/user-attachments/assets/2ef7fcc2-8c6d-448d-8eab-e1625fc204f1" />

<img width="1478" height="1079" alt="image" src="https://github.com/user-attachments/assets/2ad2844c-0921-4f13-97af-2692da65ecef" />


- https://qpms.pythonanywhere.com          
- Installation available for **on-premise deployment (internet connection optional)**
- **AI ChatBot features** available with Ollama depend on the hardware capacity (successfully tested on 32GB RAM) 
- Offline technical support and installation services available
- **qualityportfolio9** at google mail

## Features

- **User Authentication**: JWT-based authentication with registration and profile management
- **Project Management**: Create, update, and manage projects with goals and tasks
- **Task Management**: Assign, track, and complete tasks within projects
- **Issue Tracking**: Create and manage issues with comments and status updates
- **Team Collaboration**: Forum discussions and chat functionality
- **Time Tracking**: Comprehensive timesheet management for reporting and measurement
- **Document Management**: Repository for project documents and QMS files
- **Reporting**: Project analytics and quality reports
- **Search**: Advanced search across projects, tasks, and issues

## Technology Stack

- **Backend**: Django 5.2.3 + Django REST Framework
- **Database**: sqlite3
- **Authentication**: JWT (JSON Web Tokens)
- **Cursor**: Approximately 80% of this code was generated using Cursor AI
  
## APIs 
### Projects
- List user's projects
- Create new project
- Get project details
- Update project
- Delete project
- Transfer ownership (TBD)
- Leave project
- Archive project (TBD)
- Unarchive project (TBD)

### Project Members
- List project members
- Add member
- Change member role
- Remove member

### Project Goals
- List project goals
- Create goal
- Get goal details
- Update goal
- Delete goal

### Tasks
- List project tasks
- Create task
- Get task details
- Update task
- Delete task
- Mark complete (toggle key)
- Assign task

### Issues
- List project issues
- Create issue
- Get issue details
- Update issue
- Delete issue
- Update status
- Update priority
- Assign issue

### Forums (Public or Project-related Private Forums) 
- List forum threads
- Create thread
- Get thread details
- List comments
- Add comment
- Update comment
- Delete comment

### Chat
- Get chat messages
- Send message

### Notifications
- List notifications
- Mark all as read
- Mark as read
- Mark as unread

### Repository
- List QMS documents
- Add QMS document
- Update QMS document
- Delete QMS document
- List project files
- Upload file
- Update file 
- Delete file
- List tailoring documents
- Add tailoring document
- Update tailoring document
- Delete tailoring document
- Set Doc-ID generation rules
- Generate document ID

### Timesheets
- List timesheet entries
- Log time entry
- Update time entry
- Delete time entry
- List project timesheets
- Get project summary

### Reports (TBD)
- Project summary report
- List quality reports
- Create quality report
- Update quality report
- Delete quality report
- Workload report
- Timesheet report
- Export reports

### Search
- Search projects

### Dashboard
- User dashboard
- Project-specific dashboard

## Authentication

## Permissions
The API implements role-based access control:
- **Public**: Registration and login
- **Authenticated**: Most endpoints require authentication
- **Project Member**: Access to project-specific resources
- **Project Staff**: Can manage tasks, issues, and members
- **Project Owner**: Full control over project
- **Admin/Superuser**: Access to QMS documents and system-wide features






