In 2016: Deputy Manager in charge of French and Thai teams.

Built a fully automated system to analyze and manage crashes sent from the client side software Eikon by a homemade crash reporter.
Using agile methodology, daily Scrum stand up, Kanban, in charge of the deployment (Dev, Prod and client side), we produced:

Front-end:
* Create a C++ Library to catch Native and Managed crashes, generate dumps, gather data on a multi process application.
* Create a WPF Application to generate dumps of another process, upload crashes to back-end using BITS or Web Services.

Back-end:
* Create and manage a SQL Server Database (tables, Triggers, security).
* Create a C# Entity Framework Repository library to be used on all back end projects.
* Create ASP.net Web Services and BITS server to receive, store dumps, and use HangFire to launch the dump analysis.
* Create a C# Windows Service to extract info from dumps using WinDBG; Analyze results and categorize them by issue types.
* Create an ASP.net MVC web portal to display dumps info as data tables, statistics, graphs or world maps; Issue management including feature to categorize dumps automatically and interact with Jira; Special pages for support or dev teams; Create an OAuth2 library based on Katana to manage security using company authentication system.

Created Eikon services in C++ and C#; Created multi-thread and thread-safe client to access a hosted file system on Thomson Reuters private Cloud. Worked on compilation process, development tools.
