# CoronaVirusApp
_The corona virus app from the YouTube video by Java Brains_ 

Building a Coronavirus tracker app with Spring Boot and Java - Java Brains Tutorial
[Link to the video here](https://www.youtube.com/watch?v=8hjNG9GZGnQ&t=7s)

![video](https://user-images.githubusercontent.com/83961643/169647487-20977da4-a344-48b6-8607-839c3a469509.jpeg)



COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University
[Data source](https://github.com/CSSEGISandData/COVID-19)

koushikkothagal / coronavirus-tracker *github rep*
[Source code for the project by Java Brains](https://github.com/koushikkothagal/coronavirus-tracker)


## Setting up the project 
`https://start.spring.io`

![init](https://user-images.githubusercontent.com/83961643/169647448-ccace802-ce2c-45d6-b855-7c9e3adf9846.jpeg)


The uploaded file in IntelliJ IDEA

![pomdependenciesloaded](https://user-images.githubusercontent.com/83961643/169647486-60d733fe-398c-4df2-8f66-9f54118acbf6.jpeg)


Pulling the corona virus data from the online csv file from github 

![workingdataserviceHttpresponse](https://user-images.githubusercontent.com/83961643/169666935-a0c24629-8263-47ec-8f6e-0b7494456802.jpeg)

Website for more dependencies and add ons for the CSV file sorting/styling
[View it here](https://commons.apache.org/proper/commons-csv/user-guide.html)

```
<dependency>
    <groupId>org.apache.commons</groupId>
    <artifactId>commons-csv</artifactId>
    <version>1.9.0</version>
</dependency>
```

[Link for the dependency page](https://commons.apache.org/proper/commons-csv/index.html)

[Java Docs](https://javadoc.io/doc/org.apache.commons/commons-csv/latest/index.html)

![docs](https://user-images.githubusercontent.com/83961643/169667162-647f477b-e7d1-446d-9fde-8886127f8692.jpeg)

How to add a dependency in IntelliJ:
> press ⌘N (macOS) or Alt+Insert (Windows/Linux), within the POM file, the IDE will offer the option of adding a new dependency
![dependency](https://user-images.githubusercontent.com/83961643/169667537-c470f44f-ea4d-4928-b475-fd0287c7c259.jpeg)

[Link of resources](https://www.jetbrains.com/idea/guide/tutorials/migrating-junit4-junit5/adding-dependencies/)


Adding in more code: 
![header](https://user-images.githubusercontent.com/83961643/169667855-9671d73a-8d72-43fa-bad9-d2bc9782fa22.jpeg)

Issues with the code insert due to depreciated dependencies. 
![depreciated](https://user-images.githubusercontent.com/83961643/169668106-73830fed-d497-4fd1-aa62-64ed211a5be9.jpeg)

![depreciate](https://user-images.githubusercontent.com/83961643/169685703-3a87700a-17ef-48a5-a0f5-ec608bef4cb4.jpeg)

[docs.oracle](https://docs.oracle.com/javase/7/docs/technotes/guides/javadoc/deprecation/deprecation.html)

Running the app to pull the state/province info
![run](https://user-images.githubusercontent.com/83961643/169686182-5e737af7-3dfb-49eb-9192-f68807cc958f.jpeg)
![state](https://user-images.githubusercontent.com/83961643/169686206-3136ba4f-2380-4cbc-b10d-479985a765d3.jpeg)
![runningstats](https://user-images.githubusercontent.com/83961643/169703307-b1b8eb3f-6207-4be3-aae9-b21cb1fe72a4.jpeg)

### Thymeleaf Docs 
[Read more here](https://www.thymeleaf.org/documentation.html)
![thymleaf](https://user-images.githubusercontent.com/83961643/169703325-8914c0ed-eeab-4492-92e3-8e9ae5375e9c.jpeg)

Running the app with the home controller and home template working 

![working app](https://user-images.githubusercontent.com/83961643/169703482-0db9fc0a-d39c-48fe-9860-feeb9bca573e.jpeg)

Copying more code from Thymeleaf docs
![copy](https://user-images.githubusercontent.com/83961643/169704325-7151030a-dff1-4449-bc14-bba8a6c3e70c.jpeg)


# Final Working App:

![workingapp](https://user-images.githubusercontent.com/83961643/169802092-8a575a1f-2dff-40d0-aa53-58206444bc7f.jpeg)
![working](https://user-images.githubusercontent.com/83961643/169802110-4062587e-706c-4dd1-ac2f-c57fcefbd678.jpeg)

# Deployment on Heroku 
[Deploying Spring Boot Applications to Heroku](https://devcenter.heroku.com/articles/deploying-spring-boot-apps-to-heroku)
![heroku](https://user-images.githubusercontent.com/83961643/170816963-5d756fdd-219e-4aab-a065-ffa74fdf1353.jpeg)
![download](https://user-images.githubusercontent.com/83961643/170887205-80b0e073-2f84-4db3-923c-9558e55b7c71.jpeg)


LAST UPDATE: May 2022
