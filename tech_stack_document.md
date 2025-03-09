# Tech Stack Document

## Introduction

FocusCal is a productivity and calendar management app designed specifically for students and individuals with ADHD. It combines task management, intelligent time tracking, calendar integration, and focus tools into one seamless experience. The technology choices made for FocusCal are intended to provide a secure, reliable, and highly interactive environment. These choices support rapid development, ease of maintenance, and the ability to grow and adapt as user needs evolve, ensuring that both everyday users and technical teams can engage with the project effectively.

## Frontend Technologies

For the user interface, we have chosen React as the primary framework. React enables the creation of a dynamic and responsive experience. It allows us to develop components that users can interact with easily, ensuring that features like drag-and-drop task scheduling and real-time calendar updates are smooth and intuitive. In addition, the integration of Lovable.dev helps generate both front-end and full-stack web applications efficiently, reducing development time and maintaining a consistent design language. This technology stack lends itself to a user-friendly, accessible, and visually appealing experience, matching the clear and minimalist design inspired by popular calendar models.

## Backend Technologies

On the server side, FocusCal is powered by Node.js and the Express framework. This combination provides a scalable and efficient back-end environment where requests are handled quickly, and RESTful APIs are built effectively. PostgreSQL is used as the primary database, ensuring that structured data such as user profiles, task details, and scheduling information are managed reliably. OAuth 2.0 is implemented to secure authentication and authorization, allowing safe connections with social login options like Google and Apple ID. Additionally, the backend supports intelligent time estimation through planned machine learning integration, initially using regression analysis on historical data and designed to scale into a more advanced model as the app matures.

## Infrastructure and Deployment

The project utilizes reliable cloud-based services to manage file storage and backups. AWS S3 is used to store and manage assets with secure, scalable cloud storage, ensuring that user data and media files are safely maintained. Continuous integration and deployment procedures are implemented to facilitate fast iterations and updates, while service workers ensure that offline functionality is robust and dependable. This infrastructure is complemented by source control systems and automated pipelines that ensure any updates are thoroughly tested and deployed with minimal disruption, thereby supporting both scalability and a seamless user experience across devices.

## Third-Party Integrations

FocusCal goes beyond its core functionalities by integrating with a range of third-party services. External calendar integration is achieved by connecting with platforms like Google Calendar and Apple Calendar, ensuring that users' schedules are unified in one place. The application also integrates with tools like Speechify and WordQ to support study assistance, and with learning management systems such as Moodle and Blackboard, making assignment imports and course management smooth and automated. These integrations enhance the overall functionality of the app by providing added layers of user convenience and automating many aspects of scheduling and learning management.

## Security and Performance Considerations

Security is a top priority in the FocusCal tech stack. The choice of OAuth 2.0 for authentication, combined with secure backend practices on Node.js and Express, means that user identities and data are well-protected. Data encryption is used during both transmission and storage, and two-factor authentication provides extra security at login. Performance optimization is achieved through the use of React to deliver fast, responsive front-end interactions and service workers to ensure offline access without compromising the integrity of the user experience. Regular performance audits, caching strategies, and strict conflict resolution protocols work in tandem to ensure that the application remains fast and reliable even as it scales.

## Conclusion and Overall Tech Stack Summary

The technology choices behind FocusCal are carefully selected to create an adaptive, user-friendly, and secure productivity solution. Utilizing React and Lovable.dev on the front end delivers an interactive experience that is easy to navigate. Node.js with Express supports a robust backend environment with PostgreSQL handling data reliably, while AWS S3 provides secure cloud storage. Third-party integrations with popular calendar services and study tools ensure that users have all the functionalities they need in one place. In addition, the use of OAuth 2.0 for security, service workers for offline access, and an evolving approach to machine learning for time estimation position FocusCal as a forward-thinking and comprehensive tool designed to help students and those with ADHD stay organized and productive. This tech stack is not only modern and scalable, but also closely aligned with the project’s goal of making scheduling and task management as seamless and accessible as possible.
