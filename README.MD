# TICK 1 INSTRUCTIONS
## Matching Rules: The search should be case-insensitive and allow partial matches to enhance usability. For instance, searching "Potter" should return any titles or authors containing "Potter."
## Priority of Results: Books that match multiple criteria (e.g., both title and author) should appear higher in the results than those matching only a single criterion. This one could be a bit more challenging so don't need to do it.
## Result Limit: Limit search results to a maximum of 50 books per request to prevent overwhelming users.
## Empty Results: If no matches are found, return aÂ 200 OKÂ status with an empty array, indicating a successful search with no results.