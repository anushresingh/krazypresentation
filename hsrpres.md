<style>

body{
  font-size: 2.8vmin;
}

p,li{
  margin-bottom: 1em;
}

code{
  border-radius: 0.2em;
  background-color: #444;
}

table tr{
  background-color: transparent;
}
img.one {
    height: 20%;
    width: 80%;
    text-align: center;
}

table tr:nth-child(2n) {
    background-color: transparent;
}

</style>

# What's our next JVM language?
<h2 style="text-align: center">:zap: Anushree Singh :zap:</h2>


-----------------------


<center><h2> Problem Statement</h2></center>

<center><h1>Explore and study new languages to make sure we are using the most efficient one</h1></center>




-----------------------


# Scope & Goals

- Understand the KG (Krazyglue) application
- Explore and find candidate JVM languages
- Refactor a part of KG to each of the candidate languages
- Compare the languages based on performance and other metrics
- Recommend a JVM language for KG



-----------------------


# What kind of application is krazyglue:

1. <del> Computation intensive </del>
2. <del>DB Intensive </del>
3. Request driven &#10004;


-----------------------

# Candidate languages

1. <b>Clojure</b>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;General-purpose, Emphasis on functional programming
2. <b>Groovy</b>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dynamic language with static-typing -  concise, easy to learn syntax
3. <b>Kotlin</b>  &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Statically typed for JVM, Android and the browser
4. <b>Scala</b>   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;General-purpose, Full support for functional programming

------------------------

# Choose a part of krazyglue to work on which:


- is of appropriate size
- is not strongly connected to other modules
- has some complex logic or language features

------------------------



<center> <h2> Point of Sale Retreiver </h2> </center>

<center><img src="krazyglue1.png" height="70%" width="40%"></center>



------------------------

# Why is Clojure not a good fit

- OOPs to functional programming transformation.
- Challenging to work with Spring. Works better with other frameworks - Fleet or Hiccup.
- It is aimed for multithreaded and concurrent programs.
- Syntax is very different from Java.

------------------------



#  Non performance metrics 

<center><img  src="np1.png" height="100%" width="100%"></center>



------------------------


# Results: Non performance metrics 

<center><img  src="np2.png" ></center>



------------------------


# Performance metrics 

<center><img class = "one" src="p1.png" ></center>



------------------------



<center><h2> CPU Usage </h2></center>
 
<center><h3>&uarr; CPU usage = &#8595; performance</h3></center>

<center><img  src="cpubar.png" width="45%" height="30%"></center>

<center><img  src="cpuusage.jpg" width="45%" height="30%"></center>







------------------------


<center><h2> Classes loaded </h2></center>
 
<center><h3>&uarr; Number of classes loaded = &#8595; performance</h3></center>



<center><img  src="classesbar.png" width="45%" height="30%"></center>
<center><img src="Classesusage.jpg" width="45%" height="30%"></center>






------------------------

<center><h2> Heap Size used </h2></center>
 
<center><h3>&uarr; heap size used = &#8595; performance</h3></center>



<center><img  src="heapbar.png" width="45%" height="30%"></center>

<center><img src="Heapsize.jpg" width="45%" height="30%" ></center>



------------------------

<center><h2> Threads started </h2></center>

<center><img  src="threadsbar.png" width="45%" height="30%"></center>

<center><img  src="Threadsusage.jpg" width="45%" height="30%" ></center>




------------------------

# Results: Performance 

<center><img  src="p2.png" height="50%" width="70%"></center>

-----------------------

# Final Results 

<center><img  src="final.png" height="60%" width="60%"></center>

-----------------------

# My Recommendation : SCALA

<center><img  src="meme.jpg" height="40%" width="40%"></center>

-----------------------



# Thank you! :v:

##The presentation can be found on: 

## This presentation has been made using markpress (https://www.npmjs.com/package/markpress).
