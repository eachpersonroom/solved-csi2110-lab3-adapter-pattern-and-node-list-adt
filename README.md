Download Link: https://assignmentchef.com/product/solved-csi2110-lab3-adapter-pattern-and-node-list-adt
<br>
<h2>Adapter Pattern and Node List ADT</h2>

As discussed in class a doubly-linked list provides a natural implementation of the Node List ADT.

The Java Collections Framework does not provide a NodeList interface. In this lab you will need to adapt the LinkedList implementation of the Java Collections Framework to a NodeList and analyze this approach.

The Java Collections Framework is well documented in the this <a href="http://java.sun.com/docs/books/tutorial/collections/index.html">tutorial</a> by Sun. The Collections Framework provides two list implementations: <em>java.util.ArrayList</em> and <em>java.util.LinkedList</em> . You should run the simple example program TestListImplementation.java which compares the two list implementations. The test program is contained in the archive <a href="lab3.zip">lab3.zip</a>.

Your NodeList should hold a sentence consisting of strings which your main program should print in order. See the main program in Sentence.java for clarification.

Your NodeList adapter class needs to implement the methods specified in this NodeList.java skeleton class. You may assume that each node in your NodeList has a unique reference but may contain several objects where a call to “equals()” will return true.

Consider the performance of your adaptor class. Which methods have not the expected performance of a NodeList implementation and why?

<h2>Summary</h2>

<ul>

 <li>Look at the Java Collections Framework

  <ul>

   <li><a href="http://java.sun.com/docs/books/tutorial/collections/index.html">tutorial</a></li>

  </ul></li>

 <li>Download the archive

  <ul>

   <li><a href="lab3.zip">lab3.zip</a></li>

  </ul></li>

 <li>Study and run

  <ul>

   <li>TestListImplementation.java</li>

  </ul></li>

 <li>Look at</li>

</ul>

<ul>

 <li></li>

</ul>

<ul>

 <li style="list-style-type: none;">

  <ul>

   <li>NodeList.java</li>

  </ul></li>

 <li>Implement indicated methods and test your code with</li>

</ul>

<ul>

 <li></li>

</ul>

<ul>

 <li style="list-style-type: none;">

  <ul>

   <li>Sentence.java</li>

  </ul></li>

 <li>Analyze the behaviour of your adapter class</li>

</ul>