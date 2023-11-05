1. in app, we create a new page using folders
    -Add a page.tsx file for content on the landing page
    -Add a layout.tsx if we want certain things to always be on pages (like a navbar) - this is always top level
    -Subpages are created by creating a new folder in the top level folder page
        -follow step 1 to create content

2. UI folder is where we would add all of our components for particular pages
    -Create a new folder for each page

3. loading.tsx - this creates a page for when a page is loading
    -This is useful for pages which could take a few moments to load
    -We can add a skeleton UI to this, is a basic layout of the webpage which its going to load (has no information)

4. lib folder is used to store information, db information etc 


https://nextjs.org/docs/app/building-your-application/routing/route-groups - useful to know when there are multiple paths, 
    -Route groups allow you to organize files into logical groups without affecting the URL path structure.
    -When you create a new folder using parentheses (), the name won't be included in the URL path. So /dashboard/(overview)/page.tsx becomes /dashboard.
