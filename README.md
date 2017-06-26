# gauge-maven-multimodule
Sample Gauge project with multimodule setup.  

##Project structure
The maven project structure is : 
```
parent-module   
   |
    - module1
   |
    - module2
```

This project has two maven modules : `module1` and `module2`.  
`module1` is dependant on `module2`.

`module1` and `module2` use concepts which can be found in [gauge-maven-multimodule-concepts](https://github.com/nehashri/gauge-maven-multimodule-concepts.git) repository.

`module2` contains the actual implementation for the concepts present in [gauge-maven-multimodule-concepts](https://github.com/nehashri/gauge-maven-multimodule-concepts.git). Hence, module2 is a maven dependency for module1. This ensures module1 gets the implementation details for concepts as well.
