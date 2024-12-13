# Explanation: CSS Database Simulation

## Why This is a Poor Solution

Creating a "database" using CSS and HTML is an extremely inefficient and inappropriate approach for managing structured data. Here is a detailed explanation of the issues:

### 1. **Wrong Tool for the Job**
CSS is designed for styling, not data storage or querying. Real databases (e.g., SQL, MongoDB) offer optimized solutions for:
- Handling large datasets.
- Efficiently querying and filtering data.
- Dynamically updating data.

This CSS solution is fundamentally a hack and cannot compete with real database technologies.

### 2. **Poor Scalability**
With this setup:
- Every record must be hardcoded into HTML, which is impractical for large datasets.
- Adding, removing, or updating records requires manual code edits, leading to significant technical debt.
- Real databases scale effortlessly, enabling dynamic CRUD operations without manual intervention.

### 3. **No True Query Capabilities**
The "querying" here relies on basic CSS selectors and JavaScript toggling classes. This approach:
- Cannot handle complex filters, sorting, or aggregations.
- Is not dynamic and depends entirely on hardcoded logic.

### 4. **Time-Consuming and Costly**
Building this "database" involves a disproportionate amount of time and effort for a subpar result. Developers would spend:
- Hours creating, testing, and debugging CSS/JS hacks.
- Days maintaining and updating hardcoded data.

Using a proper database or API would save significant development time and costs.

### 5. **Collaboration and Maintainability Issues**
This unconventional approach:
- Confuses other team members or future maintainers.
- Creates technical debt, as it's far removed from industry best practices.

For recruiters, this kind of implementation might raise concerns about the technical expertise of the team.

### 6. **Risky and Error-Prone**
Without proper database mechanisms, this system:
- Lacks validation, consistency, or security checks.
- Is prone to breakages if a single CSS rule or attribute is mistyped.

## Jira Tickets and Story Points
Here’s a breakdown of the effort required to implement this solution:

### Tasks:
1. **Setup CSS and HTML for Records**  
   - Create hardcoded records in HTML with `data-*` attributes.  
   - Write CSS rules to simulate queries.  
   - **Effort:** 2 tickets, ~5 story points.

2. **Add JavaScript for Filters**  
   - Implement dropdowns for categories and colors.
   - Write JS to dynamically toggle `visible` classes based on filter selections.  
   - **Effort:** 2 tickets, ~8 story points.

3. **Testing and Debugging**  
   - Test filtering logic and fix CSS/JS conflicts.  
   - Ensure edge cases (e.g., no matching records) are handled.  
   - **Effort:** 2 tickets, ~6 story points.

4. **Documentation**  
   - Write usage documentation and setup instructions for future maintainers.  
   - **Effort:** 1 ticket, ~3 story points.

### Total Estimate: **7 Tickets, ~22 Story Points**

## Conclusion
This project would require significant time and effort for a result that is inferior to even the simplest database solution. Instead, we recommend using:
- **SQLite** for local database needs.
- **MySQL** or **PostgreSQL** for more scalable solutions.
- **APIs with JavaScript frameworks** (like React or Angular) for front-end interaction with databases.

**Recommendation:** Avoid implementing this "CSS database" and allocate resources to a proper technical solution that aligns with best practices.

