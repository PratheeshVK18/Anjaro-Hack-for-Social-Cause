ANJARO – PDS-on-Wheels

Smart & Inclusive Ration Delivery Platform

Team Name: ONE DREAM
Team ID: HSC|TN|02646
Team Lead: Pratheesh K
Institution: Sri Sairam Engineering College, Tamil Nadu, India
Theme: Rural Development & Livelihoods

1. Project Overview

ANJARO – PDS-on-Wheels is a digital platform designed to improve access to Tamil Nadu's Public Distribution System (PDS). It aims to make ration booking more convenient through digital services, doorstep delivery, real-time stock visibility, and GPS-based delivery tracking.

The platform focuses on improving accessibility for rural households, elderly citizens, and people with mobility challenges while promoting transparency and efficiency in ration distribution.

2. Problem Statement

Ration beneficiaries may experience several challenges when accessing Fair Price Shops:

Long queues and waiting times.

Travel difficulties, particularly for rural households and elderly citizens.

Limited visibility into ration stock availability.

Difficulty tracking delivery progress.

Accessibility barriers for people with mobility limitations.

ANJARO aims to address these challenges through a convenient and inclusive digital ration booking and delivery system.

3. Proposed Solution

ANJARO connects beneficiaries, Fair Price Shops, and delivery personnel through a digital platform. Users can select ration items, check stock availability, request delivery slots, and track their orders.

The platform combines digital booking, delivery coordination, verification mechanisms, and accessibility features to support a more efficient ration distribution process.

4. Key Features

Digital Ration Booking: Select ration items and submit booking requests.

Doorstep Delivery: Support convenient delivery of essential ration supplies.

Live Stock Visibility: View available ration stock information.

GPS Delivery Tracking: Monitor delivery progress using location services.

OTP/QR Verification: Support beneficiary authentication and delivery verification.

AI-Assisted Route Optimization: Help identify efficient delivery routes.

Tamil IVR Support: Improve accessibility through Tamil-language voice assistance.

Offline-Friendly Access: Support users experiencing limited internet connectivity.

Delivery Slot Selection: Request a suitable delivery time.

Administrative Management: Support inventory, booking, and delivery coordination.

Note: Features described as proposed or planned should be identified as such if they are not yet implemented in the current prototype.

5. System Architecture

The proposed architecture consists of the following modules:

Beneficiary Interface: Registration, login, ration selection, and booking.

Fair Price Shop Module: Stock updates and booking management.

Backend and APIs: Communication between application modules.

Database: Storage of beneficiary, inventory, and booking information.

Delivery Management: Delivery assignments and order status updates.

GPS and Route Optimization: Location tracking and delivery route planning.

OTP/QR Verification: Verification during the delivery process.

Admin Dashboard: Monitoring and managing system activities.

Architecture Diagram

flowchart TD
    A[Beneficiary App] --> B[Backend and REST APIs]
    C[Fair Price Shop Module] --> B
    D[Delivery Personnel Module] --> B
    B --> E[Database]
    B --> F[Booking and Inventory Management]
    B --> G[GPS Tracking and Route Optimization]
    B --> H[OTP and QR Verification]
    B --> I[Admin Dashboard]

6. Technology Stack

The application uses or is intended to use technologies from the following categories. Update this section to match the technologies actually implemented in the repository.

Component

Technology

Frontend

Add the actual framework used

Backend

Add the actual language and framework

Database

Add the actual database

API Communication

REST APIs, if implemented

Maps and GPS

Add the actual maps service

AI/ML

Add the actual route optimization approach

Version Control

Git and GitHub

7. Installation and Setup

Prerequisites

Install the tools required by the actual project, such as Git, the appropriate runtime, and the required package manager.

Clone the Repository

git clone <YOUR_PUBLIC_REPOSITORY_URL>
cd <YOUR_REPOSITORY_FOLDER>

Install Dependencies

Run the installation command appropriate for your technology stack.

For a Node.js project with a valid package.json, use:

npm install

Environment Configuration

Create a .env file containing the environment variables required by your implementation. Never commit secrets, passwords, or private API keys.

Example template:

APP_PORT=
DATABASE_URL=
MAPS_API_KEY=

Remove variables that your application does not use and document the actual configuration requirements.

Run the Application

For a Node.js project with a configured development script:

npm run dev

Use the actual startup command defined in the repository.

8. Application Workflow

The beneficiary logs in to the platform.

Available ration items and stock information are checked.

The beneficiary selects items and requests a delivery slot.

The Fair Price Shop confirms the booking and stock.

The delivery is assigned and the route is planned.

The beneficiary tracks the delivery status.

OTP/QR verification is performed at the appropriate handover stage.

The order status is updated after delivery.

9. Testing

The following test cases should be used to validate the application:

Registration and login validation.

Ration item selection and booking.

Stock availability and booking confirmation.

Delivery slot selection.

GPS tracking and delivery status updates.

OTP/QR verification success and failure.

Invalid input and unauthorized access.

Offline and poor-connectivity behaviour.

Delivery assignment and route optimization.

Add actual test files, execution commands, and test results to document verified functionality.

10. Security and Privacy

Protect beneficiary information and authentication credentials.

Keep API keys and secrets out of version control.

Apply appropriate access controls to beneficiaries, shop personnel, delivery staff, and administrators.

Validate application inputs and API requests.

Collect only the data required for the service.

Use anonymized or synthetic sample data in public demonstrations.

11. Expected Impact

ANJARO aims to:

Reduce unnecessary travel and waiting time.

Improve visibility of ration stock and delivery progress.

Support more convenient access to essential food supplies.

Improve delivery coordination and operational efficiency.

Promote inclusive access for elderly citizens and people with mobility challenges.

Strengthen transparency in ration distribution.

12. UN Sustainable Development Goals

ANJARO aligns with the following UN Sustainable Development Goals:

SDG 2 – Zero Hunger: Supports convenient access to essential food supplies.

SDG 9 – Industry, Innovation and Infrastructure: Applies digital technology to public service delivery.

SDG 10 – Reduced Inequalities: Aims to improve access for underserved beneficiaries.

SDG 16 – Peace, Justice and Strong Institutions: Promotes transparency and accountability.

Reference: United Nations Sustainable Development Goals

13. Limitations and Future Scope

Potential future enhancements include:

Integration with authorized Public Distribution System services.

Improved Tamil voice assistance and accessibility.

Reliable offline data synchronization.

Enhanced route optimization and delivery scheduling.

Multilingual support and beneficiary feedback.

Pilot deployment with participating Fair Price Shops.

Integration with government systems or live inventory services should only be claimed after it has been implemented and authorized.

14. Team

ONE DREAM – Hack for Social Cause

Pratheesh K: Team Lead

Lohithkrishna Y: Team Member

Dhavakrishnaa Murugesan: Team Member

Institution: Sri Sairam Engineering College, Tamil Nadu, India.

15. Repository Contents

The repository should include:

README.md – Project overview and setup instructions.

Source code – Application implementation.

docs/ – Technical design and architecture documentation.

tests/ – Test cases and testing instructions.

sample-data/ – Safe sample data for demonstration.

.env.example – Example configuration without secrets.

LICENSE – Open-source license.

Include only files and directories that actually exist in the repository.

16. License

Add an appropriate open-source license after confirming that the team has the rights to distribute all included code and assets.

For example, if the team chooses the MIT License, include the standard MIT License text in a file named LICENSE and identify the correct copyright holder.

Project: ANJARO – PDS-on-Wheels
Team: ONE DREAM
Registration ID: HSC|TN|02646
Theme: Rural Development & Livelihoods
Institution: Sri Sairam Engineering College, Chennai, Tamil Nadu, India
