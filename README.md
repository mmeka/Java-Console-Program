# Compiling using Javac

To compile a class with package structure defined, use the following command. This command ensures the ".class" file is placed in the respective directory structure defined in the package name.
javac -d . <Java_file_name>   [OR] javac -d <directory_name> <Java_file_name>
Without "-d" option, ".class" files are going to be created in the current working directory.
To execute the Java program, use the following command.
java <fully_qualified_class_name>
