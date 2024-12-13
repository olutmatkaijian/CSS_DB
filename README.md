# CSS_DB
Incredibly stupid thing inspired by a YouTube short. 

[Inspired by this YouTube short](https://www.youtube.com/shorts/mAvWBub8Ycc)

# Can you use CSS to make a database? 

The glorious Neural Engine ChatGPT was not able to, but it did give an approximation:

```
Creating a "database" using only CSS is indeed a challenging thought experiment. A database, by definition, involves structured data storage and query capabilities—tasks that CSS isn't designed for. However, we can interpret your request as mimicking database-like behavior: storing data and "querying" it via styling rules.

Here's a conceptual implementation using CSS to simulate a database by leveraging data-* attributes, CSS selectors, and pseudo-classes.
Explanation:

    Data Storage:
        Each .record acts as a "row" in the database, and its attributes (like data-category and data-color) are "fields."
        The content of these rows is stored in the HTML.

    Querying:
        CSS rules filter and style the records based on their attributes. For example:
            [data-category="fruit"] displays only "fruit" records.
            Combined selectors, like [data-category="fruit"][data-color="red"], allow more specific filtering.

    Presentation:
        Styling variations based on the pseudo-classes (e.g., nth-child) can simulate additional data display logic.

This system is static and lacks interactivity or actual query logic—tasks better suited for JavaScript or server-side languages. But it creatively uses CSS selectors to approximate "queries" in a visual, declarative way.
```

See the appropriate html file in this repo. 
