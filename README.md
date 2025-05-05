# java-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [Java Lab 2 Solved](https://www.ankitcodinghub.com/product/java-lab-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95411&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Java Lab 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ol start="0">
<li>The Transportation Problem
An instance of the Transportation Problem consists of source and destinations.

<ul>
<li>Each source has a given capacity, i.e. how many units of a commodity it is able to supply to the destinations.</li>
<li>Each destination demands a certain amount of commodities.</li>
<li>The cost of transporting a unit of commodity from each source to each
destination is given by a cost matrix (or function).

We consider the problem of determining the quantities to be transported from sources to destinations, in order to minimize the total transportation cost. The supply and demand constraints must be satisfied. (We may assume that all the values are integer).

Consider the following example.

D1D2D3Supply S1 2 3 1 10 S2 5 4 8 35 S3 5 6 8 25
</li>
</ul>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Demand 20 25 25

A solution may be something like that:

S1 -&gt; D3: 10 units * cost 1 = 10 S2 -&gt; D2: 25 units * cost 4 = 100 S2 -&gt; D3: 10*8 = 80

S3 -&gt; D1: 20*5 = 100

S3 -&gt; D3: 5*8 = 40 Total cost: 330

The main specifications of the application are: Compulsory (1p)

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
Create an object-oriented model of the problem. You should have (at least) the following classes: Source, Destination, Problem.

The sources and the destinations have names. The sources will also have the property type. The available types will be implemented as an enum . For

example:

</div>
</div>
<div class="layoutArea">
<div class="column">
•

• •}

</div>
</div>
<div class="layoutArea">
<div class="column">
public enum SourceType { WAREHOUSE, FACTORY;

</div>
</div>
<div class="layoutArea">
<div class="column">
Assume S1 is a factory and S2, S3 are warehouses.

<ul>
<li>Each class should have appropriate constructors, getters and setters.

Use the IDE features for code generation, such as generating getters and setters.</li>
<li>The toString method form the Object class must be properly overridden for all the classes.
Use the IDE features for code generation, for example (in NetBeans) press Alt+Ins or invoke the context menu, select “Insert Code” and then “toString()” (or simply start typing “toString” and then press Ctrl+Space).
</li>
<li>Create and print on the screen the instance of the problem described in the example.
Optional (2p)
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>Override the equals method form the Object class for the Source, Destination classes. The problem should not allow adding the same source or destination twice.</li>
<li>Instead of using an enum, create dedicated classes for warehouses and factories. Source will become abstract.</li>
<li>Create a class to describe the solution.</li>
<li>Implement a simple algorithm for creating a feasible solution to the problem
(one that satisfies the supply and demand constraints).
</li>
<li>Write doc comments in your source code and generate the class documentation
using javadoc. Bonus (2p)
</li>
</ul>
• Implement an algorithm in order to minimize the total cost, using either: o an heuristic, for example the Vogel’s approximation method

o an exact algorithm based on minimum cost network flows.

o your own idea (!?)

• Generate large random instances and analyze the performance of your algorithm (running times, memory consumption). Identify th e hot-spots in your code.

(Warning: No points are awarded unless the implementation can be clearly explained).

Resources

<ul>
<li>Slides</li>
<li>Tutorial: Object-Oriented Programming Concepts</li>
<li>Tutorial: Classes and Objects</li>
<li>Java Language Specification: Classes</li>
<li>Enum Types</li>
<li>The Date-Time package
Objectives
</li>
</ul>
<ul>
<li>Create a project containing multiple classes.</li>
<li>Instantiate classes and manipulate objects.</li>
<li>Understand the concepts of: object identity, object state, encapsulation,
property, accessors/mutators.
</li>
<li>Override methods of the Object class.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ul>
<li>Understand uni- and bi-directional relations among objects.</li>
<li>Understand the notion of multiplicity (one-to-one, one-to-many, many-to-
many).
</li>
<li>Implement instance-level relationships among objects (association).</li>
<li>Implement class-level relationships (generalization)</li>
<li>Work with abstract classes.</li>
<li>Get used to the naming conventions of the Java language.</li>
<li>Generate documentation using javadoc.</li>
</ul>
</div>
</div>
</div>
