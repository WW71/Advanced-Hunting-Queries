# Advanced Hunting Queries for Dummies Cheat Sheet

## Operators

### | where
Filters a table to reveal rows of data that contain certain conditions. Add more to narrow your scope.
e.g. 
```
| where [column] = [data]
| where Country = US
```

### | project
Filters the table to include only the specified columns. Add more to include columns.
e.g. 
```
| project [column1], [column2], [column 3] ...
| project AccountDisplayName, IPAddress, Timestamp, Country
```
