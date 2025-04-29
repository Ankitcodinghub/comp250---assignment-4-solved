# comp250---assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [COMP250 – Assignment 4 Solved](https://www.ankitcodinghub.com/product/comp250-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110749&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP250 - Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
The teaching staff handling this assignment consists of Giulia Alberini (email), Sayantan Datta (email), Anmoljeet Gill (email), Alexander Orzechowski (email), Kelly Rombough (email), Rajveer Gandhi (email).

Learning Objectives

This assignment is meant for you to practice working with hashmaps and graphs. In particular, you will construct a graph of vertices and edges using a breadth-first or depth-first search. You will learn more in-depth about graph theory in MATH 240 and COMP 251. You will also implement one of the O(n log(n)) sorting algorithms that you’ve learned about in class, such as MergeSort or QuickSort.

General Instructions

• Submission instructions

– Please store all your files in a folder called “Assignment4”, zip the folder and submit it to myCourses. Inside your zipped folder, there must be the following files.

∗ Sorting.java

∗ SearchEngine.java

• Starter code is provided for this assignment. Do not change any of the class names, file names, method headers. You can add helper methods if you wish. Note also that for this assignment, you are NOT allowed to import any other class (all import statements other than the one provided in the starter code will be removed). In terms of package names, you can do whatever you wish. Any failure to comply with these rules will give you an automatic 0.

• You will automatically get 0 if your code does not compile.

Introduction

A search engine is software, usually accessed on the Internet, designed to carry out searches in a database of information according to the user’s query. The results provided are meant to best match what the user is trying to find and they are usually displayed in order of importance. The first search engine ever developed is considered to be Archie. It was named to resemble the word “archive”, and it was created in the 1990 by Alan Emtage, Bill Heelan and J. Peter Deutsch, computer science students at McGill. Today, there are many different search engines available on the Internet, each with their own abilities and features. The most popular of them all being Google.

A search engine performs the following tasks:

• Crawling and Indexing

• Ranking

• Searching

The starter code contains four classes:

• XmlParser: This class has two methods: one to read the content of the xml database (which will serve as proxy for a web page for our assignment) given a url, and the other to extract information from it.

– getContent(String url) returns an ArrayList of Strings corresponding to the set of words in the web page located at the given url. You will need to use this method while crawling in order to build your word index.

– getLinks(String url) returns an ArrayList of Strings containing all the hyperlinks going out of the given url. You will need this method to build the graph representing the data found while crawling.

You should NOT modify this class at all.

• MyWebGraph: This class implements the data structure needed to store the data collected during the crawling phase. It has an inner class called WebVertex which is used to store data related to a specific web page. You should NOT modify this class at all.

• SearchEngine: This is one of the classes in which you will have to add your code. You will be implementing methods that performs the three tasks described above.

• Sorting: This is utility class containing methods that implement some sorting algorithm. You will be asked to implement one of them.

Your task

In this assignment you are going to write a search engine program that will:

1. explore a portion of the web (which we’ll simulate through a database),

2. build an index of the words contained in each web page,

3. analyze the structure of the web graph to establish which web page should be ranked higher,

4. use this analysis to perform simple searches where a query word is entered by the user and a sorted list of relevant web pages available is returned.

Although we are going to apply these tools using a local database, what you will develop is a simplified version of the what is used at Google to answer actual web queries.

To be able to implement the search engine program described above, we need a graph data structure that will allow us to store all the information related to the web pages. Such class is provided to you.

[Provided] The class MyWebGraph is an implementation of a directed graph using adjacency lists. You will be using this type of data structure to store the information your program collects in the crawling phase. Each node in the graph will store a String corresponding to the url of a webpage. The class has the following field:

• A HashMap storing all the vertices in the graph. Note that we’ll be labelling each vertex with the String corresponding to the url of the webpage represented by this vertex.

The class has also the following public methods:

• The constructor MyWebGraph() which does not take any input and initializes the field with an empty HashMap.

• An addVertex() method which takes as input a String representing a url. The method adds the corresponding vertex to the graph.

• An addEdge() method which takes as input two Strings, i.e. two urls. The method adds to the graph an edge from the vertex labelled with the first input to the vertex labelled with the second input.

• A getNeighbors() method which takes as input a String representing a url and returns an ArrayList of all the hyperlinks contained in the specified url.

• A getVertices() method which returns the list of all the urls represented in the graph.

• A getEdgesInto() method that takes as input a String representing a url. The method returns an ArrayList of Strings of all the pages that contains an hyperlink to the specified url.

• A getOutDegree() method which takes as input a String representing a url and returns the number of hyperlinks in the specified page.

• A getPageRank() method which takes as input a String representing a url and returns the rank of the specified page.

• A setPageRank() method which takes as input a String representing a url and a double representing its rank. The method assigns the input number as the rank of the specified page.

• A getVisited() method which takes as input a String representing a url and returns whether or not the specified page has been visited.

• A setVisited() method which takes as input a String representing a url and a boolean. The method assigns the input boolean to the visited field of the specified page.

[20 points] The Sorting class is a utility class that at the moment contains a static method called slowSort(). This method takes as input a HashMap where the values are Comparable. The method returns an ArrayList containing all the keys in the map, sorted in descending

order based on the values they map to. The time complexity of slowSort is O(n2), where n is the number of pairs in the map. Your task is to implement a method called fastSort which performs the same task as slowSort but with a time complexity of O(n · log(n)).

[80 points] The SearchEngine class has the following fields:

• A HashMap called wordIndex used to represent the mapping from single words to a list of urls containing them.

• A MyWebGraph called internet which is used to store all relevant information regarding the structure of the webgraph.

• An XmlParser called parser which you should use to retrieve information for the database serving as a proxy for the web.

In this class, you should implement the following methods:

[35 points ] crawlAndIndex

This method takes a String as input representing a url. It will perform a graph traversal of the web, starting at the given url. You can use either a depth-first search or a breadthfirst search, and you can make it either recursive or non-recursive. For each url visited, the method should do the following:

• Update the web graph by adding the appropriate vertex and edges.

• Update the word index so that every word in the url just visited appear in the mapping.

Note that, it is possible for the graph to contain cycles. For instance, if it possible that two web pages link to each other. To prevent this method from getting stuck in an infinite loop, you should make sure to keep track of which web page has already been visited. This method should stop crawling once all web pages (in the database) have been visited.

[35 points ] assignPageRanks and computeRanks

• Good web pages are cited by many other pages. If we think about it in terms of the webgraph, this means that we should prefer web pages (i.e. vertices) with a large in-degree.

• Web pages that link to a large number of other pages are less valuable. In terms of webgraph, this means that we will value less web pages (i.e. vertices) with a large out-degree.

• A link from a web page is more valuable if the web page is itself a good one. In graph terms, higher the rank of a web page (i.e. vertex), more valuable an in-edge from it would be.

Note that the rank of a page depends solely on the structure of the graph we have created while crawling. To represent the ideas just described, let

• the pr(w) be the page rank of a vertex w

• the out(w) be the out-degree of a vertex w

• w1, w2, …, wk be all the vertices in the graph that have an out edge going into v.

Then, the following equation determines the page rank of a vertex v:

• Start by initializing pr(vi) to 1 for all 0 ≤ i ≤ N

• Repeat the following until convergence:

– compute pr(vi) for all i using the formula above.

This single step is what the helper method computeRanks should be doing. The method takes as input an ArrayList&lt;String&gt; representing the urls in the web graph and returns an ArrayList&lt;double&gt; representing the newly computed ranks for those urls. Note that the double in the output list is matched to the url in the input list using their position in the list. That is, the page rank of the url stored in position i in the input list, can be found in position i in the output list.

Convergence is reached when for all i, where prj(vi) represents the computation of pr(vi) in the j-th iteration, and is the input to the method. Note that, you can assume that the web graph does not contain self loops and every vertex in the graph has at least one outgoing edge.

Consider the following web graph:

0.01. We start by assigning value 1 to each of them:

• pr(A) = 1

• pr(B) = 1

• pr(C) = 1

• pr(D) = 1

Then we need to use the following formula (same as the formula above, but with damping factor of 0.5) to recompute the page ranks for each vertex, until convergence.

After the first iteration we get:

• pr(A) = 1/2 + 1/2 ∗ (1/3 + 1) = 7/6 = 1.166

• pr(B) = 1/2 + 1/2 ∗ (1/2) = 3/4 = 0.75

• pr(C) = 1/2 + 1/2 ∗ (1/2 + 1/3 + 1) = 17/12 = 1.416

• pr(D) = 1/2 + 1/2 ∗ (1/3) = 4/6 = 0.666

After the second iteration we get:

• pr(A) = 1/2 + 1/2 ∗ (0.75/3 + 1.416) = 1.333

• pr(B) = 1/2 + 1/2 ∗ (1.166/2) = 0.791

• pr(C) = 1/2 + 1/2 ∗ (1.166/2 + 0.75/3 + 0.666) = 1.25

• pr(D) = 1/2 + 1/2 ∗ (0.75/3) = 0.625

After 5 iterations we reach convergence since the difference between the rank values in the 4th iteration and the rank values in the fifth iteration is smaller than . The ranks at the end are:

• pr(A) = 1.270

• pr(B) = 0.819

• pr(C) = 1.274

• pr(D) = 0.636

[10 points ] getResults

This method takes as input a String representing a single-word query. It then returns an ArrayList of urls that contain such word, ordered based on their rank from most relevant to least relevant. This method will be called only after both crawlAndIndex and assignPageRanks have been executed. This method should use one of the sorting algorithms from the Sorting class. Ideally, it should use fastSort(), but if you did not implement it, you can use slowSort().

Testing

To test your code we provided you with two XML files that act as a proxy for the internet. The XML files contains proxy web-pages indicated by the tag name webpage. Each web-page contains multiple hyperlinks to other web-pages indicated by the tag link. The contents of a web-page is marked using the tag content. To help you with testing, we also provide the expected ranks of the web-pages computed using the algorithm described in the previous section. Note that rank is not part of an actual web-page, we simply provide them to help you with debugging. Page rank is indicated by tag rank and can be accessed in your code using the function XmlParser::getPageRank() which takes as input the name of the page.

• testAcyclic.xml – The provided tester use this database to test your code. Note that this database does not have any circular chains – making it easy for you to test and debug.

• test.xml – We do not provide any test cases for this database but is more general than the one above. We encourage you to create your tests with this database that will help you find more intricate issues with your code.

Finally, you should create your databases that are much larger as we will test on a much bigger database in the final grading.
