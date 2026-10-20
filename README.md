# SkillShare — Social Learning Platform

SkillShare is a social learning platform designed to help users share knowledge, connect with learners, organize learning activities, and track personal development. The platform combines social networking features with structured learning plans, progress monitoring, achievement tracking, and user engagement tools.

## Core Features

### 1. User Management & Authentication
- User registration and login with OAuth 2.0 support.
- Profile creation and management.
- Password updates and account management.
- Email and username validation.

### 2. Social Networking
- Create, view, edit, and delete posts.
- Comment on posts and manage discussions.
- Like and unlike posts.
- Follow and unfollow users.
- Display follower and following counts.
- Personalized feed featuring posts from followed users.

### 3. Learning Management & Progress Tracking
- Create and manage learning plans with start and end dates.
- Organize learning plans using resources, tasks, and milestones.
- Mark learning activities as completed.
- Track progress using statuses such as *Not Started*, *In Progress*, and *Completed*.
- Monitor achievement levels and completion percentages.
- Filter learning progress by status, category, type, and difficulty level.
- Share completed achievements with the community.

### 4. Discovery & Exploration
- Browse trending and recently published posts.
- Discover new users and follow their profiles.
- Explore user profiles and their published posts.
- Find learning inspiration through community content.

### 5. Administration
- Admin-to-user messaging system.
- Create and manage platform announcements.
- Administrative dashboard for platform management.

### 6. Notifications
- Notifications for relevant user interactions and platform activities.
- Keep users informed about social engagement and updates.

## Technology Stack

| Component | Technologies |
|---|---|
| Frontend | React 19, Vite |
| Styling | Tailwind CSS |
| State Management | Redux |
| Routing | React Router |
| Backend | Java, Spring Boot |
| Database & Backend Services | Supabase |
| Animations | Framer Motion |
| Icons | Lucide React, Heroicons |
| PDF Generation | jsPDF |
| Date Handling | date-fns |

## Project Objectives

- Encourage collaborative and community-driven learning.
- Help users organize learning goals into manageable plans.
- Provide clear visibility into learning progress and achievements.
- Build meaningful connections between learners.
- Create an engaging environment for sharing knowledge and resources.

## Getting Started

### Prerequisites

Ensure the following tools are installed before setting up the project:

- Node.js and npm
- Java Development Kit (JDK)
- Maven
- Git
- A configured Supabase project

### Installation

**1. Clone the repository**

```bash
git clone <your-repository-url>
cd SkillShare
```

**2. Install frontend dependencies**

Navigate to the frontend directory, or the project root if it contains the frontend `package.json`:

```bash
npm install
```

**3. Configure environment variables**

Create a `.env` file in the frontend directory and add the required configuration, using the variable names expected by your application.

**4. Start the frontend**

```bash
npm run dev
```

**5. Run the Spring Boot backend**

From the backend directory, use the Maven wrapper if it is included in the repository:

```bash
./mvnw spring-boot:run
```

On Windows, use:

```powershell
.\mvnw.cmd spring-boot:run
```

Ensure the backend configuration, database connectivity, and required environment variables are set before starting the application.

> **Note:** Update the directory names, environment variable names, and setup commands to match the actual repository structure and configuration.

## Security & Configuration

- Keep sensitive credentials out of source control.
- Validate and sanitize user input on the server.
- Apply appropriate authentication and authorization rules.
- Protect administrative endpoints with role-based access control.
- Configure database access policies and environment-specific settings.

## Future Enhancements

- Advanced learning recommendations.
- Search and filtering for learning resources.
- Real-time notifications and messaging.
- Learning analytics and personalized insights.
- Additional achievement and gamification features.

## License

Specify the project's license here if it is intended for public distribution.
