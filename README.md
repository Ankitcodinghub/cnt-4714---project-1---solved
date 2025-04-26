# cnt-4714---project-1---solved
**TO GET THIS SOLUTION VISIT:** [CNT 4714 – Project  1 – Solved](https://www.ankitcodinghub.com/product/cnt-4714-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;65524&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CNT 4714 – Project &nbsp;1 – Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<strong>Title:</strong>&nbsp; “Project 1:&nbsp; Multi-threaded Programming in Java”

<strong>Objectives:</strong> To practice programming an application with multiple threads of execution and synchronizing their access to necessary shared objects.

<strong>Description:</strong>&nbsp; In this programming assignment you will simulate the package shipping management system for an automated package shipping operation similar to the one depicted here:

<img data-recalc-dims="1" decoding="async" class="aligncenter lazyloading" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/858.png?w=980&amp;ssl=1" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/858.png?w=980&amp;ssl=1">

&nbsp;

This example package shipping operation has five routing stations (S0 – S4), each of which has an input and output conveyor connecting to conveyor lines (C0 – C4) that go elsewhere in the system.&nbsp; Resources were limited when the system was built so each conveyor going to the rest of the facility must be shared between two routing stations.&nbsp; Since each routing station simultaneously needs an input and output connection to function, access to the shared conveyor lines must be strictly regulated.&nbsp; Flow direction in not important in our simulation.

&nbsp;

You have been hired to design a simulator for a new package management system being built with the same design, but possibly fewer/more stations.&nbsp; You are to implement this simulator in Java and have each routing station function in its own thread.&nbsp; A routing station moves packages from one of its connected conveyors to the other.&nbsp; A station’s workload is the number of times that a routing station needs to have exclusive access to the input and output conveyors during the simulation.&nbsp; Once a routing station is granted access to both conveyors it calls its doWork()method during which it will flow packages down each of its connected conveyors (of course it must verify that it has access and isn’t in conflict with another routing station).&nbsp; After the packages-in and packages-out methods are run, the workload of the routing station is reduced by 1 and the routing station will release both of the conveyors and signal waiting routing stations that the conveyors are available.&nbsp; After executing a flow and releasing its conveyors, a routing station should sleep for some random period of time.&nbsp; A routing station’s thread stops running when its workload reaches 0.&nbsp; To prevent deadlock, ensure that each routing station acquires locks on the conveyors it needs in increasing numerical order.

&nbsp;

<strong>Restrictions: </strong>

<ol>
<li>Your source files should begin with comments containing the following information:</li>
</ol>
<strong>/* </strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Name: <em>&lt;your name goes here&gt;</em> </strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Course: CNT 4714 Summer 2021 </strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Assignment title: Project 1 – Multi-threaded programming in Java </strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Date:&nbsp; June 6, 2021 </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Class:&nbsp; <em>&lt;name of class goes here&gt; </em></strong>

<strong>*/ </strong>

<ol start="2">
<li><strong>Do not</strong> use a monitor to control the synchronization in your program (i.e., do not use the Java synchronize statement).</li>
</ol>
&nbsp;

<strong>Input Specification:</strong>

Your program must initially read from a text file (config.txt) to gather configuration information for the simulator.&nbsp; The first line of the text file will be the number of routing stations to use during the simulation.&nbsp; Afterwards, there will be one line for each station.&nbsp; These lines will hold the amount of work each station needs to process (i.e, the number of times it needs to move packages down the conveyor system).&nbsp; Only use integers in your configuration file, decimals will not be needed.&nbsp; You can assume that the maximum number of stations will be 10.

<strong>&nbsp;</strong>

<strong>Output Specification:</strong>

Your simulator must output the following text to let the user know what the simulator is doing in each of these situations:

&nbsp;

<ol>
<li>An input conveyor is set:</li>
</ol>
<strong>Routing Station X: Input connection is set to conveyor number Cn.</strong>

&nbsp;

<ol start="2">
<li>An output conveyor is set:</li>
</ol>
<strong>Routing Station X: Output connection is set to conveyor number Cn. </strong>

&nbsp;

<ol start="3">
<li>A stations workload is set:</li>
</ol>
<strong>Routing Station X: Workload set. Station X has a total of n package groups to move.</strong>

&nbsp;

<ol start="4">
<li>A station is granted access to its input conveyor:</li>
</ol>
<strong>Station X: LOCK ACQUIRED! Now holding lock on input conveyor Cn.</strong>

&nbsp;

&nbsp;

<ol start="5">
<li>A station is granted access to its output conveyor:</li>
</ol>
<strong>Station X: LOCK ACQUIRED! Now holding lock on output conveyor Cn.</strong>

&nbsp;

<ol start="6">
<li>A station releasing access to its input conveyor:</li>
</ol>
<strong>Station X: Unlocks input conveyor Cn.</strong>

&nbsp;

<ol start="7">
<li>A station releasing access to its output conveyor:</li>
</ol>
<strong>Station X: Unable to lock output conveyor Cm – releasing lock on input conveyor Cn.</strong>

&nbsp;

<ol start="8">
<li>A station cannot obtain its second lock (on the output conveyor):</li>
</ol>
<strong>Station X: Unlocks output conveyor Cn&nbsp; </strong>

<ol start="9">
<li>A station successfully flows packages on input conveyor:</li>
</ol>
<strong>Station X: . . . Active. . . moving packages into station on input conveyor Cn. </strong>

<strong>&nbsp;</strong>

<ol start="10">
<li>A station successfully flows packages on output conveyor:</li>
</ol>
<strong>Station X: . . .Active. . .moving packages packages out of station on output conveyor Cn.&nbsp; </strong>

<ol start="11">
<li>A station completes a flow:</li>
</ol>
<strong>Station X: Number of packages groups left to move is: n.&nbsp; </strong>

<ol start="12">
<li>A station has completed its workload:</li>
</ol>
<strong>* * Station X: Workload successfully completed. * * Station Going Idle!</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Deliverables: </strong>

&nbsp;

Submit the following items via WebCourses no later than 11:59pm June 6, 2021.

<ul>
<li>All of your .java</li>
<li>A copy of a sample execution of your program, i.e., the output produced by your simulator (this should just be a text file). In your IDE, redirect console output to a file and include a copy of the entire output file produced by your program.</li>
</ul>
&nbsp;

<strong>&nbsp;</strong>

<strong>Additional Information: </strong>

&nbsp;

<strong>&nbsp;</strong>

Actual simulation run in Eclipse (console output redirected in this example) with <strong>config.txt containing 3 2 3 4</strong>, is shown below.

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/155.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

&nbsp;

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/864.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

&nbsp;

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/600.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

&nbsp;

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/941.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

&nbsp;

The example scenario below may help you to understand what is happening with a routing station and the acquisition of locks and work flow. Illustration is based only on S0 from the original configuration.

&nbsp;

<strong><u>Illustration of the timeline of a station in execution</u> </strong>

<strong>&nbsp;</strong>

<strong>Time 1:</strong>&nbsp; Station 0 needs to move a package group from input conveyor (conveyor 0) to the output conveyor (conveyor 4).&nbsp; It must acquire the locks on conveyor 0 and conveyor 4, in that order.&nbsp; If Station 1, currently holds the lock on conveyor 0, then Station 0 is blocked and must wait for conveyor 0 to become available.&nbsp; Note that Station 0 cannot attempt to lock conveyor 4 if it is unable to obtain the lock on conveyor 0.

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/161.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

&nbsp;

<strong>Time 2:</strong>&nbsp; Station 0 acquires lock on conveyor 0.&nbsp; Attempts to lock conveyor 4.&nbsp; If conveyor 4 is not available (Station 4 currently owns lock on conveyor 4), then Station 0 must release lock on conveyor 0 and block until both conveyor 0 and conveyor 4 can be obtained.

&nbsp;

&nbsp;

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/920.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

&nbsp;

&nbsp;

<strong>Time 3:</strong>&nbsp; Station 0 has acquired locks on conveyor 0 and conveyor 4.&nbsp; Packages now moving.

&nbsp;

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/886.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

<strong>Time 4:</strong>&nbsp; Station 0 has successfully moved 1 workload unit of packages from input side to output side.&nbsp; Station 0 releases locks on conveyor 0 and conveyor 4.&nbsp; Station 0 goes idle for random period of time if its workload is not yet 0, otherwise, Station 0 terminates.

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/06/643.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

&nbsp;

&nbsp;

&nbsp;
