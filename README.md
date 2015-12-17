# How to Start Every Project in this Class

###Purpose of This Document

This document will show you how to start every exercise or lab in this course.

###Copy the Template Project

To start a project you download the Cs105ProjectTemplate from the Moodle web site. This will be downloaded as a compressed (zip) file. **Do not uncompress (unzip) the file**. From Eclipse import the project in to your workspace by selecting the **File -> Import -> General -> Existing Projects into Workspace** and press next. The import dialog appears as shown below:

<img src="https://www.dropbox.com/s/ihh8wrc865l1rxj/importarchive.png?dl=1" width="525" height="671" />

Follow the following sequence to import the template.

1. Choose the button "Select archive file:" to import our compressed project.
2. Use the browse to navigate to the compressed file and select it.
3. Press "Finish"

###Rename the Template Project

Once you have imported the project reaname it to your project name. Select the project and choose **Refactor -> Rename**. You can also bring up the context sensitive menu and it is on there under the Refactor submenu. Change the name to the proper form which is in the following format {FLname}_ProjectName_XYY. For example, if your name is Hayao Miyazaki in my Fall 2025 class and you are working on a project named Grade then the project name would be

HMiyazaki_Grade_F25

This consists of the first initial, last name, underscore, project name exactly as specified, underscore, first initial of the term (F - fall, S - spring), two year identifier assuming the twenty-first century.

_All projects must use this naming convention. No credit will be awarded to those who do not use this convention and no investigation will be performed. I'm sorry to be so strict but it's the only way for me to stay on top of the huge numbers of items I have to grade._

###Add the Main Class

Then once the project is renamed open the project and add a Main.java source file by choosing **File -> New -> Class**. This is where you will write your test code for the objects you are creating to solve the programming problem. The class wizard looks like the following:

<img src="https://www.dropbox.com/s/doc1mz4zsftl9ng/NewJavaClass.png?dl=1" width="536" height="644" />

Configure the class by following these steps:

1. Enter the package name for the project. All packages in this course are in the package `edu.sbcc.cs105`
2. Enter the class name. This class is called Main (Note the capital letter to denote a class).
3. Check the box to generate a main method. This is where our program will start when we go to run it.
4. Click finish to create the source file.

###All Done

You now have a project that is ready to be worked on. Using our student Mr. Miyazaki as an example, this is what we see if we look at the package explorer.

<img src="https://www.dropbox.com/s/dbsaql728o1d9lk/MiyazakiPackageExplorer.png?dl=1" width="244" height="103" />

You're ready! Now on to the fun!