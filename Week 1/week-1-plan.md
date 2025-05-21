WEEK 1: NopCommerce Orientation, Environment Setup & .NET Core Fundamentals (60h)
Goals:

    Get NopCommerce running locally (source version, not just the install package).

    Learn admin and storefront inside out.

    Get comfortable with ASP.NET Core basics and Razor.

    Start a dev journal (Notion, OneNote, Google Docs, whatever you like).

Day 1–2: Environment Setup & Running NopCommerce [10h]

    Install Visual Studio 2022+ (Community or higher), SQL Server (Express or Developer), and Git.

    Clone NopCommerce GitHub repo.

        Follow official setup guide.

        Get the database created, build/run the app, seed with test data.

        Troubleshooting is part of learning!

    Test all basic workflows:

        Create products, categories, manage inventory, test cart/checkout, try discount/coupon creation, add a user, test order fulfillment.

Resource:

    NopCommerce Docs: Installation

    YouTube: NopCommerce Installation Tutorial

    SQL Server Express Download

Day 3–4: Admin & Storefront Deep Dive [10h]

    Map every admin menu. Write a "cheat sheet" with what each does.

    Try creating, editing, deleting, searching products/categories/users/orders.

    Place and process some test orders, simulate refunds, etc.

    Test all built-in widgets (banners, featured products, newsletter signup, etc.)

    Write notes on questions/oddities you find.

Resource:

    NopCommerce Admin Demo

    NopCommerce Docs: Administration

Day 5–6: Codebase & Architecture Exploration [12h]

    Read the NopCommerce architecture overview.

    Map the main projects:

        Nop.Web (MVC web app)

        Nop.Core, Nop.Services, Nop.Data, Nop.Web.Framework, Nop.Plugin.*

    Use Solution Explorer: click through folders, identify where controllers, models, views, plugins, themes, and services live.

    Open a few controllers and services, skim code and comments.

    Draw a diagram of how a product flows (DB > Data > Service > Controller > View).

    Write down 10 things you don’t understand yet—this is valuable for later.

Resource:

    NopCommerce Docs: Architecture

    NopCommerce Source Code Guide (community)

Day 7: .NET Core & Razor Fundamentals [8h]

    Do a free Pluralsight course on ASP.NET Core MVC.

    Build a mini project: a To-Do list or blog with controllers, views, and models.

    Focus:

        Routing (attribute and conventional)

        Controllers

        Models/ViewModels

        Razor syntax

    Add a few simple forms (CRUD).

Resource:

    Microsoft Docs: ASP.NET Core MVC Fundamentals

    YouTube: ASP.NET Core MVC Crash Course

Entity Framework Core Basics [6h]

    Create a new database, simple EF Core project.

    Practice adding/migrating tables, basic queries, relationships.

Resource:

    MS Docs: EF Core Getting Started

    YouTube: EF Core Tutorial

Mini-Project (End of Week 1):

    Add a field to the Product table/model (e.g. "Extra Info") and surface it on the admin side.

    Journal about challenges, wins, and open questions.