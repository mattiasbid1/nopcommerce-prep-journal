WEEK 5: DevOps, Deployment, Testing, & Security (60h)
Goals:

    Deploy and maintain NopCommerce in different environments.

    Learn testing and security best practices.

Day 1–2: Deployment (Local IIS, Azure, Docker) [12h]

    Deploy NopCommerce to:

        Local IIS (with custom domain)

        Azure App Service (use free trial)

        Docker container (if familiar)

    Practice moving database between environments.

    Troubleshoot issues, read logs.

Resource:

    NopCommerce Docs: Deployment

    Deploying ASP.NET Core to Azure

    NopCommerce Docker

Day 3: CI/CD Pipelines [8h]

    Set up a basic GitHub Actions workflow:

        Lint, test, and build on push.

    If time: Set up Azure DevOps pipeline for deploy on merge.

Resource:

    GitHub Actions for .NET Core

    YouTube: GitHub Actions + .NET

Day 4: Automated & Manual Testing [8h]

    Unit testing in .NET (xUnit, MSTest, or NUnit).

    Write unit tests for your plugins/services.

    Try basic UI tests with Selenium or Playwright.

    Learn about mocking/stubbing dependencies.

Resource:

    MS Docs: Unit Testing .NET

    Playwright .NET Docs

Day 5: Security in NopCommerce [8h]

    Learn how authentication & roles work.

    Study how user passwords are stored (hashed/salted).

    Research common web security threats (OWASP Top 10).

    Practice exploiting/test-fixing a simple vulnerability (e.g. XSS in custom plugin).

Day 6: Database Admin [8h]

    Backup/restore your SQL database.

    Write migration scripts for evolving schema.

    Test rollback of changes.

Day 7: Monitoring & Logging [8h]

    Learn where NopCommerce logs go (file, db, etc.).

    Integrate with a logging/monitoring tool if possible (e.g. Seq, Application Insights).

    Practice tracking and resolving an error.

Mini-Project (End of Week 5):

    Deploy your extended NopCommerce with your custom plugin to a cloud or local IIS, show it to a friend or mentor.

    Write a “deployment checklist” and “bug report template”.