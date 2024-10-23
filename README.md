
# 🏥 HealthCare Management System

A comprehensive healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors. It includes administrative tools for scheduling, confirming, and canceling appointments, and sends SMS notifications for appointment confirmations, all built with modern web technologies.

## ⚙️ Tech Stack

- **Next.js** - React framework for server-side rendering and building full-stack applications.
- **Appwrite** - Backend as a service for managing authentication, database, storage, and more.
- **TypeScript** - Strongly typed JavaScript for better maintainability and catching errors early.
- **TailwindCSS** - Utility-first CSS framework for rapid UI development.
- **ShadCN** - Provides component libraries.
- **Twilio** - SMS service for sending notifications.
- **Sentry** - Error and performance tracking to monitor application health.

---

## 🔋 Features

- **Patient Registration**: Users can sign up and create a personal profile as patients.
- **Book Appointments**: Patients can schedule appointments with doctors and book multiple appointments as needed.
- **Admin Appointment Management**: Administrators can efficiently view, manage, and track all scheduled appointments.
- **Confirm/Schedule Appointments**: Admins can confirm and set appointment times for patients.
- **Cancel Appointments**: Administrators can cancel appointments when necessary.
- **SMS Notifications**: Patients receive SMS confirmation for their appointments via Twilio.
- **Fully Responsive Design**: The application works seamlessly across all device types and screen sizes.
- **File Upload Using Appwrite Storage**: Secure file storage through Appwrite for user-uploaded documents.
- **Performance Monitoring via Sentry**: Track application performance and detect errors using Sentry.
- **Scalable & Reusable Code Architecture**: Designed with reusability and scalability in mind for easy future enhancements.

---

## 🤸 Quick Start

Follow the steps below to set up the project locally.

### Prerequisites

Ensure you have the following installed on your machine:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Cloning the Repository

1. Clone the repository:

    ```bash
    git clone https://github.com/miravanisri/HealthCareManagement
    cd healthcare
    ```

2. Install the project dependencies:

    ```bash
    npm install
    ```

### Set Up Environment Variables

1. Create a new file named `.env.local` in the root of your project and add the following content:

    ```bash
    # APPWRITE
    NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
    PROJECT_ID=
    API_KEY=
    DATABASE_ID=
    PATIENT_COLLECTION_ID=
    APPOINTMENT_COLLECTION_ID=
    NEXT_PUBLIC_BUCKET_ID=

    NEXT_PUBLIC_ADMIN_PASSKEY=111111
    ```

2. Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

### Running the Project

1. Run the development server:

    ```bash
    npm run dev
    ```

2. Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

---

## 🚀 Deployment

For deploying the project to production, refer to the Next.js [deployment documentation](https://nextjs.org/docs/deployment).

---









