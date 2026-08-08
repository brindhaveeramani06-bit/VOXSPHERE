# Problem Statement

## 1. Title
VoxSphere – A Voice-Based Social Communication Platform

## 2. Domain
Social Networking / Real-Time Communication

## 3. Who is the User?
### User
- Register and Login
- Join voice rooms
- Participate in voice discussions
- Chat with other users
- Vote in polls and ask questions

### Host
- Create and manage voice rooms
- Approve speakers
- Mute/Unmute participants
- Manage discussions

### Admin
- Manage users
- Manage rooms
- Review reports
- Ban/Unban users

## 4. What Problem Are We Solving?
Existing communication platforms are often designed for either messaging, meetings, or language exchange, making it difficult to build topic-based voice communities with interactive participation. Users need a platform where they can communicate through live voice discussions, participate in polls and Q&A sessions, and interact safely through moderation features.

## 5. Proposed Solution
VoxSphere is a web-based voice communication platform that enables users to create and join voice rooms, communicate in real time, participate in live polls and Q&A sessions, follow other users, and interact securely using JWT authentication and role-based access control. Hosts can manage discussions, while administrators can monitor and moderate the platform.

## 6. Core Entities / Database Tables
- Users
- Roles
- Rooms
- Room_Members
- Messages
- Polls
- Poll_Options
- Poll_Votes
- Questions
- Reports
- Follows
- Subscriptions

## 7. User Roles & Permissions

### User
- Register/Login
- Join Rooms
- Participate in Voice Chat
- Vote in Polls
- Ask Questions
- Report Users

### Host
- Create/Delete Rooms
- Approve Speakers
- Mute/Unmute Participants
- Start Polls
- Manage Discussions

### Admin
- Manage Users
- Manage Rooms
- Review Reports
- Ban/Unban Users

## 8. Success Criteria
- Users can register and log in securely.
- Users can create and join voice rooms.
- Voice communication works in real time.
- Hosts can manage participants.
- Users can participate in polls and Q&A.
- Admins can moderate the platform effectively.

## 9. Out of Scope
- Video Calling
- Screen Sharing
- Payment Gateway
- Mobile Application
- AI-based Features (Future Enhancement)

## 10. Chosen Track
Java (Spring Boot) + React.js + MySQL