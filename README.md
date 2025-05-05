# arp-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [ARP Assignment 1 Solved](https://www.ankitcodinghub.com/product/arp-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99750&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ARP Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
This document describes the specifications of ARP assignment, updated after the pandemic emergency.

The original specifications assumed that all students developed a single piece of code to be exchanged with other students, in order to carry out a cooperative experiment in the lab. As you know, labs will stay closed at least until September. Therefore, it is necessary to change the specifications and transform the cooperative project into an individual one. At the same time I want that what you have already developed will need very small modifications.

The new specifications convert the distributed/cooperative model into a single machine implementation. In the next page you can find the new specifications.

The document reports in yellow all the text changes with respect to the original sheet (V1.0). Students will produce the following documents:

<ol>
<li>source code with embedded comments (clearness is evaluated)</li>
<li>a script for compiling and executing</li>
<li>executable form</li>
<li>brief description of the source package, how to install, execution instructions</li>
<li>brief summary of the experiments and results</li>
<li>optional: generated wave plots (see final part of the document).</li>
</ol>
A repository will be setup in aulaweb for uploading the projects.

These rules are valid also for students who will do the exam in the next dates.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2019 ARP Assignment V2.0

The problem to be solved has the following specifications.

The goal is to simulate a network of multi-process systems, all identical, each one running on a machine in the same LAN, connected through sockets, exchanging a data token at a specified and measured speed. The number of machines is not given a priori. In figure 1 there are 4 machines as an example. They may be more, or less, or they may even reduce to one single machine for setup and debugging purposes.

Figure 1

In figure 2 the structure of each machine is defined. Note that a black frame encompasses each machine’s multi- process system, whereas a colored frame includes the system components that must developed by each student. Summing up, each student develops all system components of her/his machine, except for one, which is acquired by her/his partner “right side” student; in her/his turn, the student develops a component that is to be given to, and integrated by the”left side” student (“right” and “left” refer to the schema in figure 2).

Figure 2

</div>
</div>
<div class="layoutArea">
<div class="column">
Students will implement on a single machine all processes, simulating a distributed implementation. An artificial

</div>
</div>
<div class="layoutArea">
<div class="column">
delay (it will be called waiting time) will be used to mimic the network communication delays.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Glossary.

<ul>
<li> &nbsp;Circles are Posix processes.</li>
<li> &nbsp;Process P receives tokens, computes and sends an updated token after a given delay (see the waiting
time below).
</li>
<li> &nbsp;Process L logs data end events in a log file.</li>
<li> &nbsp;Process G receives tokens and dispatches them to P.</li>
<li> &nbsp;Process S receives console messages as Posix signals.</li>
<li> &nbsp;Processes S and G are connected to P through non-deterministic pipes (Posix select).</li>
<li> &nbsp;A socket connects P to the partner’s G process.
Detailed specifications.

A configuration file in the machine contains in text format the necessary parameters, and is edited by the user before running the multi-process:
</li>
</ul>
<ul>
<li> &nbsp;IP address of the machine and port numbers of processes (where relevant)</li>
<li> &nbsp;reference frequency (RF) of the generated token wave</li>
<li> &nbsp;waiting time (in microseconds) applied by process P before sending the updated token (initially: 1,000)</li>
<li> &nbsp;other relevant data to be read before starting.
Token is:

 a floating point number between -1. and 1, plus 

P does the following computation:

new token = received token + DT x (1. – (received token)^2/2) x 2 pi x RF

where DT is the time delay between the reception and delivery time instants (that ). In this way the token series forms a sine wave of frequency RF.

Log file

holds a series of text lines in couples: &lt;timestamp&gt; &lt;from G | from S &gt; &lt;value&gt; &lt;timestamp&gt; &lt;sent value&gt; (a sample of the wave)

The log file contents is output anytime G receives a suitable request from the console

S receives signals for carrying out the following actions:
</li>
</ul>
<ul>
<li> &nbsp;start (receiving tokens, computing, sending tokens)</li>
<li> &nbsp;stop ((receiving tokens, computing, sending tokens)</li>
<li> &nbsp;dump log: outputs the contents of the log file, separating the wave from the actions.
Start phase

P, G, S, L start using the parameters stored in the configuration file.

The process G is given by the “right side” student in executable form, and is run using the exec syscall.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
a time stamp with the absolute system time (by the operating system) of the instant P writes data on

</div>
</div>
<div class="layoutArea">
<div class="column">
socket.

</div>
</div>
<div class="layoutArea">
<div class="column">
must be measured by the

</div>
</div>
<div class="layoutArea">
<div class="column">
system

</div>
</div>
<div class="layoutArea">
<div class="column">
Note that DT takes into account the

</div>
</div>
<div class="layoutArea">
<div class="column">
waiting time written in the configuration file.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Main syscalls involved:

</div>
</div>
<div class="layoutArea">
<div class="column">
fork(), exec() pipe() select() read() write() socket() signal()

and related ones.

Organization and goal

Students should setup their own multi-process systems by implementing all components in a single machine.

</div>
</div>
<div class="layoutArea">
<div class="column">
The system components to implement are those in the red frame of figure 2 Referring to this figure, processes

</div>
</div>
<div class="layoutArea">
<div class="column">
Gn and Gn+1 coincide (only one process), as well as Pn and Pn-1.

</div>
</div>
<div class="layoutArea">
<div class="column">
The operating system is Ubuntu 16.04 LTS or later versions.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
The final test will be carried out by triple or quad groups of randomly selected students.

</div>
</div>
<div class="layoutArea">
<div class="column">
The code must be – mandatorily – such as all processes might run on separate machines.

</div>
</div>
<div class="layoutArea">
<div class="column">
Experiments will start with a waiting time

</div>
</div>
<div class="layoutArea">
<div class="column">
minimum waiting time compatible with their implementation.

</div>
</div>
<div class="layoutArea">
<div class="column">
value equal to 1,000 microseconds and a sine wave frequency

</div>
</div>
<div class="layoutArea">
<div class="column">
equal to 1; then, students will change those values in order to find the maximum RF frequency and the

</div>
</div>
<div class="layoutArea">
<div class="column">
A graphical interface for inspecting the generated wave is strongly recommended (e.g. using matlab or excel or

</div>
</div>
<div class="layoutArea">
<div class="column">
another app on the log file). Please give the processor and opsys types.

</div>
</div>
</div>
</div>
