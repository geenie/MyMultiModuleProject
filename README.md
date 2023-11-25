##  MyMultiModuleProject

### Purpose - to build and package child modules into a zip in a target folder at parent level

#### **Run below command from parent dir to build child modules and package them into a zip**

#### mvn package assembly:single

#### Expecting output
MyMultiModuleProject/
├── module1/
│   ├── module1.jar
├── module2/
│   ├── module2.jar
├── target/
│   ├──MyMultiModuleProject.zip --> this should contain module1.jar and module2.jar 
