# Dad Joke Search & Management Application  

## Introduction
This task is one of your first steps in working with us at Wysi!
As part of of the application process, we would like you to complete a small task so we can get a better understading of the way you work, and how you would approach a problem.

## The Stack
At Wysi, we have a close partnership with a CMS & CRM called [Siteglide](https://www.siteglide.com/), which is built on top of [PlatformOS](https://www.platformos.com/); Therefore, all features in PlatformOS are available for you in Siteglide. This close relationship means that we have some of the best knowledge about the platform, soon you will too!

### Technologies
When using Siteglide, the three main technologies you will use (Aside from HTML, CSS & JS), will be [Liquid](https://documentation.platformos.com/api-reference/liquid/introduction), [GraphQL](https://graphql.org/learn/) and [YAML](https://en.wikipedia.org/wiki/YAML). These are relatively novel technologies, so we don't expect you to be an expert straight away, but you should soon realise the power of them combined, especially if you're coming from a front end stack.

## Minimum Requirements  

- **Proxy API Request:** Use **Liquid, GraphQL, and YML** to create an internal API endpoint that proxies requests to the icanhazdadjoke API.  
- **Fetch and Display Jokes:** Use **JavaScript** to call the internal endpoint and display jokes dynamically.  
- **Search Field:** Allow users to query jokes by **keyword**.  
- **Result Customization:** Let users adjust the **number of results returned** dynamically.  
- **Clear Search:** Implement a button to **reset the search field and results**.  
- **Favorites List:** Allow users to **"Favorite"** jokes and store them in platformOS **user session** for persistence.  
- **Caching:** Use **fragment cache** to store previously searched terms and reduce API calls.  

---

## Expanded Challenge Features  

### Improved UI and UX  
- Display a **loading indicator** while fetching results.  
- Use **Tailwind CSS or another framework** to create a clean and modern design.  

### Filtering and Sorting Options  
- Add a **sort feature** to arrange jokes alphabetically, descending and ascending.

### Sharing Functionality  
- Implement a **one-click sharing feature** to copy joke to clipboard.

## Deliverables  

- A fully functional **Dad Joke Search Page**  
- A live demo hosted on **platformOS/Siteglide**  
- A GitHub repository with  codebase

This task ensures that the new employee gains experience in **backend API development, frontend interactivity, caching strategies, and modern web development practices.**

### Hints
[More Info](https://documentation.platformos.com/developer-guide/notifications/creating-api-call-notification#step-1-create-api-call-notification)(Ignore step 2b and invoke directly with a [GraphQL tag](https://documentation.platformos.com/api-reference/liquid/platformos-tags#graphql)).
