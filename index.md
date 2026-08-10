# Introduction and Self Assessment
-------Insert Text Later-------

# Code Review

The following code review video goes over the previous original artifact, and goes into each enhancement that will be performed and various improvements that will be implemented.

[CS 499 Code Review](https://www.youtube.com/watch?v=oYhBLnIxIvQ)

# Category One: Software Design and Engineering
## Narrative
**Description:**  The original artifact chosen for this enhancement was the CS 360 Android Studio project, which was created earlier this year in the final part of the March-April 2026 SNHU term. The project itself allowed the students to choose from three potential situations, in which I chose the weight tracking project. This project would then allow a user to create an account, use that information to login, and then would be able to enter in weight information to track their progress towards their goal.

**Justification:** I chose this artifact originally to enhance for two main reasons: First, it was a more recently finished project that was fresher in my memory to make better changes to. Second, this particular project was one of the few projects during a student's time at SNHU where the entire project was student created, being built from the ground up from scratch and could show more original work that was created and showcase that original talent.
 
The artifact itself for this enhancement was improved by moving the code from its original code being Java, over to the new language of Kotlin. Some additional aspects were improved such as cleaning up unused variables and imports or removing commented out test code that remained from the original project.

Original Code Sample: 
![Java code](images/ScreenshotCS360Java.jpg)

Enhanced Code Sample:
![Kotlin code](images/ScreenshotCS499Kotlin.jpg)

**Reflection:**  One aspect that was learned was learning all of the different aspects of the new language in how that related to the older code, in how that changed how the code looked overall and in what ways the new code would interact with each other.  One challenge that was faced was ensuring that proper program functionality was maintained through the conversion process. Ensuring to run the project and go through the different steps of the app while watching other screens such as the database entries to ensure none of the aspects of the app were nonfunctional.

[Original Artifact](https://github.com/ScottMWeiss/CS499/blob/main/Artifact%201%20-%20Software%20Design%20and%20Engineering/Original%20Artifact/WeissCS360Files.zip) | [Full Narrative](https://github.com/ScottMWeiss/CS499/blob/main/Artifact%201%20-%20Software%20Design%20and%20Engineering/Enhanced%20Artifact/CS%20499%20-%20Milestone%20Two%20Enhancement%20One%20Narrative%20-%20Weiss.docx) | [Enhanced Artifact](https://github.com/ScottMWeiss/CS499/blob/main/Artifact%201%20-%20Software%20Design%20and%20Engineering/Enhanced%20Artifact/WeissCS499EnhancementOne.zip)

# Category Two: Algorithms and Data Structures
## Narrative
**Description:**  The artifact chosen for this enhancement was the same CS 360 Android Studio project used for the first enhancement, which was created earlier this year in the final part of the March-April 2026 SNHU term. The project itself allowed the students to choose from three potential situations, in which I chose the weight tracking project. This project would then allow a user to create an account, use that information to login, and then would be able to enter in weight information to track their progress towards their goal.

**Justification:**  I chose this artifact originally to enhance for two main reasons: First, it was a more recently finished project that was fresher in my memory to make better changes to. Second, this particular project was one of the few projects during a student's time at SNHU where the entire project was student created, being built from the ground up from scratch and could show more original work that was created and showcase that original talent.

This specific enhancement for the artifact was improved by adding in a new graph screen to visually see the data entered in by the user, which can be seen in the images below. 

Graph Code Section:
![Graph Code Section](images/GraphCodeSectionjpg.jpg)

Graph Fragment Screen Sample:
![Graph Fragment](images/GraphFragmentScreen.jpg)

In the Graph Fragment Screen Sample, the graph fragment screen is shown running in the app in Android Studio using sample weight data entered into the database. As Android Studio seems to lack the native ability to make graphs itself, outside tools were necessary to assist in this process. For this enhancement, the tool MPAndroidChart (PhilJay, n.d.) was used to take data from the database and display it into a graph, as well as referencing other material for use in the coding shown in the Graph Code Section in order to understand and implement the necessary code, such as from Yilmaz (2019).

**Reflection:**  Some aspects that I learned were more learning how coding in Kotlin worked and how that interacted with the tool being used to help create the graph, and became more familiar with the new coding style, as well as how to implement new features into Android Studio and how those could be used within the program, which will be helpful moving into the next enhancement with implementing a new database.

Some challenges that were faced were mainly issues with the tool itself. It’s unclear where the underlying issues reside, as a lot of the code base of the tool seems to be from years ago being the latest release is from 2019 so it’s possible there’s compatibility issues with the more modern version of Android Studio, but trying to implement certain aspects were problematic to say the least. One example is I was using test data when initially trying to make sure the created code itself worked before reading data from the database. The x-axis labels would refuse to show up or the code would produce array out of bounds errors if the amount of test data was too small, something I only learned about from an offhand GitHub issue page comment about a week later after multiple attempts to get it to work that wasn’t even about that specific issue. I was using sample arrays of about five entries to initially test the graph, and apparently using about 10 or more data entries in the arrays magically caused it to start working better. Some design choices had to be limited, some attempts to design the graph in certain ways were leading to some of the errors like the out of bounds errors that came up, and it’s still unclear why those issues persisted even after spending too much time researching more into the tool itself, so I had to settle for what I was able to get out of it, even after having to rollback and use an older version of the tool in order to get it to function.

[Original Artifact](https://github.com/ScottMWeiss/CS499/blob/main/Artifact%202%20-%20Algorithms%20and%20Data%20Structures/Original%20Artifact/WeissCS360Files.zip) | [Full Narrative](https://github.com/ScottMWeiss/CS499/blob/main/Artifact%202%20-%20Algorithms%20and%20Data%20Structures/Enhanced%20Artifact/CS%20499%20-%20Milestone%20Three%20Enhancement%20Two%20Narrative%20-%20Weiss.docx) | [Enhanced Artifact](https://github.com/ScottMWeiss/CS499/blob/main/Artifact%202%20-%20Algorithms%20and%20Data%20Structures/Enhanced%20Artifact/WeissCS499EnhancementTwo.zip)


# References
PhilJay. (n.d.). GitHub - PhilJay/MPAndroidChart: A powerful 🚀 Android chart view / graph view library, supporting line- bar- pie- radar- bubble- and candlestick charts as well as scaling, panning and animations. GitHub. https://github.com/PhilJay/MPAndroidChart/tree/master

Yilmaz, V. (2019, November 27). Kotlin Line Chart. Medium. https://medium.com/@yilmazvolkan/kotlinlinecharts-c2a730226ff1
