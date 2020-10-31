# ImageLab

ImageLab is a framework that allows students to develop
image modification processors (filters) and to experience
the results visually and aurally.

## Contents
The __imagelab__ and __sound__ packages may be provided in an `imagelab.jar` file.
The `imagelab.jar` file also includes the class __Run__ with a `public static void main` method in the unnamed package, used to facilitate running the ImageLab application.
(This version may also be used directly as a [BlueJ](http://bluej.org) project.)

The __filter__ package is generally provided as a folder with source (`.java`) and compiled (`.class`) files, with the source versions serving as examples for students.

A sample set of images are provided in an __"images"__ directory.

## Creating an executable jar file
Instructions may vary depending on the IDE but in general the process will be similar to these instructions.

1. Open up the java files from this repository in your desired IDE. These will be found in the **sound, filters and imagelab** folders. Don't forget to also open up the **Run.java** from the base directory of the project. 
2. Compile all of the java files.
3. Navigate your IDE to find its *create jar* functionality.
4. Set up the dependencies of the jar to use all of the files except for the **Run.java**.
5. It should now give you an option to select the main class. The main class for this project is Run, so select Run as the main class.
6. Choose a name for your jar to be saved under. Make sure to save your jar file in base directory of your imagelab repository.

Some specific examples from popular IDE's can be found here:
- [Eclipse](https://support.smartbear.com/alertsite/docs/monitors/web/selenium/export-eclipse-java-project-as-runnable-jar.html)
- [JDeveloper](https://www.albinsblog.com/2014/12/building-executable-jar-file-with.html)
- [IntelliJ](https://www.jetbrains.com/help/idea/compiling-applications.html#package_into_jar)
- [BlueJ](https://bluej.org/tutorial/tutorial-v4.pdf)
- [NetBeans](https://netbeans.org/kb/articles/javase-deploy.html)

## To use from command line:  
* Make sure the __filters__ directory is _in the same directory_ as the __imagelab.jar__ file.
* Then issue the command  
`java -jar imagelab.jar`  
  
An alternative command is:
`java -cp ".:imagelab.jar" Run`  
Note that on Windows platforms, the ":" character in the classpath must be changed to the ";" character.

## License

ImageLab is a framework for student exploration of image processing.  
Copyright (C) 2016,2019 by Aaron Gordon & Jody Paul  
The software comes with ABSOLUTELY NO WARRANTY.
 
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see https://www.gnu.org/licenses/

___

Project Website: https://metrocs.github.io/imagelab/
