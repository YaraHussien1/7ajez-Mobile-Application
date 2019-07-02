# 7ajez-Mobile-Application
 ## Motivation
   * Although Palestine exists on Google maps, the main problem uncovered is the checkpoints that we face in our every day lives. These checkpoints are not provided on the map and their status is needed for the Palestinian community on a daily basis. The idea of our project will solve a big issue for the Palestinian community as it is needed to know about the best path to be taken for not wasting any time whilst traveling from city to the other. The motivation behind our project is in complete synchronization with the theme that is to organize the checkpoints’ information and make it accessible and useful for the user. Traffic on the roads is also another problem to undertake in our project as it affects the availability of the roads and makes a big issue for the people as to which path is the most available for anyone to take in order to avoid any hazards.

 * Why use Android ?
    - Android is an open source OS anyone can use it and develop it. 
    - Android is a Component based architecture, which means a part can be used in other parts of another operating system. It also provides a mash up, which is combining two or more services to create an application.
    - Android programs got many layers of security.
    - Android takes low power, less memory devices.
   
  
  
 * Why these third parties?
    - Easy to use.
    - More documentation.
    - Free keys.
    - Stable and secure.

# System Analysis

  ## SOA Diagram
![HAJEZ_SOA_Diagram (1)](https://user-images.githubusercontent.com/43942189/60539868-61f81380-9d16-11e9-8d3b-d5ae088fb88c.png)
   
# Details

 ## 3_Main Functions The user can do :
    
  * Search for destination.
  * Find the path to the destination.
  * View the barrier status.
  * Update the barrier status.
  
  ## Deployment Diagram

![HAJEZ_DeploymentDiagram](https://user-images.githubusercontent.com/43942189/60547287-f028c580-9d27-11e9-9204-6b985d1b8ff4.png)
   
## Sequence Diagram (Send CheckPoint Status)

![HAJEZ_Sequence_Update](https://user-images.githubusercontent.com/43942189/60547454-60cfe200-9d28-11e9-8de3-99f33a80eaa3.png)

# Details

 ## 1- The user clicks on Report Button
 ## 2- A list of options is shown to the user
 ## 3- The user chooses the type of the checkpoint status
 ## 3- The database is updated and all the near users are notified with the update.
   

# Implementation Details
 The Design Of The Application 


 ## Main Activiy 
 
 ![main](https://user-images.githubusercontent.com/43942189/60547764-303c7800-9d29-11e9-9615-e120dd94282a.png)

 ## Second Activity 
 
 ![second](https://user-images.githubusercontent.com/43942189/60547845-67128e00-9d29-11e9-8d82-0af9901ae8b4.png)
 
 ## Report Page
 
 
  ## Applied Technologies
  
  * Development Environment : STS , Eclipse.
  
  * Programming Languages : (JDK) java development kit 8.
  
  * Frameworks and libraries : swagger 2.0 , Spring Boot.
  
  * Deployment platforms : Google App Engine (GAE), which is a Google Cloud Platform(GCP) service provided by Google.
  
  * Application Server : Apache Tomcat ( Localhost 8080 ).
  
  ## Servise Deployment And Monitering
  
  * ##   Log File
  
    *  [   **Our Log File**  ](Team11LogFile.csv)
   
  # Conclusion and Discussion
  - The main idea of our API is to give the customer the closest hotel location, direction and to order a taxi to drive him to the           destination.
   - One of the problems was the lack of time, if we had more time we would produce a better work for sure.
   - some technical difficulties came across too, like trying to connect to the local host which eventually became successful, and             deploying the project to Google app engine made a lot of unexpected errors, which took a lot of time from us to try to solve them.
   - If we had more time I’m sure we will manage to launch a well structured and very helpful API.
   

   

