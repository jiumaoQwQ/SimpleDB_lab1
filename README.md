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

Database provides methods to access some static objects such as catalog and buffer pool. Database is a singleton class.

# ex1
see src/java/simpledb/TupleDesc.java and src/java/simpledb/Tuple.java

TupleDesc describes the structure of the tuple. It contains the type and name of each column.
# ex2
see src/java/simpledb/Catalog.java

Catalog contains the instance of each tuple and their ralationship.
# ex3
see src/simpledb/BufferPool.java

BufferPool stores the pages that has already loaded.
# ex4
see src/simpledb/HeapPageId.java
src/simpledb/RecordID.java
src/simpledb/HeapPage.java
# ex5
see src/simpledb/HeapFile.java
# ex6
see src/simpledb/SeqScan.java
