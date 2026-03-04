# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid

 classDiagram

class Test {
    - length: int
    - speed: double
    - accuracy: double
    - user: string
    - testType: string
    + getTestResults() 
}

class User {
    - username: string
    - userId: int
    + getNumTests(userId: int): int
    + getTopTests(numTests: int, userId: int): Test[]
    
}



```
