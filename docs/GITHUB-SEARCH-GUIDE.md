# GitHub Search Guide for Issues and Pull Requests

## Introduction
This guide provides comprehensive instructions on how to effectively search for issues and pull requests (PRs) in the GitHub repository [https://helloworlddev.in](https://helloworlddev.in). It includes date filters, activity metrics, review status filters, boolean operators, and real-world examples tailored for our organization.

---

## 1. Basic Search
You can start by using the GitHub search bar at the top of the page. 
To search for issues, you can use the following format:
```
org:helloworlddev.in type:issue
```
To search for pull requests:
```
org:helloworlddev.in type:pr
```

## 2. Date Filters
You can filter issues and PRs based on creation or update dates. Use `created:` or `updated:` followed by a date or range:
```
created:>2022-01-01
updated:<2023-01-01
```
You can also combine with other queries:
```
org:helloworlddev.in type:issue created:>=2023-01-01
```

## 3. Activity Metrics Filters
If you're interested in issues or PRs that have high activity metrics, you can use comments counts, review counts, and more:
```
comments:>10
reviewed-by:username
```

## 4. Review Status Filters
To filter by review status, use the following:
```
review:required
review:approved
review:changes_requested
```

## 5. Boolean Operators
You can combine search terms using boolean operators such as `AND`, `OR`, and `NOT`. Examples:
```
label:bug AND assignee:a2zzeero2nine
label:enhancement OR label:feature
```

## 6. Real-World Examples
- To find all open issues assigned to you in the organization:
```
org:helloworlddev.in type:issue assignee:a2zzeero2nine is:open
```
- To locate PRs that were recently updated:
```
org:helloworlddev.in type:pr updated:>2026-03-20
```
- To see issues with specific labels:
```
org:helloworlddev.in type:issue label:urgent
```

---

## Conclusion
Utilizing these tools and filters will enhance your efficiency when searching through issues and pull requests in GitHub. Remember, the more specific your search, the better the results. Happy searching!