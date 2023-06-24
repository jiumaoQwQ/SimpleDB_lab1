# SimpleDB lab1

This is my database final homework

https://www.cs.hmc.edu/~beth/courses/cs133/fall2019/assignments/lab1.html

# Enviroment setup

- OS : archlinux

run the following commands to install ant and git
~~~
pacman -S git
pacman -S ant
~~~

Then download the repo
~~~
git clone https://github.com/jiumaoQwQ/SimpleDB_lab1.git
~~~

Finally, check whether you are ok
~~~
ant javadocs
~~~

# 2.1

DataBase provides methods to access some static objects such as catalog and buffer pool. DataBase used Singleton pattern.

# ex1
see src/java/simpledb/TupleDesc.java and src/java/simpledb/Tuple.java


# ex2
see src/java/simpledb/Catalog.java
# ex3