##  MyMultiModuleProject

### Purpose - to build and package child modules into a zip at parent level

#### **Run below command from parent dir to build child modules and package them into a zip**

#### mvn package assembly:single

#### Expecting output
MyMultiModuleProject/\
├── module1/ <br />
│   ├── module1.jar <br />
├── module2/ <br />
│   ├── module2.jar <br />
├── target/ <br />
│   ├──MyMultiModuleProject.zip --> this should contain module1.jar and module2.jar <br />
