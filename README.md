# Assignment-Manager
## Intro
* Add homework assignments
* Specify due dates for assignments
* Describe requirements for assignments
* Specify which class assignments pertain to
* Specify assignment durations types; typical amount of time forecasted for completion. (Short, Medium, or Long)

### Entities

#### Assignments

##### Atributes
* Assignment name [String]
* Assignment requirements [Memo]
* Assignment date assigned [Date]
* Assignment teacher(s)(Derived from "Class Teacher(s)") [String]
* Assignment due date [Date]
* Assignment duration type [Enumeration]

#### Classes

##### Atributes
* Class name [String]
* Class teacher(s) [String]
* Class subject [String]{for now}
* Class schedule [String]


#### Relationships
* Assignments belong to classes (1)
* Classes have assignments (many)
