# Introduction
In an increasingly fast-paced world full of distractions, keeping track of our daily tasks can be a challenge. The need for a simple, intuitive, and effective tool to manage our personal and professional responsibilities has become crucial to improving productivity and organization.

This project aims to develop a mobile to-do list application that allows users to plan, organize, and efficiently track their pending tasks. Although there are other similar solutions, this application seeks to offer an optimized and accessible experience, maintaining a clear focus on simplicity and effectiveness.

The application will be designed to be lightweight, fast, and accessible, offering essential features such as the creation, editing, sorting, and deletion of tasks, subtasks, and task lists; marking tasks as completed; organizing by categories; synchronization between devices; collaboration between users; and personalized reminders.

The primary purpose of this application is to provide a flexible tool for both casual users who only want to track their daily tasks and those looking for a system to manage simple projects, thus adapting to the needs of a diverse audience.

# The problem

## Lack of organization
Many people struggle to organize their tasks and responsibilities, which can cause stress and decrease productivity. Without a clear structure, it's easy to forget important tasks or not know where to start.

## Difficulty prioritizing tasks
People often have trouble deciding which tasks are more important or urgent, which can lead to poor time management and the failure to complete critical tasks.

## Procrastination and lack of follow-up

It is common for people to postpone tasks, especially when they don't have an effective method to monitor their progress or receive reminders.

## Synchronization issues between devices

In a world where we use multiple devices (phones, tablets, computers), many people struggle to keep their task lists updated across all their devices. Often, they end up losing track or duplicating their efforts.

## Collaboration and simple project management

In some contexts, people need to share tasks or lists with others, whether in a family, academic, or professional environment. Without the right tool, coordinating with others can be complicated.

## Feature overload in more complex applications

Some task management applications offer so many advanced features that they become confusing for the average user, leading to confusion and demotivation.

# Stakeholders

## Me. Software Engineer

My main interest is to improve my technical skills and gain experience in mobile application development, API usage, and databases. Additionally, I am interested in creating a functional application that can be useful to me and others. Residually, it would be great to gain some economic benefit from this application.

My responsibilities will be the following:

- Define and plan the project.
- Define and develop all system functionalities.
- Ensure the application is stable, secure, and meets user expectations.
- Maintain the code, perform testing, fix bugs, and update the application when necessary.

## End users

End users are those who will use the application to manage their daily tasks. Their main interest lies in the app being easy to use, accessible, and fulfilling the promised features (lists, tasks, synchronization, reminders, etc.). They want to improve their productivity and have a tool that helps them organize without complications.

They don't have direct technical responsibilities, but their feedback is key to the evolution and improvement of the application.

Among them, we can find different profiles, such as:

- Busy workers
- Students
- Entrepreneurs
- Freelancers
- Busy parents
- People looking to improve their personal organization
- Small work teams or collaborative projects
- People with attention deficit or organization issues

## UX/UI Designer

Must ensure that the application has an attractive interface and is easy to use for the end user.

Their responsibilities will be as follows:

- Design the screens and flow of the application so that the user experience is intuitive.
- Create a visually appealing and functional design alongside the developer.
- Ensure that design decisions do not hinder the performance or accessibility of the application.

## Marketing expert

Will help the application gain visibility in the market and attract users. If it is decided to monetize the application, a marketing expert can be key to maximizing revenue.

Their responsibilities within the project will be:

- Promote the application through different channels (social networks, advertising campaigns, etc.).
- Define user acquisition and retention strategies.
- Manage relationships with media, influencers, and other promotional channels.

## Monetization services

If advertising or in-app purchases are implemented, they can provide a way to generate revenue through the application.

They are responsible for:

- Facilitating the integration of ad platforms or payment systems for in-app purchases.
- Ensuring that transactions and ads work efficiently without affecting the user experience.
- Maintaining security and compliance with local and international regulations on digital transactions.

## Cloud service providers

Offer infrastructure services (cloud storage, authentication, databases, etc.) for the application to function correctly.

Their responsibilities are:

- Ensure that backend services (such as databases or authentication) function stably.
- Provide an easy-to-integrate service and technical support when problems arise.
- Maintain the security and availability of services used by the application.

## App distribution platforms

Must facilitate the distribution of the application to users and ensure it complies with their quality, security, and user experience policies.

Their responsibilities will be as follows:

- Review and approve the application before it is published on their platforms.
- Ensure that the application is available to users and that updates are distributed smoothly.
- Provide metrics and statistics on the performance and acceptance of the application on their platforms.

## Companies developing other task list applications

They will try to maintain or increase their market share, differentiate themselves from the competition through improvements in their application, and perhaps observe our behavior. This will make it more difficult for users to adopt our application.

They can also set trends on what features are considered standard or necessary in a task list application.

They are part of the competitive ecosystem and influence user expectations. They don't have a responsibility for the success of our project, but they will determine the context in which the application will move and grow.

Below is a list of similar applications developed by competing companies:

- [Todoist](https://play.google.com/store/apps/details?id=com.todoist)
- [Microsoft To-Do](https://play.google.com/store/apps/details?id=com.microsoft.todos)
- [Trello](https://play.google.com/store/apps/details?id=com.trello)
- [Asana](https://play.google.com/store/apps/details?id=com.asana.app)
- [Google Keep](https://play.google.com/store/apps/details?id=com.google.android.keep)
- [Any.do](https://play.google.com/store/apps/details?id=com.anydo)

# The product

## Product perspective

The product will consist of a complete system designed to provide a smooth task management experience, composed of the following components:

### Native mobile application

- Developed for iOS and Android mobile platforms.
- Will provide the user interface.
- Will integrate the functions that the application will have.
- Will allow offline task management, with automatic synchronization when the device regains internet connectivity.

### Server

- Will act as the central coordination point for all functionalities that require network communication, such as task synchronization between devices and collaboration between users.
- Can serve as a link between the application and third-party services.
- Will be responsible for communicating the application with the database.

### Database

- A cloud database will be used to securely store user information, including task lists, categories, completion statuses, and user preferences.
- Will ensure system scalability, supporting user and data growth without compromising performance.

## Product description

The product will consist of a mobile task list management application that will allow users to organize, prioritize, and track their daily activities. It will be designed to be intuitive, lightweight, and accessible, with the following main functionalities:

### Creation, editing, and deletion of task lists

- Users will be able to create task lists to organize their activities into specific projects or categories.
- Lists will also be editable (for example, changing the name of a list) and can be deleted when no longer needed.

### Manual sorting of task lists

Users will be able to manually organize their task lists through a drag and drop interface. This will allow users to prioritize lists, putting the most important or active ones at the top.

### Creation, editing, and deletion of tasks

- Users will be able to create individual tasks and assign them a name.
- Each task will be editable, allowing users to modify its content at any time.
- Tasks can be deleted when no longer needed.

### Marking tasks as completed

Once a task is completed, users will be able to mark it as finished, helping them track their progress.

### Manual sorting of tasks

Users will be able to manually organize their tasks through a drag and drop interface. This will allow users to prioritize tasks, putting the most important or active ones at the top.

### Subtasks

- Each task can have a series of associated subtasks, which will serve to divide larger tasks into smaller, manageable tasks.
- Subtasks will behave in the same way as tasks and will be nested under their "parent" task.
- When all subtasks are completed, the "parent" task can also be marked as completed.
- Subtasks will be allowed up to a third level of depth (for example, "task 1", "task 1.1", "task 1.1.1").

### Organization by categories

Users will be able to assign categories to lists (for example, "Work", "Personal", "Studies"), which will allow them to organize their lives more easily and filter lists by context.

### Custom reminders

- The application will offer the option to set custom reminders for lists and tasks, based on specific dates and times.
- Reminders can be configured to alert the user at key moments through push notifications.
- Notifications will suggest rescheduling the task or marking it as completed if the due date is approaching.

### Cloud synchronization

The application will synchronize with a cloud server, allowing tasks and lists to be available on all devices where the user has logged in.

### User collaboration

The application will allow collaboration on task lists, which can be shared between users (for example, family members, friends, coworkers, classmates, etc.) to work together on common projects. Collaborators will be able to add, edit, delete, or complete tasks.

### User management and authentication

- Users will need to register in the application using email or third-party authentication (such as Google or Apple).
- The application will manage secure authentication and maintain active user sessions on all devices where the user has logged in.

### Offline handling

Users will be able to manage their lists and tasks without an internet connection, and modifications will automatically synchronize when the device comes back online. They will receive a visual indication when working offline.

### Customizable interface

Users will have basic interface customization options, such as changing themes (dark/light mode) or modifying the display color of lists to suit their preferences.

## Operating assumptions

### Use of devices compatible with the mobile application

To ensure optimal performance, it is assumed that users will use relatively recent devices, with adequate hardware resources (memory, processor) and operating system versions.

### Availability of internet connection for synchronization

Synchronization between devices and collaboration between users require a stable connection to keep data updated on all devices.

### User registration and authentication for synchronization

Authentication is necessary to manage each user's personal lists, ensure secure synchronization between devices, and allow collaboration between different users.

### User actions to organize their lists and tasks

The application offers flexibility, but requires users to adopt proactive practices to properly manage their activities and take advantage of all functionalities.

### Access to push notifications for reminders

Notifications are essential for the functionality of reminders and to keep the user informed of tasks that require attention.

### Devices with sufficient local storage

Offline functionality requires lists and tasks to be temporarily stored on the device.

### Cloud storage capacity

To ensure a smooth experience and that data is stored securely and persistently, a reliable and scalable cloud storage service is needed.

### Compatibility with app distribution platforms

For the application to be accessible to users, it must meet the requirements of app distribution platforms and be available for download.

### Availability and stability of the server and database

Continuous server operation is critical for key functionalities (such as synchronization and multi-user access) to be available at all times.

## Dependencies on other external systems

### Third-party authentication services

The application will allow users to register and log in using third-party authentication services, which facilitates authentication and improves user experience. These services provide fast and secure login, reducing friction when registering.

### App distribution platforms

The application will depend on app distribution platforms to be distributed and updated on users' mobile devices.

### Cloud service provider

A cloud service provider will be needed to host the database and handle synchronization of lists and tasks between devices. It will also provide the necessary backend services for user management, data storage, and system scalability.

### Payment systems

In case of integrating monetization models, a payment system will need to be integrated to process transactions securely.

## Non-Functional requirements

### Performance

The application must be fast and lightweight, ensuring quick response times even with a large number of lists and tasks.

### Scalability

The system must be designed to grow seamlessly as the number of users increases, without experiencing a performance drop of more than 10% in server response time and without data loss.

### Availability

The application must have an availability of at least 99.9% over any 30-day period, which equates to a maximum of 43.2 minutes of downtime per month.

### Security

All user information must be encrypted. There must be no security breaches for 100% of authenticated requests.

### Compatibility

The application must be compatible with Android and iOS devices, ensuring it works correctly on iOS versions 15+ and Android 11+.

### Maintainability

The code must be well-structured and documented to facilitate future modifications, bug fixes, and the addition of new features. The use of design patterns, unit testing, and good development practices is key to maintaining the system in the long term.

### Usability

The interface must be intuitive and easy to use. Users should be able to complete common tasks without the need for extensive instructions or training. The UI design should follow user-centered design principles, ensuring a smooth and satisfying experience.

### Portability

User data should be easily migratable between devices, allowing synchronization between them. If a user changes devices, they should be able to retrieve their information effortlessly through cloud synchronization.

### Reliability

The system must operate consistently and without failure. Data loss or critical errors must be minimal, and in case of failure, the application must recover automatically with minimal user intervention.

### Responsiveness

The application must react swiftly to user interactions. For example, there should be no delays when dragging and dropping lists or tasks. The goal is for the user experience to be smooth and without noticeable delays.

### Privacy

User data must be handled responsibly, complying with data protection regulations. Users must have control over their information and be able to delete their accounts and data whenever they wish.

### Monitoring and logging

The system must have tools to monitor performance and usage, as well as log potential errors or anomalies. This will allow for the proactive identification and correction of issues, improving stability and user experience.

### Internationalization

The application must be designed to support multiple languages and easily adapt to different regions and cultures. This includes the ability to change the language of the interface and adapt date and time formats to the user's locale.
