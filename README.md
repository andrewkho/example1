Here is our first Java program. Let us discuss the source code (which is in `FirstProgram.java`) here:

    public class FirstProgram {
        // Let us print two strings.
         public static void main(String[] args) {		
	        System.out.println( "Welcome to EECE 210!" );
	        System.out.println( "Was that not easy?" );
        }
    }

First observe that all code in Java belongs to a class. Further, each class is typically described in its own file. Therefore the class `FirstProgram` is in the file `FirstProgram.java`. In this example, the program has only one class and this class contains the method `main( )`. Every Java program has one class (and no more than one class) that contains the `main( )` method. You may also notice that we use the term _method_ rather than the term _function_.

This program does something extremely simple: it displays two strings on the screen. To write to the standard output device (in this case, the monitor/screen for your computer), one would typically use the `System.out.println( )` method.

`public` and `static` are keywords in Java and we will discuss their meaning in detail later. The keyword `void` that precedes the declaration of the `main( )` method indicates that this method does not return any value.

The use of `//` indicates that the text that follows on that line is a comment. (Why do we use comments?)

The tools that you will immediately need to install on your computer are:
* The Java Development Kit 7 (http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html);
* The Java Runtime Environment 7 (http://www.oracle.com/technetwork/java/javase/downloads/java-se-jre-7-download-432155.html);
* The Eclipse IDE for Java development (http://www.eclipse.org/downloads/packages/eclipse-ide-java-developers/junosr2).

To run `example1` on your own computer (assuming that you have the Eclipse IDE and Java 7 installed), perform these steps:

* Start `Eclipse`.
* Use the `File > Import` menu item.
* Select the `Git` option, which will have drop-down item `Projects from Git`; select this option.
* Double-click on the `Clone URI` option.
* In the URI entry, provide the URL of this GitHub repository. (It is `https://github.com/EECE-210/example1`.) Then select `Next`.
* In the branch selection dialog window, ensure that `master` is selected and click `Next`.
* In the local destination dialog window, you will see the default directory where the files from this repository will be stored on your machine. Make a note of this directory. Then click `Next`.
* You will be asked to select a wizard. Pick `Use the New Project wizard` Then click on `Finish`.
* You will now be asked to select a wizard to create a new Java project. Select `Java Project` under the `Java` dropdown list. Click on `Next`.
* You will be taken to the `New Java Project` dialog window. Uncheck the `Use default location` option. Then enter the name of the project as `example1` and select the directory where the files were stored (from the earlier step) as the project location. Once this is done, click on `Finish`.
* You should now be able to see the new project in the left pane of the Eclipse IDE. If you double-click on the project, you will be able to find the source file `FirstProgram.java`. 
* Double-click on the source file to open it in Eclipse. Eclipse should, by default, build (or compile) your project when you open it.
* From Eclipse's `Run` menu select `Run` and you should see the program output in the bottom of the Eclipse window in the Console pane.

(This video illustrates the steps above: http://vimeo.com/gsathish/eece210-example1. Better quality video:  http://vimeo.com/gsathish/eece210-example1-hd.)
