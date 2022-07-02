# Saba Android Assignment
The goal of this assignment is to evaluate candidate's skills and technical workflow. It is recommended to limit the time spent to complete the assignment to a maximum of 8 hours.

## Assignment
Create a small test app that makes use of the Filimo API for search. Please note that there's no big emphasis on the UI, an input field with a list should be good enough!, the overall architecture and patterns used are more important.

## Deliverables
Result can be delivered as a project hosted on Github or Gitlab
1. The program-code - preferably in a git repository hosted on e.g. Github.
2. An archived version of the app that we can run.
3. README instructions on how to run and test the solution as well as a summary of the
required software and version needed to run or test the solution
4. All assumptions that were made, as well as the underlying reason
5. Any other elements that you believe would speed up running or testing the solution

## Search API
In order to get results for a specific query use the API below:
```http
https://www.filimo.com/api/en/v1/movie/movie/list/tagid/1000300/text/{Query}/sug/on
````
following header must be added to the request as well:
```
"jsonType" : "simple"
```
which will return a list of movies matching the query

## Evaluation Criteria
The solution will be evaluated according to the following criteria:
1. Code readability
2. Used technology
3. The soundness of the architecture
4. Clarity of individual git commits
5. Clarity of the README instructions and other documentation
