# QPMS : Quality Project Management System  

<img width="1226" height="1153" alt="image" src="https://github.com/user-attachments/assets/e651c43c-d817-4bdb-8c02-6fe45a553fb2" />




    
- https://qpms.pythonanywhere.com           qpmstest / testme01)
- Installation available for **on-premise deployment (internet connection optional)**
- **Free plan** available for independent QA consultants and freelance quality professionals
- **One-time purchase** license: £79.00 GBP (unlimited use, self-installation)
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


