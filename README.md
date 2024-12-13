# Planium - Project Management Application

Planium is a robust project management application that enables efficient task organization, team collaboration, and project tracking. Built with a scalable architecture using **Next.js** and **Express.js**, it is fully integrated with **AWS services** for enterprise-grade deployment.

## Features
- **Drag-and-Drop Boards**: Easily manage tasks across multiple projects.
- **Multi-View Options**: Switch between List, Table, and Timeline views.
- **Task Search**: Quickly find tasks across projects.
- **Team Management**: Add users, create teams, and manage roles.
- **Analytics and Visualization**: Recharts integration for insightful analytics.
- **Responsive Design**: Fully optimized for all devices with dark/light mode support.
- **AWS Integration**:
  - **Cognito**: Secure authentication with email confirmation.
  - **RDS**: Scalable PostgreSQL database.
  - **EC2 and S3**: Hosting backend and managing storage.

## Tech Stack
- **Frontend**: Next.js, Redux Toolkit, Tailwind CSS, Recharts
- **Backend**: Express.js, Prisma, PostgreSQL
- **Cloud**: AWS (Cognito, EC2, RDS, S3, Amplify)
- **Other Tools**: TypeScript, Material UI

## Deployment
The project is deployed on AWS:
- **Frontend**: Hosted on Amplify
- **Backend**: Hosted on EC2
- **Database**: Managed with RDS
- **Storage**: Images and files stored in S3

## Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/SameekshThakur/planium.git
   cd planium
