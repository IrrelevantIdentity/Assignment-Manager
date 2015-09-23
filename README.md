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
* Assignment name [Text]
* Assignment requirements [Memo]
* Assignment date assigned [Date]
* Assignment teacher(s)(Derived from "Class Teacher(s)") [Text]
* Assignment due date [Date]
* Assignment duration type [Enumeration]

#### Classes

##### Atributes
* Class name [Text]
* Class teacher(s) [Text]
* Class subject [Text]{for now}



#### Relationships
* Assignments belong to classes (1)
* Classes have assignments (many)
