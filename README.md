# MODERN-FULLSTACK-INTERNSHIP-SSUUBI-STEPHEN
A full-stack web application for a campus help desk, allowing students to submit and track service tickets.
#USER ROLES
Student (Enduser)
  Permissions
    -Submit tickets: Create new help requests
    -Track status: View updates on their open tickets
    -Manage profile: Access personal information and ticket history
Agent (Administrator)
  Permissions
    -Ticket management: View, assign, update status and close support requests
    -Communication: Reply to student messages directly through the app
    -Knowledge base access: Read and potentially update predefined FAQs or technical guides

#FIVE CORE FEATURES 
1. Ticket submission and creation portal
    -Input fields: Student name, Registration number, Issue category, detailed description
    -Attachments: Ability to upload images and documents
    -Automation: Generates a unique, trackable ticket ID automatically upon submission
2. Multi channel commenting system
    -Public comments: Direct messaging between the student and the support agent
    -Audit trail: Time stamped-logs of all comments to maintain conversational history
  Private notes: Internal collaboration space visible to only agents and staff
3. Smart ticket assignemt engine
    -Manual assignemt: Allows managers to assign a ticket to a specific agent
    -Self-assignment: Enables agents to claim unassigned tickets from a general queue
    -Reassignment: Allows agents to transfer issues to specialized teams members
4. Real-time status and life cycle tracker
    -Status states: Defines clear phases such as; New, In progress, Pending and Resolved
    -Visual labels: Uses color-coded tags to quickly identify ticket status in a list a view 
    -Status controls: Limits who can change status levels(only agents can mark tickets as resolved)
5. Configuration Support workflow automation
    -Notification triggers: Sends automatic email or app alerts when a ticket is assigned or updated
    -SLA Warnings: Flags tickets that have been sitting open or unassigned for too long 
    -Routing rules: Automatically directs tickets to specific departments based on student's chosen issue category


More features;
     
     -Code splitting to load only necessary resources i.e; use of Tailwind CSS
     
     -Real time synchronization which is very reliable with aid of modern web sockets
