# cop3503-project-1---templated-linked-list-solved
**TO GET THIS SOLUTION VISIT:** [cop3503 Project 1 – Templated Linked List Solved](https://www.ankitcodinghub.com/product/cop3503-project-1-templated-linked-list-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;11495&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;cop3503 Project 1 – Templated Linked List Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
<h1>Overview</h1>
The purpose of this assignment is for you to write a data structure called a Linked List, which utilizes templates (similar to Java’s generics), in order to store any type of data. In addition, the nature of a Linked List will give you some experience dealing with non-contiguous memory organization. This will also give you more experience using pointers and memory management. Pointers, memory allocation, and understand how data is stored in memory will serve you well in a variety of situations, not just for an assignment like this.

<h1>Background</h1>
Remember Memory?

Variables, functions, pointers—everything takes up SOME space in memory. Sometimes that memory is occupied for only a short duration (a temporary variable in a function), sometimes that memory is allocated at the start of a program and hangs around for the lifetime of that program. Visualizing memory can be difficult sometimes, but very helpful. You may see diagrams of memory like this:

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/10/924.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

Or, you may see diagrams like these:

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/10/708.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

If you are trying to draw out some representation of memory to help you solve a problem, any of these (or some alternative that makes sense to you) will be fine.

<h2>Arrays</h2>
Arrays are stored in what is called <strong>contiguous</strong> memory. A contiguous memory block is one that is not interrupted by anything else (i.e. any other memory block). So if you created an array of 5 integers, each of those integers would be located one after the other in memory, with nothing else occupying memory between them. This is true for all arrays, of any data type.

&nbsp;

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/10/820.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">All of the data in an application is not guaranteed to be contiguous, nor does it need to be. Arrays are typically the simplest and fastest way to store data, but they have a grand total of zero features. You allocate one contiguous block, but you can’t resize it, removing elements is a pain (and slow), etc.

Consider the previous array. What if you wanted to add another element to that block of memory? If the surrounding memory is occupied, you can’t simply overwrite that with your new data element and expect good results.

&nbsp;

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/10/893.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

someArray[5] = 12; // #badIdea &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This will almost certainly break.

<table width="622">
<tbody>
<tr>
<td width="117">Other Memory</td>
<td width="46"></td>
<td width="46"></td>
<td width="46"></td>
<td width="46"></td>
<td width="46"></td>
<td width="275"></td>
</tr>
</tbody>
</table>
&nbsp;

In this scenario, in order to store one more element you would have to:

<ol>
<li>Create another array that was large enough to store all of the old elements plus the new one</li>
<li>Copy over all of the data elements one at a time (including the new element, at the end)</li>
<li>Free up the old array—no point in having two copies of the data</li>
</ol>
&nbsp;

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/10/128.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

<table width="618">
<tbody>
<tr>
<td width="80">Other Memory</td>
<td width="159">Newly available memory</td>
<td width="189">Someone else’s memory</td>
<td width="32"></td>
<td width="32"></td>
<td width="32"></td>
<td width="32"></td>
<td width="32">10</td>
<td width="32">12</td>
</tr>
</tbody>
</table>
This process has to be repeated each time you want to add to the array (either at the end, or insert in the middle), or remove anything from the array. It can quite costly, in terms of performance, to delete/rebuild an entire array every time you want to make a single change. Cue the Linked List!

<h2>Linked List</h2>
The basic concept behind a Linked List is simple:

<ol>
<li>It’s a container that stores its elements in a non-contiguous fashion</li>
<li>Each element knows about the location of the element which comes after it (and possibly before, more on that later)</li>
</ol>
So instead of a contiguous array, where element 4 comes after element 3, which comes after element 2, etc… you might have something like this:

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/10/871.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

Each element in the Linked List (typically referred to as a “node”) stores some data, and then stores a reference (a pointer, in C++), so the node which should come next. The First node knows only about the Second node. The Second node knows only about the Third, etc. The Fourth node has a null pointer as its “next” node, indicating that we’ve reached the end of the data.

A real-world example can be helpful as well.

Think about a line of people, with one person at the front of the line. That person might know about the person who is next in line, but no further than that (beyond him or herself, the person at the front doesn’t need to know or care). The second person in line might know about the third person in line, but no further. Continuing on this way, the last person in line knows that there is no one else that follows, so that must be the end. Since no one is behind that person, we must be at the end of the line.

&nbsp;

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/10/549.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

So… What are the advantages of storing data like this? When inserting elements to an array, the entire array has to be reallocated. With a Linked List, only a small number of elements are affected. Only elements surrounding the changed element need to be updated, and all other elements can remain unaffected. This makes the Linked List much more efficient when it comes to adding or removing elements.

Now, imagine one person wants to step out of line. If this were an array, all of the data would have to be reconstructed elsewhere. In a Linked List, only three nodes are affected: 1) The person leaving, 2) the person in front of that person, and 3) the person behind that person.

Imagine you are the person at the front of the line. You don’t really need to know or care what happens 10 people behind you, as that has no impact on you whatsoever.

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/10/393.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

If the 5<sup>th</sup> person in line leaves, the only parts of the line that should be impacted are the 4<sup>th</sup>, 5<sup>th</sup>, and 6<sup>th</sup> spaces.

<ol>
<li>Person 4 has a new “next” Person: whomever was behind the person behind them (Person 6).</li>
<li>Person 5 has to be removed from the list.</li>
<li>Person 6… actually does nothing. In this example, a Person only cares about whomever comes after them. Since Person 5 was before Person 6, Person 6 is unaffected. (A Linked List could be implemented with two-way information between nodes—more on that later).</li>
</ol>
The same thought-process can be applied if someone stepped into line (maybe a friend was holding their place):

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/10/379.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">In this case, Person 2 would change their “next” person from Person 3, to the new Person being added.

New Guy would have his “next” pointer set to whomever Person 2 was previously keeping track of, Person 3. Because of the ordering process, Person 3 would remain unchanged, as would anyone else in the list (aside from being a bit irritated at the New Guy for cutting in line).

So that’s the concept behind a Linked List. A series of “nodes” which are connected via pointer to one another, and inserting/deleting nodes is a faster process than deleting and reconstructing the entire collection of data. Now, how to go about creating that?

<h2>Terminology</h2>
<table width="623">
<tbody>
<tr>
<td width="126">Node</td>
<td width="498">The fundamental building block of a Linked List. A node contains the data actually being stored in the list, as well as 1 or more pointers to other nodes.

This is typically implemented as a <strong>nested class</strong> (see below).
</td>
</tr>
<tr>
<td width="126">Singly-linked</td>
<td width="498">A Linked List would be singly-linked if each node only has a single pointer to another node, typically a “next” pointer. This only allows for uni-directional traversal of the data—from beginning to end.</td>
</tr>
<tr>
<td width="126">Doubly-linked</td>
<td width="498">Each node contains 2 pointers: a “next” pointer and a “previous” pointer. This allows for bi-directional traversal of the data—either from front-to-back or backto-front.</td>
</tr>
<tr>
<td width="126">Head</td>
<td width="498">A pointer to the first node in the list, akin to index 0 of an array.</td>
</tr>
<tr>
<td width="126">Tail</td>
<td width="498">A pointer to the last node in the list. May or may not be used, depending on the implementation of the list.</td>
</tr>
</tbody>
</table>
&nbsp;

<h2>Nested Classes</h2>
The purpose of writing a class is to group data and functionality. The purpose of a <strong>nested</strong> class is the same—the only difference is where we declare a nested class. We declare a nested class like this:

<table width="623">
<tbody>
<tr>
<td width="246">class MyClass

{ public:

// Nested class&nbsp;&nbsp;&nbsp; class NestedClass

{

int x, y, z;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; NestedClass();&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~NestedClass(); &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;int SomeFunction();

}; private:

// Data for “MyClass”

NestedClass myData[5]; &nbsp;&nbsp;&nbsp;NestedClass *somePtr; &nbsp;&nbsp;&nbsp;float values[10];

MyClass();

// Etc…

};
</td>
<td width="378">// To create nested classes…

// Use the Scope Resolution Operator

MyClass::NestedClass someVariable;

&nbsp;

// With a class template…

TemplateClass&lt;float&gt; foo;

TemplateClass&lt;float&gt;::Nested bar;

&nbsp;

/* NOTE: You can make nested classes private if you wish, to prevent access to them outside of the encapsulating class. */
</td>
</tr>
</tbody>
</table>
Additional reading: <u><a href="http://en.cppreference.com/w/cpp/language/nested_types">http://en.cppreference.com/w/cpp/language/nested_types</a></u>

The nature of the Linked List is that each piece of information knows about the information which follows (or precedes) it. It would make sense, then, to create some nested class to group all of that information together.

&nbsp;

<h1>Benefits and Drawbacks</h1>
All data structures in programming (C++ or otherwise) have advantages and disadvantages. There is no “one size fits all” data structure. Some are faster (in some cases), some have smaller memory footprints, and some are more flexible in their functionality, which can make life easier for the programmer.

Linked List versus Array – Who Wins?

<table width="623">
<tbody>
<tr>
<td width="312"><strong>Array </strong></td>
<td width="312"><strong>Linked List </strong></td>
</tr>
<tr>
<td width="312">Fast access of individual elements as well as iteration over the entire array</td>
<td width="312">Changing the Linked List is fast – nodes can be inserted/removed very quickly</td>
</tr>
<tr>
<td width="312">Random access – You can quickly “jump” to the appropriate memory location of an element</td>
<td width="312">Less affected by memory fragmentation, nodes can fit anywhere in memory</td>
</tr>
<tr>
<td width="312">Changing the array is slow – Have to rebuild the entire array when adding/removing elements</td>
<td width="312">No random access, slow iteration</td>
</tr>
<tr>
<td width="312">Memory fragmentation can be an issue for arrays—need a single, contiguous block large enough for all of the data</td>
<td width="312">Extra memory overhead for nodes/pointers</td>
</tr>
<tr>
<td width="312"></td>
<td width="312">Slow to access individual elements</td>
</tr>
</tbody>
</table>
<h1>Code Structure</h1>
As shown above, the Linked List class itself stores very little data: Pointers to the first and last nodes, and a count. In some implementations, you might only have a pointer to the first node, and that’s it. In addition to those data members, your Linked List class must conform to the following interface:

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<h2>Function Reference</h2>
<table width="623">
<tbody>
<tr>
<td width="120"></td>
<td width="504"><strong>Accessors </strong></td>
</tr>
<tr>
<td width="120">PrintForward</td>
<td width="504">Iterator through all of the nodes and print out their values, one a time.</td>
</tr>
<tr>
<td width="120">PrintReverse</td>
<td width="504">Exactly the same as PrintForward, except completely the opposite.</td>
</tr>
<tr>
<td width="120">NodeCount</td>
<td width="504">Wait, we’re storing how many things in this list?</td>
</tr>
<tr>
<td width="120">FindAll</td>
<td width="504">Find all nodes which match the passed in parameter value, and store a pointer to that node in the passed in vector. Use of a parameter like this (passing a something in by reference, and storing data for later use) is called an <strong>output parameter</strong>.</td>
</tr>
<tr>
<td width="120">Find</td>
<td width="504">Find the <strong>first</strong> node with a data value matching the passed in parameter, returning a pointer to that node. Returns null if no matching node found. const and nonconst versions.</td>
</tr>
<tr>
<td width="120">GetNode</td>
<td width="504">Given an index, return a pointer to the node at that index. Throws an exception if the index is out of range. Const and non-const versions.</td>
</tr>
<tr>
<td width="120">Head</td>
<td width="504">Returns the head pointer. Const and non-const versions.</td>
</tr>
<tr>
<td width="120">Tail</td>
<td width="504">Returns the tail pointer. Const and non-const versions.</td>
</tr>
<tr>
<td width="120"></td>
<td width="504"><strong>Insertion Operations </strong></td>
</tr>
<tr>
<td width="120">AddHead</td>
<td width="504">Create a new Node at the front of the list to store the passed in parameter.</td>
</tr>
<tr>
<td width="120">AddTail</td>
<td width="504">Create a new Node at the end of the list to store the passed in parameter.</td>
</tr>
<tr>
<td width="120">AddNodesHead</td>
<td width="504">Given an array of values, insert a node for each of those at the beginning of the list, maintaining the original order.</td>
</tr>
<tr>
<td width="120">AddNodesTail</td>
<td width="504">Ditto, except adding to the end of the list.</td>
</tr>
<tr>
<td width="120">InsertAfter</td>
<td width="504">Given a pointer to a node, create a new node to store the passed in value, after the indicated node.</td>
</tr>
<tr>
<td width="120">InsertBefore</td>
<td width="504">Ditto, except insert the new node before the indicated node.</td>
</tr>
<tr>
<td width="120">InsertAt</td>
<td width="504">Inserts a new Node to store the first parameter, at the index-th location. So if you specified 4 as the index, the new Node should have 3 Nodes before it. Throws an exception if given an invalid index.</td>
</tr>
<tr>
<td width="120"></td>
<td width="504"><strong>Removal Operations </strong></td>
</tr>
<tr>
<td width="120">RemoveHead</td>
<td width="504">Deletes the first Node in the list. Returns whether or not the operation was successful.</td>
</tr>
<tr>
<td width="120">RemoveTail</td>
<td width="504">Deletes the last Node, returning whether or not the operation was successful.</td>
</tr>
<tr>
<td width="120">Remove</td>
<td width="504">Remove ALL Nodes containing values matching that of the passed-in parameter. Returns how many instances were removed.</td>
</tr>
<tr>
<td width="120">RemoveAt</td>
<td width="504">Deletes the index-th Node from the list, returning whether or not the operation was successful.</td>
</tr>
<tr>
<td width="120">Clear</td>
<td width="504">Deletes all Nodes. Don’t forget the node count!</td>
</tr>
<tr>
<td width="120"></td>
<td width="504"><strong>Operators </strong></td>
</tr>
<tr>
<td width="120">operator[]</td>
<td width="504">Overloaded brackets operator. Takes an index, and returns the index-th node. Throws an exception if given an invalid index. Const and non-const versions.</td>
</tr>
<tr>
<td width="120">operator=</td>
<td width="504">After listA = listB, listA == listB is true.</td>
</tr>
<tr>
<td width="120">operator==</td>
<td width="504">Overloaded equality operator. Given listA and listB, is listA equal to listB? What would make one Linked List equal to another? If each of its nodes were equal to the corresponding node of the other. (Similar to comparing two arrays, just with non-contiguous data).</td>
</tr>
<tr>
<td width="120"></td>
<td width="504"><strong>Construction / Destruction </strong></td>
</tr>
<tr>
<td width="120">LinkedList()</td>
<td width="504">Default constructor. A head, a tail, and a node counter walk into a bar… and get initialized? Wait, that’s not how that one goes… How many nodes in an empty list? What is head pointing to? What is tail pointing to?</td>
</tr>
<tr>
<td width="120">Copy Constructor</td>
<td width="504">Sets “this” to a copy of the passed in LinkedList. Other list has 10 nodes, with values of 1-10? “this” should too.</td>
</tr>
<tr>
<td width="120">~LinkedList()</td>
<td width="504">The usual. Clean up your mess. (Delete all the nodes created by the list.)</td>
</tr>
</tbody>
</table>
&nbsp;

<h1>Tips</h1>
A few tips for this assignment:

<ul>
<li>Remember the “Big Three” or the “Rule of Three” o If you define one of the three special functions (copy constructor, assignment operator, or destructor), you should define the other two</li>
<li>Start small, work one bit of functionality at a time. Work on things like Add() and PrintForward() first, as well as accessors (brackets operator, Head()/Tail(), etc). You can’t really test anything else unless those are working.</li>
<li>Refer back to the recommended chapters in your textbook as well as lecture videos for an explanation of the details of dynamic memory allocation o There are a lot of things to remember when memory allocation</li>
<li>The debugger is your friend! (You have learned how to use it, right?)</li>
<li>Make charts, diagrams, sketches of the problem. Memory is inherently difficult to visualize, find a way that works for you.</li>
<li>Don’t forget your node count!</li>
</ul>
