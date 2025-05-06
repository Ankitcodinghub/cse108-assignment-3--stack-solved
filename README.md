# cse108-assignment-3--stack-solved
**TO GET THIS SOLUTION VISIT:** [CSE108 Assignment 3- Stack Solved](https://www.ankitcodinghub.com/product/cse108-assignment-3-stack-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96922&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE108 Assignment 3- Stack Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<strong>Introduction</strong>

Stack is a linear data structure that maintains LIFO (Last In First Out) ordering. So, while removing an element the one inserted last is removed at first. A stack can be implemented using an array or a linked list. However, for this problem, you have to follow an object oriented approach for its implementation.

A stack can have different functionalities like inserting an element, removing the most recently inserted element, reporting number of elements in the stack and so on. But in the object orient approach, you have to implement all these traditional and some special functionalities (details in next section) by calling appropriate functions of your defined class.

<strong>Problem Specification &amp; Instructions</strong>

You have to design &amp; implement a class named stack having the following operations. Specification of these operations &amp; what you need to do are also described in brief.

<ul>
<li><strong>Initialization: </strong>Write suitable constructor(s) so that your stack can be initialized &amp; memory can be dynamically allocated. How much memory you should allocate may or may not be specified in terms of number of elements. Besides, you may need to write a special constructor so that the memory which is dynamically allocated in an instance of your class (i.e. object) does not get accidentally erased in another resulting in runtime error/garbage value. Print appropriate messages in each of these constructors so that they can be easily distinguished (in case you need multiple ones).</li>
</ul>
<strong>&nbsp;</strong>

<ul>
<li><strong>Termination: </strong>Write suitable destructor(s) in which you should free dynamically allocated memory. Print appropriate messages in each of these destructors so that they can be easily distinguished (in case you need multiple ones).</li>
</ul>
<strong>&nbsp;</strong>

<ul>
<li><strong>Push: </strong>You should be able to insert an integer or an array of integers or another stack object into your stack. The example below illustrate each of these.</li>
</ul>
<table>
<tbody>
<tr>
<td width="181">Current elements in Stack</td>
<td width="180">Push</td>
<td width="207">Elements in Stack after Push</td>
</tr>
<tr>
<td width="181">2, 4</td>
<td width="180">10</td>
<td width="207">2, 4, 10</td>
</tr>
<tr>
<td width="181">2, 4</td>
<td width="180">Array, {8, 10}</td>
<td width="207">2, 4, 8, 10</td>
</tr>
<tr>
<td width="181">2, 4</td>
<td width="180">Stack with elements: 5, 6</td>
<td width="207">2, 4, 6, 5</td>
</tr>
</tbody>
</table>
&nbsp;

Write suitable functions to achieve this. Note that, name of the functions must be the same for all these push operations.

&nbsp;

<ul>
<li><strong>Pop: </strong>Removes the most recently inserted element from stack. Note that, this function will always return an integer.</li>
<li><strong>Top: </strong>Reports the most recently inserted element without removing it.</li>
<li><strong>Size: </strong>Reports number of elements currently in the stack.</li>
</ul>
<strong>&nbsp;</strong>

<ul>
<li><strong>Resize: </strong>Reallocate memory dynamically for the storage of elements in the stack. Note that, the stack must never have memory allocated for 10 more elements than it actually has. So, if there are <em>x </em>elements in the stack, already allocated memory cannot exceed memory required by <em>x</em>+10 elements. For example, say your stack has 9 integers and memory allocated for 10. Now if you push two integers, during the second push, you have to expand available memory so that a total of 20 integers can be inserted. But the already inserted elements must be retained. Similarly, if you pop twice next, there will be additionally allocated memory for 11 more integers. So, during the second pop, you have to reallocate memory again shrinking the available space for your stack. You can use two different definitions (not mandatory though) of this function for expanding and shrinking available memory.</li>
</ul>
&nbsp;

<ul>
<li><strong>Similarity: </strong>Write a function to check similarity between two stacks. You can calculate similarity by checking how many elements of a stack matches with corresponding ones of the other. A similarity score can be obtained by dividing it by the average size of the two stacks. Please see the following example for clarification.</li>
</ul>
<table>
<tbody>
<tr>
<td width="123">Stack – 1 Elements</td>
<td width="123">Stack – 2 Elements</td>
<td width="123"># of Elements Matched</td>
<td width="123">Average Size of Two Stacks</td>
<td width="123">Similarity Score</td>
</tr>
<tr>
<td width="123">2,4,6 [push 2, push 4, push 6]</td>
<td width="123">3,5,6</td>
<td width="123">1</td>
<td width="123">3</td>
<td width="123">1/3 = 0.3333</td>
</tr>
<tr>
<td width="123">2,4,6</td>
<td width="123">6</td>
<td width="123">1</td>
<td width="123">2</td>
<td width="123">1/2 = 0.5</td>
</tr>
<tr>
<td width="123">2,4,6</td>
<td width="123">4,2</td>
<td width="123">1</td>
<td width="123">2.5</td>
<td width="123">1/2.5 = 0.4</td>
</tr>
<tr>
<td width="123">2,4,6</td>
<td width="123">4,6,2</td>
<td width="123">0</td>
<td width="123">3</td>
<td width="123">0/3 = 0</td>
</tr>
</tbody>
</table>
<strong>

*</strong> You can use as many member variables and additional member functions as required for your implementation. But all your member variables must be private.

<strong>* </strong>There must be no method to access the elements of stack randomly from outside. You must use push &amp; pop/top for this purpose.

* All your functions (except main function) must be member functions of the stack class.

In the main function, you will create an instance of stack and push some integers into it, let us call it mainStack. You will also maintain a pointer of stack type, let us call the pointer tempStack (how you have to use it is mentioned in the next section).

<strong>Input Output Specification</strong>

You have to prompt for input in a loop in the main function. Show a menu like the one shown below. Note that all operations will be done on the mainStack.

<table>
<tbody>
<tr>
<td width="55">1:</td>
<td width="120">Push an element</td>
<td width="120">5:</td>
<td width="120">Top</td>
</tr>
<tr>
<td width="55">2:</td>
<td width="120">Push an array</td>
<td width="120">6:</td>
<td width="120">Size</td>
</tr>
<tr>
<td width="55">3:</td>
<td width="120">Push a stack</td>
<td width="120">7:</td>
<td width="120">Similarity</td>
</tr>
<tr>
<td width="55">4:</td>
<td width="120">Pop</td>
<td width="120">8:</td>
<td width="120">Exit</td>
</tr>
</tbody>
</table>
Based on the response, take necessary inputs next. For example, if the user chooses 2, take <em>n</em>+1 integers as input where <em>n </em>denotes the size of array followed by <em>n </em>elements of the array. Similarly if the user chooses 3 or 7, take <em>n</em>+1 integers as input where <em>n </em>denotes the size of stack&nbsp; followed by <em>n </em>elements of the stack. For this, allocate memory dynamically for tempStack using suitable constructor and <strong>push </strong>the elements sequentially into it. When you are done with the operation, free this allocated memory.

[Note that, <strong>Resize</strong> was not mentioned in the menu. So you need not call it from outside. Try to set its access specifier accordingly.]

Finally, when the user chooses 8, pop all the elements of the mainStack one by one &amp; print them.

<strong>Marks Distribution:</strong>

<table>
<tbody>
<tr>
<td width="55">Task</td>
<td width="96">Initialization</td>
<td width="94">Termination</td>
<td width="50">Push</td>
<td width="42">Pop</td>
<td width="42">Top</td>
<td width="42">Size</td>
<td width="57">Resize</td>
<td width="81">Similarity</td>
<td width="57">Total</td>
</tr>
<tr>
<td width="55">Marks</td>
<td width="96">5</td>
<td width="94">2</td>
<td width="50">5</td>
<td width="42">1</td>
<td width="42">1</td>
<td width="42">1</td>
<td width="57">2</td>
<td width="81">3</td>
<td width="57">20</td>
</tr>
</tbody>
</table>
&nbsp;

<strong>Special Instructions: </strong>

<ul>
<li><strong><em><u>You must not copy anyone’s code. If copy is found, you will be penalized severely resulting in a high risk of failing in the course. In this case, both students will face the same penalty, no matter who actually did it &amp; who copied.</u></em></strong></li>
</ul>
<strong><em><u>&nbsp;</u></em></strong>

<ul>
<li><strong><em><u>You must not copy from any source from internet. If you do so, you will face similar penalty as the one mentioned previously.</u></em></strong></li>
</ul>
<strong><em><u>&nbsp;</u></em></strong>

<ul>
<li>You can check the ” Practice_A2(Array_of_Object) File” program on moodle. It may help with your implementation.</li>
</ul>
&nbsp;

<ul>
<li>A thread titled “Offline 2 Queries” will be opened in the news forum of CSE108 on moodle. Please post your queries there.</li>
</ul>
