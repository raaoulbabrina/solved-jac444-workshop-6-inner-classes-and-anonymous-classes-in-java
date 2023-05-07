Download Link: https://assignmentchef.com/product/solved-jac444-workshop-6-inner-classes-and-anonymous-classes-in-java
<br>
This assignment lets you practice concepts such as Object Serialization, and Swing (or Java FX) GUI.

<strong> </strong>

In this assignment, you will be working with some objects of a <strong>Student</strong> class (which should be serializable.)

This class has fields such as <strong>stdID</strong> (int), <strong>firstName</strong> (String), <strong>lastName</strong> (String), and <strong>courses</strong> (an array or preferably an ArrayList which contains the names of the courses the student currently has). Please provide constructors, getters, and setters, where appropriate.

In the second class, you will need to enter some information for some student objects from the console and save these student objects in a file.

And finally, in the third class of this project, you need to read those student objects from the file, and then show their info in the console, to verify that they had been saved (and serialized) correctly.

For Workshop 6, after we have covered GUI programming in Java in the next lectures, you should design a Swing (or Java FX) GUI-based Java application to do the same job. It could be as simple as (at least) a <strong>JFrame</strong> with some <strong>JTextField</strong>s and a <strong>JButton</strong> (to let the user enter the information of the students and save them), and a <strong>JTextArea</strong> and another <strong>JButton</strong> (to let the application to read the information of all saved students from the file and show them to the user.)

<em>Note that we should be able to run the third class and retrieve the data (student objects) already stored in the file independent of running the second class first (assuming we have serialized some objects by running the second class in advance). These two classes should be treated and/or run as two independent processes/programs in your project. The same applies to the GUI version; you could have an interface which lets you choose whether you want to read/load or save students’ info. </em>