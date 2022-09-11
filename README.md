# Student Grade Checker

# studentgradechecker-api-40040160

### NOTE: Database credentials need added in 'application.properties' file of 'resources' folder.

Student Grade Checker is a microservice application designed as part of the Queen's University Belfast MSc Software Development Cloud Computing module (CSC7071).

The Java Spring Boot API function receives HTTP request containing form data (module marks, student details, etc.). It then processes this information, creating
a Student object and importing it into a databases (AWS RDS hosted).

## Functions

1. Highest and lowest scoring modules calculator
2. Sort modules from highest to lowest score
3. Calculate total marks
4. Calculate final classification (measured against QUB official guidelines)

### Additional Functions

5. Get averages (all modules, dissertation modules, non-dissertation modules)
6. Print unofficial transcript to PDF

## Further Information

#### The project required the demonstration of:

A) New functionalities using containers, including unit testing and CI pipeline

B) Improvements to functionalities, including error handling, stateful saving and frontend failure handler

C) Proxy implementation, including configurability

D) Monitoring

## Contributing

Original code created by Niall Hodgen.

## License

[MIT](https://choosealicense.com/licenses/mit/)

