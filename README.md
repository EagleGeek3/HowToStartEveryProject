# How to Start Every Project in this Class

###Purpose of This Document

This document will show you how to start every exercise or lab in this course.

###Fork the Project on GitHub

Before starting any project you must first fork it from GitHub. Go to the class [GitHub Repository](https://github.com/sbcc-cs105-spring2016) and find the repository for the assignment you are starting. There should also be a link to it on the Moodle page.

Follow the following sequence to fork the project and copy the URL for your forked version of the project to import into Eclipse:

 <img src="https://www.dropbox.com/s/uezrecne119tlja/fork_assignment.png?dl=1" width="1002" height="289" />
 
1. Click the **Fork** button to copy the assignment to your own personal repository.
2. When asked "Where should we fork this repository?" select your profile.
3. Click on the icon to the right to copy the link to your fork to the clipboard. This link will be used in the next step.

###Import Project from GitHub into Eclipse

To start a project in Eclipse you import it from Git. From Eclipse import the project in to your workspace by selecting the **File -> Import -> Git -> Projects from Git** and press "Next". Then click **Clone URI**. 

Next, you'll paste the URI from the provious step into the import dialog as shown below:

<img src="https://www.dropbox.com/s/zgagb305rlwxkfu/SourceGitRepository.tiff?dl=1" width="525" height="671" />

Follow the following sequence to import the project from Git.

1. Paste the URI from the previous step into "URI.
2. Press "Next", and 
3. Press "Next" again
4. Press "Next" again
5. Press "Next" again

You should now be on the "Import Projects" dialog. It looks like the following:

<img src="https://www.dropbox.com/s/6i8nkv7z2ca7mwj/ImportProjects.png?dl=1" width="525" height="671" />

Press "Finish", and that's it. 

###Add the Main Class

Then once the project is renamed open the project and add a Main.java source file by choosing **File -> New -> Class**. This is where you will write your test code for the objects you are creating to solve the programming problem. The class wizard looks like the following:

<img src="https://www.dropbox.com/s/doc1mz4zsftl9ng/NewJavaClass.png?dl=1" width="536" height="644" />

Configure the class by following these steps:

1. Enter the package name for the project. All packages in this course are in the package `edu.sbcc.cs105`
2. Enter the class name. This class is called Main (Note the capital letter to denote a class).
3. Check the box to generate a main method. This is where our program will start when we go to run it.
4. Click finish to create the source file.

###All Done

You now have a project that is ready to be worked on.

<img src="https://www.dropbox.com/s/tbzdmpjob7hjtj4/EX01-HelloWorld.png?dl=1" width="286" height="189" />

You're ready! Now on to the fun!