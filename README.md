# dynamodb-enhanced-demo


VisitsDAO using the new Enhanced DynamoDB Client

Output:

```
(Just getting) Matt has visited Guatemala 0 time(s)
(After recording) Matt has visited Guatemala 1 time(s)
(After recording) Matt has visited utah 1 time(s)
(After deletion) Matt has visited utah 0 time(s)
Matt has visited: [Visit{visitor='matt', location='guatemala', visit_count=1}, Visit{visitor='matt', location='idaho', visit_count=1}], and are there more pages? true
Matt has also visited: [Visit{visitor='matt', location='italy', visit_count=1}], and are there more pages? false
Italy was visited by: [Visit{visitor='adam', location='italy', visit_count=1}, Visit{visitor='elliot', location='italy', visit_count=1}], and are there are more pages? true
Italy was also visited by: [Visit{visitor='matt', location='italy', visit_count=1}, Visit{visitor='nate', location='italy', visit_count=1}], and are there are more pages? false
```