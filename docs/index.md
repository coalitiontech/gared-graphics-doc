# Welcome to the Gared Graphics WordPress documentation

This documentation shows you how to update your website yourself: the text and photos on each page, your contact details, menus, portfolio projects, blog posts and the forms on the Contact page.

Your site runs on **WordPress**, with a custom theme built by Coalition Technologies to match your design. Most of what you see can be changed from the WordPress dashboard without touching any code.

## Logging in

1. Go to **/wp-admin/** on your website (add it to the end of your website address).
2. Enter the username and password you were given, then click **Log In**.
3. You'll land on the **Dashboard**. The menu on the left takes you everywhere you need to go.

!!! tip
    While you're logged in and viewing your site, a dark bar at the top of every page gives you shortcuts such as **Edit Page** and **Customize**.

## Where things are

| In the left menu | What you change there |
|---|---|
| **Pages** | The content of Home, About Us, Services, Portfolio, Contact Us and the other pages (see [Editing pages](editing-pages.md)) |
| **Posts** | Your blog articles and their categories (see [Blog posts](blog-posts.md)) |
| **Portfolio** | Your portfolio projects and their categories (see [Portfolio projects](portfolio-projects.md)) |
| **Media** | Every image and file you've uploaded (see [Images](images.md)) |
| **Forms** | Messages and quote requests sent through the website's forms (see [Forms](forms.md)) |
| **Appearance → Customize** | Logo, contact details, header, footer, social links and other site-wide settings (see [Site settings](site-settings.md)) |
| **Appearance → Menus** | The links in the header and footer menus |

## Please don't change

Some areas control how the site is built rather than what it says. Changing them can break the layout, so please leave them as they are, or ask us first:

- **ACF** (field groups): these define the editing fields for each section of your pages.
- **Appearance → Themes**: switching theme would replace your site's design.
- **Appearance → Customize → Additional CSS**: code that changes the site's styling.
- **Plugins**: they power the forms, the editing fields and backups.

## In this documentation

- [Editing pages](editing-pages.md): how the page editor works, the page header, and the kinds of fields.
- What's on each page: [Home](pages/home.md), [About Us](pages/about.md), [Services](pages/services.md), [Portfolio](pages/portfolio.md), [Contact Us](pages/contact.md).
- [Portfolio projects](portfolio-projects.md): adding projects and their categories.
- [Blog posts](blog-posts.md): writing posts, categories and comments.
- [Forms](forms.md): reading messages and quote requests, and who gets the emails.
- [Images](images.md): sizes, file names and alt text.
- [Site settings](site-settings.md): logo, contact details, header and footer, social links, menus.

!!! note "For developers"
    Custom WordPress theme (*Gared Graphics*) with page sections built as ACF Pro blocks; field definitions are saved as JSON in the theme (`acf-json/`), so change them in code, not under ACF in the dashboard. Forms use Gravity Forms. Theme code is managed in its own git repository.
