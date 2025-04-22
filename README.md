# Tuiter Poll Feature

## Project Overview

This project introduces a polling feature to Tuiter, enhancing user engagement by allowing users to create and participate in polls. The feature is designed to be intuitive and integrates seamlessly with the existing Tuiter platform.

## Features
- **Poll Creation**: Users can create polls with custom questions and multiple-choice answers.
- **Voting Mechanism**: Authenticated users can vote on polls and view real-time results.
- **Poll History**: Users can view a list of polls they've participated in.
- **Voter Insights**: Poll creators can see who voted on their polls, providing insights into audience engagement.

## User Stories

### 1. Creating a Poll
- As a user, I want to create a poll with a question and multiple choices so that I can gather opinions from my audience.

### 2. Voting on a Poll
- As a user, I want to vote on polls so that I can share my opinion on various topics.

### 3. Viewing Poll Participation
- As a user, I want to see which polls I've voted in so that I can track my participation.

### 4. Viewing Voter Details
- As a poll creator, I want to see who voted on my polls so that I can understand my audience better.

## Technical Stack

- **Frontend**: React, TypeScript
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT), Session management
- **Testing**: Jest, React Testing Library
- **Deployment**: (Optional: Vercel, Heroku, or custom server)

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone git@github.com:your-username/tuiter-poll-feature.git
   cd tuiter-poll-feature
2. **Install Dependencies**
   ```bash
   npm install
3. **Create a .env file**
   Inside the root directory, create a .env file and add:
   ```bash
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
4. **Start the development server**
   ```bash
   npm run dev
5. **Run tests**
   ```bash
   npm test


## Submission Notes

- This README summarizes the feature pitch and design expectations.
- The implementation will span 5 weeks and follow best practices for maintainability and collaboration.

---

*Fall 2022 – CS5500 Software Development*  
*Team of 4 students*
