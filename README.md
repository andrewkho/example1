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

To run this program on your own computer (assuming that you have the Eclipse IDE and Java 7 installed), perform these steps:

1. Start `Eclipse`.

2. Use the `File > Import` menu item.

3. Select the `Git` option, which will have drop-down item `Projects from Git`; select this option.

4. Double-click on the `Clone URI` option.

5. In the URI entry, provide the URL of this GitHub repository. (It is `https://github.com/EECE-210/example1`.) Then select `Finish`.

6. You will be asked to select a wizard. Pick `Java Project` under the drop-down list named `Java`. Then click on `Next`.

7. You will be asked to enter a project name. You can enter any project name you choose. For example, you could enter `example1`. Then click on `Finish`.
