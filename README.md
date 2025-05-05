# en-601-619-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [EN.601.619 Assignment 1 Solved](https://www.ankitcodinghub.com/product/en-601-619-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94996&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EN.601.619 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1 OpenFlow functionality with Mininet

Experimentation is an important part of networking research. However, large-scale cloud experiments can sometimes be hard to achieve, e.g., due to lack of machines. In this section, you will learn how to use Mininet1 , a relatively new experimental platform that can scale to hundreds or more emulated “nodes” running on a single machine. Mininet takes advantage of Linux support for network namespaces2 to virtualize the network on a single machine, so that dierent processes on the same machine can see their own network environments (like network interfaces, ARP tables, routing tables, etc.), distinct from other processes. Combined with the Mininet software, this enables a single machine to emulate a network of switches and hosts. The emulated processes, however, do see the same real/physical file system.

</div>
</div>
<div class="layoutArea">
<div class="column">
Mininet is designed with OpenFlow3 in mind. In this exercise, you will gain a basic understanding of OpenFlow and create a custom OpenFlow controller to control your switches. Quite simply, OpenFlow allows for “programmable” network devices, e.g., switches. With Mininet, each switch will connect to the controller specified when the switch is launched. When the switch receives an Ethernet frame, it consults its forwarding table for what to do with the frame. If it cannot determine what to do with the frame, the switch sends the frame (and some extra information such as the input switch port) to the controller, which will then instruct the switch on what to do with the frame. To avoid this extra work on every such frame, the controller can install a new rule/match in the switch’s forwarding table, so that the switch can forward future similar frames without having to contact the controller.

</div>
</div>
<div class="layoutArea">
<div class="column">
1http://mininet.org/ 2http://lwn.net/Articles/219794/ 3http://www.openflow.org/

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
EN.601.419/EN.601.619 Spring 2020

</div>
</div>
<div class="layoutArea">
<div class="column">
1.1 Prepare the Mininet VM and OpenFlow Controller

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Install VirtualBox from https://www.virtualbox.org/wiki/Downloads. VMware should also work; adjust your VM configurations accordingly. (It is possible to install Mininet directly on your Linux system, but for simplicity we’ll use the virtual machine here.)

</div>
</div>
<div class="layoutArea">
<div class="column">
2. DownloadandunziptheVMwithMininetalreadyinstalledfromhttp://onlab.vicci.org/mininet-vm/ mininet-2.2.1-150420-ubuntu-14.04-server-amd64.zip

You can also download VM images with Minine from https://github.com/mininet/mininet/ releases

</div>
</div>
<div class="layoutArea">
<div class="column">
3. In VirtualBox, import the “ovf” template just unzipped. For the newly imported machine, go to “Settings” ! “Network” and make “Adapter 1″ a “NAT” (Network Address Translation). If your VM is allowed to obtain an IP address from your local network, you can alternatively use “Bridge Adapter.”

</div>
</div>
<div class="layoutArea">
<div class="column">
For more information on networking with VirtualBox, see http://www.virtualbox.org/manual/

</div>
</div>
<div class="layoutArea">
<div class="column">
ch06.html

<ol start="4">
<li>StarttheVM</li>
<li>Loginwithmininetforbothusernameandpassword</li>
<li>Makesureeth0isup:
(a) runthecommand:

ifconfig eth0

(b) checktheinetaddrfield.IfitdoesnothaveanIPaddress,thenrunthecommand:
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>sudo dhclient eth0
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
and repeat step (a).

</div>
</div>
<div class="layoutArea">
<div class="column">
7. ThedownloadedimageshouldhavePOXpreinstalled.POXisaplatformthatallowsyoutowriteyour own OpenFlow controller using Python. Please check home folder and see if there is a folder called

</div>
</div>
<div class="layoutArea">
<div class="column">
“pox”. If not, please do:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>git clone https://github.com/noxrepo/pox
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
For more information on POX, see https://openflow.stanford.edu/display/ONL/POX+Wiki 8. InstallaGUIintheVM:

(a) InstalltheGUI

<pre>       sudo apt-get update
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>sudo apt-get install openbox xinit -y
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
(b) Startit

</div>
</div>
<div class="layoutArea">
<div class="column">
startx

(c) Tocreateanewterminal,right-clickonthedesktopandselect“Terminalemulator”

Alternately you may use SSH to log in to the VM remotely, with GUI (X11) forwarding. With SSH, you will need to enable X-forwarding (e.g., ssh -X on *NIX hosts) when you ssh into the VM. NOTE: this requires you have an X server running on the host. See a description of how to do this on various platforms at https://github.com/mininet/openflow-tutorial/wiki/ Installing-Required-Software. Alternative for some versions of Mac OS X: install the Developer Tools (a free download from the App Store) and open /Applications/Utilities/X11.

1.2 Create a hub in Mininet using POX

In this exercise you will create a Mininet network with 3 hosts connecting via a switch. Using POX, you will program the switch to behave like a hub, which simply forwards incoming packets to every port except the one on which it entered.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
EN.601.419/EN.601.619 Spring 2020

</div>
</div>
<div class="layoutArea">
<div class="column">
First, you can familiarize yourself with Mininet by following http://mininet.org/walkthrough/. To start Mininet with the topology we want:

<ul>
<li>Firstcleanupthenetwork:
sudo mn -c
</li>
<li>Thencreateanetworkwiththetopologywewant:
<pre>     sudo mn --topo single,3 --mac --switch ovsk --controller remote
</pre>
This will create a network with the following topology:

<pre>host h1 ------switch s1 ---- controller c0
host h2 -------/ /
host h3 --------/
</pre>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
After you create this network, you will be entering the Mininet console. You can type help in the console to see a list of commands provided by Mininet. We will later use some of these commands.

</div>
</div>
<div class="layoutArea">
<div class="column">
Now let’s run POX controller. Create another terminal (right-click on the desktop and select “Terminal emulator”). Go to the directory you installed POX in this new terminal, and then start POX with basic hub function:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>pox/pox.py log.level --DEBUG forwarding.hub
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
The argument log.level –DEBUG enables verbose logging and forwarding.hub asks POX to start the hub component. It takes up to 15 seconds for switches to connect to the controller. When a OpenFlow switch has connected, POX will print something like:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>   INFO:openflow.of_01:[00-00-00-00-00-01 1] connected
INFO:forwarding.hub:Hubifying 00-00-00-00-00-01
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
To verify the hub behavior, we use tcpdump, a common packet analyzer that intercepts and prints packet information. To do this, we first create an xterm (terminal emulator in X Window System) for each host in Mininet and view packets in each. To start an xterm for each host, type the following command in the Mininet console:

</div>
</div>
<div class="layoutArea">
<div class="column">
xterm h1 h2 h3

You may want to arrange xterms properly so that you can see them on the screen at once. You may need to reduce the terminal height to fit a laptop screen. In the xterms for h1 and h2, run tcpdump to capture and print all the packets:

<pre>   tcpdump -XX -n -i h1-eth0
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
and

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>tcpdump -XX -n -i h2-eth0
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
In the xterm for h3, send a ping to h1:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>   ping -c1 10.0.0.1
</pre>
The ping packets are going to the controller, which floods the packet out all interfaces but the received one. Because of this hub behavior, you should see identical ARP and ICMP packets in both xterms running tcpdump.

• [1points]A.1.1Whatwillhappenifyoupinganon-existenthostthatdoesn’treplyICMPrequests? For example, do the following command in the xterm for h3:

ping -c1 10.0.0.9

Submit and explain the results.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
EN.601.419/EN.601.619 Spring 2020

</div>
</div>
<div class="layoutArea">
<div class="column">
Now let’s take a look at the hub code at pox/pox/forwarding/hub.py. Make sure to get familiar with the code because many POX API functions used here will help you answer the later questions. We describe several important API functions here, and you can find more information about POX APIs at https://openflow.stanford.edu/display/ONL/POX+Wiki#POXWiki-POXAPIs.

</div>
</div>
<div class="layoutArea">
<div class="column">
• connection.send() function sends an OpenFlow message to a switch.

When the connection between a switch and the controller established, the code will invoke _handle_ConnectionUp() function that implements the hub logic.

</div>
</div>
<div class="layoutArea">
<div class="column">
• ofp_flow_mod OpenFlow message

This tells a switch to install a flow entry, which matches some fields of incoming packet headers and executes some actions on matching packets. Important fields include:

</div>
</div>
<div class="layoutArea">
<div class="column">
– actions: A list of actions that apply to matching packets (e.g., ofp_action_output described below).

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;match: An ofp_match object (described below).</li>
<li>– &nbsp;priority: When a packet matches on more than one non-exact flow entry, only the highest</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
priority entry will be used. Here, higher values are higher priority.

</div>
</div>
<div class="layoutArea">
<div class="column">
• ofp_action_outputclass

This is an action for use with of.ofp_flow_mod. You can use it to assign a switch port that you want to send the packet out of. It can also take “special” port numbers, e.g., we use OFPP_FLOOD to send the packet out all ports but the received one.

</div>
</div>
<div class="layoutArea">
<div class="column">
• ofp_match class (not used in the hub code but is useful in the assignment) This is an object that specifies packet header fields and input port to match on. All fields here are optional, i.e., if you do not specify a field, it becomes a “wildcard” field and will match on anything. Some important objects in this class:

</div>
</div>
<div class="layoutArea">
<div class="column">
– dl_src: The data link layer (MAC) source address

– dl_dst: The data link layer (MAC) destination address – in_port: The packet input switch port

Example to match packets with source MAC address 00:00:00:00:00:01 in a OpenFlow message msg: msg.match.dl_src = EthAddr(“00:00:00:00:00:01”)

1.3 Create a firewall

</div>
</div>
<div class="layoutArea">
<div class="column">
A firewall is used as a barrier to protect networked computers by blocking the malicious network trac generated by viruses and worms. In this assignment, you are asked to implement a data link layer firewall to block certain trac.

</div>
</div>
<div class="layoutArea">
<div class="column">
To start this, you will find a skeleton class file at http://soudeh.net/teaching/cloud/spring_ 2020/files/a1/firewall.py. This skeleton class is currently not blocking any trac and you will need to modify this skeleton code to add your own logic later. To test the firewall, put the firewall.py in the pox/pox/misc directory and run the POX controller:

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
EN.601.419/EN.601.619 Spring 2020

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>   ./pox.py log.level --DEBUG forwarding.hub misc.firewall
</pre>
Note: You may need to use the layer 2 MAC learning instead of the hub, i.e., you can replace the command above with:

<pre>   ./pox.py log.level --DEBUG forwarding.l2_learning misc.firewall
</pre>
After the connection between the controller and the switch is established, we can verify the connectivity between all pairs of hosts by typing pingall in the Mininet console. Note that when ping cannot get through a pair of hosts, you need to wait for the timeout, which takes about 10 seconds.

</div>
</div>
<div class="layoutArea">
<div class="column">
1.4

</div>
<div class="column">
• [1points]A.1.2Modifythefirewall(firewall.py)toblocktracwithsourceMACaddress00:00:00:00:00:02 and destination MAC address 00:00:00:00:00:03. To show the result, you can use the command pingall

and copy the output to your report. (Hint 1: this only takes a few lines of code. Hint 2: if you did not specify any action in a OpenFlow message, then matching packets will be dropped.)

What to turn in

</div>
</div>
<div class="layoutArea">
<div class="column">
Your submission should comprise two parts: 1) a part in your PDF document that answers the aforemen- tioned questions (2 points) and 2) a .zip file that contains your source code (3 points).

Note: To get your files o the VM, you can scp or ftp them to some other machine. Or you can install the GUI (instructions in PDF) and then “sudo apt-get install firefox” and then launch the GUI and use firefox to upload/email the files o the machine.

2 Playing with MapReduce

When discussing data analytic systems, we will see MapReduce as a paradigm for large-scale data processing. This part of the assignment provides practical experience writing MapReduce jobs.

2.1 Overview

</div>
</div>
<div class="layoutArea">
<div class="column">
The National Do Not Call Registry4 is a national database of telephone numbers of individuals who do not want to be contacted by telemarketers. Unfortunately, robocalls and spoofing are on the rise, leading to a record number of complaints in recent years.

</div>
</div>
<div class="layoutArea">
<div class="column">
In an eort to stop unwanted calls, law enforcement recently seized evidence from a cloud provider that assists businesses in contacting their customers.5 In the excitement of the raid, however, service metadata about the records and cloud consumers was damaged, leaving only portions of logs recording phone calls. Your goal is to uncover which cloud consumers are violating the law!

</div>
</div>
<div class="layoutArea">
<div class="column">
Fragments of the original call logs have been partially pieced together. Each log entry is a single line that provides the following information:

</div>
</div>
<div class="layoutArea">
<div class="column">
1. thedateandtimeofacall,

2. thecompanyresponsibleforthecall,

3. theoriginatingphonenumberforthecall, 4. therecipient’sphonenumber,and

5. thedurationofthecall(inseconds).

</div>
</div>
<div class="layoutArea">
<div class="column">
4https://www.donotcall.gov/

5The events that follow are fictitious. Any similarity to real life is purely incidental.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
EN.601.419/EN.601.619 Spring 2020

</div>
</div>
<div class="layoutArea">
<div class="column">
For example, the log entry indicates that the Acme Corporation used (429) 785-4094 to place a 9-second call to (429) 826-1640 slightly before 6 p.m. on 9 April 2017. Of course, this information alone is insucient to determine if this phone call is legitimate: one must know that 1) the first telephone number has been reported for spam calls or 2) the second telephone number is part of the Do Not Call Registry and reported this specific call as unwanted.

</div>
</div>
<div class="layoutArea">
<div class="column">
Law enforcement has identified that the following numbers reported unwanted calls during the time frame captured in the call log: (216) 684-9356, (404) 934-5110, (589) 371-5037, and (945) 792-0329. You may assume that all calls that appear in the log and were placed to these numbers are violations of the Do Not Call Registry. That is, no business contacted these numbers for legitimate reasons such as an order confirmation.

</div>
</div>
<div class="layoutArea">
<div class="column">
As part of your forensics investigation, you must answer the following questions:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>A.2.1OnhowmanyoccasionsdidcompaniesviolatetheDoNotCallRegistry?</li>
<li>A.2.2Howmanynumbersshouldbeblocked/markedasspamtoreducethenumberofunwanted</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
calls?

<ul>
<li>A.2.3Whichtelephonenumbersreceivedthemostspamcalls?</li>
<li>A.2.4Whichtelephonenumbersareresponsibleforthemostspamcalls?</li>
<li>A.2.5Whichhoursofthedayarespamcallsmostlikely?</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Although you technically need not use MapReduce to answer these questions, large-scale data analysis practically necessitates a parallel processing framework.

2.2 What to turn in

</div>
</div>
<div class="layoutArea">
<div class="column">
You may implement the MapReduce jobs using any programming language. For simplicity, consider using a scripting language (e.g., Python) and Hadoop’s streaming to facilitate testing your jobs.

</div>
</div>
<div class="layoutArea">
<div class="column">
For testing your implementation and answering questions, you can use the data file at http://soudeh. net/teaching/cloud/spring_2020/files/a1/mr.data.

</div>
</div>
<div class="layoutArea">
<div class="column">
Your submission should comprise two parts: 1) a part in your PDF document that answers the afore- mentioned questions and uses the guidance that follows for forming your responses to them (5 points) and 2) a .zip file that contains your source code (10 points). The source code archive should include all code used to answer each question, with the source code for each question in a separate directory named (01, 02, . . . ). That is, the root directory of the archive should contain a subdirectory for each question and each subdirectory could include all source code (i.e., implementation of the MapReduce job) used to answer that question. This archive must also include a script called “runall.sh” which will run all of your mapping and reducing jobs.

</div>
</div>
<div class="layoutArea">
<div class="column">
Please note that answering some questions may require post-processing of the MapReduce results (e.g., extracting only the top-3 hours that had the most spam calls). You are not required to submit any code used for such post-processing, as it is assumed that you can perform this step manually.

</div>
</div>
<div class="layoutArea">
<div class="column">
Specific guidance for answering each question follows.

</div>
</div>
<div class="layoutArea">
<div class="column">
A.2.1. On how many occasions did companies violate the Do Not Call Registry? For each company that violated the Do Not Call Registry list the number of known unwanted calls placed by that company. That is, how many times did each company contact one of the numbers that reported unwanted calls? Order your results lexicographically by company (i.e., alphabetically by company name).

</div>
</div>
<div class="layoutArea">
<div class="column">
Your answer should resemble the following:

6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
EN.601.419/EN.601.619 Spring 2020

Acme Corporation 4 …

A.2.2. How many numbers should be blocked / marked as spam to reduce the number of unwanted calls? What is the total number of telephone numbers that should be blocked for each company? These telephone numbers should be all numbers used by the companies guilty of violating the Do Not Call Registry. That is, if the company violated the Do Not Call Registry once, then assume that all its calls should be marked as spam. Order your results lexicographically by company (i.e., alphabetically by company name).

Acme Corporation 6411 …

A.2.3. Which telephone numbers received the most spam calls? List the top-3 telephone numbers receiving spam calls and how many spam calls each received. Order your results in decreasing order of the telephone number receiving the most calls.

(847) 580-3060 18 …

A.2.4. Which telephone numbers are responsible for the most spam calls? List the top-3 telephone numbers placing spam calls and how many calls originated from each. Order your results in decreasing order of the telephone number responsible for the most spam calls.

(202) 221-4130 77 …

A.2.5. Which hours of the day are spam calls most likely? List the top-3 hours that had the most spam calls and how many spam calls were placed in each hour. Order the results in decreasing order of the number of calls.

11 a.m. 3157 …

</div>
</div>
<div class="layoutArea">
<div class="column">
Your answer should resemble the following:

</div>
</div>
<div class="layoutArea">
<div class="column">
Your answer should resemble the following:

</div>
</div>
<div class="layoutArea">
<div class="column">
Your answer should resemble the following:

</div>
</div>
<div class="layoutArea">
<div class="column">
Your answer should resemble the following:

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
A Hadoop

</div>
</div>
<div class="layoutArea">
<div class="column">
Apache Hadoop1 is an open source software framework for big data processing. It has several components, but the two most critical to this assignment are its implementation of MapReduce and the Hadoop Distributed File System (HDFS), which are based on MapReduce [1] and the Google File System (GFS) [2] respectively.

</div>
</div>
<div class="layoutArea">
<div class="column">
For simplicity in this assignment, we’ll use Hadoop’s streaming application programming interface (API) which allows the use of any executable script to define the map and reduce operations. The streaming API uses the standard input and output streams to pass information among jobs. More specifically, the map operation coverts lines of input (text-based and terminated by a line break) into a series of key-value pairs, one per line of output. After these key-value pairs are sorted (automatically by Hadoop), the reduce operation aggregates them to produce a final value for each unique key. By convention, the streaming API uses the first tab character on a line to delimit the key and value.

</div>
</div>
<div class="layoutArea">
<div class="column">
An advantage of the streaming API is that you can use command line utilities to test your map and reduce operations. For example, the following shell command executes two Python scripts using a (small) local data file:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>cat /path/to/data | python map.py | sort | python reduce.py
</pre>
where cat prints the specified data files on standard out, map.py defines the map operation, sort sorts the script’s output in ascending order, and reduce.py defines the reduce operation. Of course, none of these steps are parallelized in this case, but Hadoop will perform the various operations in parallel when processing multiple data files.

B MapReduce

Writing a MapReduce job using the streaming API is straightforward. The canonical MapReduce example is counting words so we’ll use it to illustrate the process.

1 https://hadoop.apache.org/

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
As previously mentioned, the map operation reads input from standard in and outputs a series of key-value pairs, one per line. The following Python code implements this operation for counting words:

1 #!/usr/bin/env python 2

3 import sys

4

</div>
</div>
<div class="layoutArea">
<div class="column">
5

6 for 7

8

9

10 11 12 13

</div>
<div class="column">
line in sys.stdin:

line = line.strip() # remove leading and trailing whitespace

<pre># split line using whitespace as delimiters
</pre>
tokens = line.split() # iterate over tokens for token in tokens:

<pre>    print("{token}\t{count}".format(token=token, count=1))
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
That’s it! This Python code outputs a stream of tokens with a ‘1’ to indicate that each token was encountered once in the line of text. (If the same token appears multiple times, then it will be listed multiple times.) For example, the input

<pre>a man a plan a canal panama
</pre>
becomes

<pre>a
man
a
plan
a
canal
panama
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
i|1 i|1

i|1 i|1

i|1

i|1

i|1

</div>
</div>
<div class="layoutArea">
<div class="column">
where i| indicates a tab character (i.e., \t).

The reduce operation reads the key-value pairs and aggregates them to pro-

</div>
</div>
<div class="layoutArea">
<div class="column">
duce a final value for each key. Of course, its input must be sorted to produce the correct results. The following Python code implements this operation for counting words:

</div>
</div>
<div class="layoutArea">
<div class="column">
1 #!/usr/bin/env python 2

3 import sys

4

5

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
6

7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30

</div>
<div class="column">
<pre>def emit(token, count):
    print('{token}\t{count}'.format(token=token, count=count))
</pre>
<pre>previous = None
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
for

</div>
<div class="column">
line in sys.stdin:

line = line.strip() # remove leading and trailing whitespace

token, count = line.split(‘\t’, 1) # split key-value pair try:

<pre>    count = int(count)
except ValueError:
</pre>
continue

<pre>if previous == token:
    total = total + count
</pre>
<pre>else:
    if previous:
</pre>
<pre>        emit(previous, total)
    previous = token
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>        total = count
emit(token, total)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
In essence, this script simply checks to see if the prior token is the same as the current token, incrementing the total count when they match and outputting the total when they dier.

</div>
</div>
<div class="layoutArea">
<div class="column">
Try writing these scripts and testing them as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
echo “a man a plan a canal panama” | map.py | sort | reduce.py You should see the following result:

i|3

i|1

i|1 i|1

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>a
canal
man
panama
plan
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
i|1

(Note: Both scripts must be executable to invoke them in this fashion.)

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
References

[1] J. Dean and S. Ghemawat. MapReduce: Simplified Data Processing on Large Clusters. In Proceedings of the 6th Conference on Symposium on Opearting Systems Design &amp; Implementation, volume 6 of OSDI ’04, pages 10–10, 2004.

[2] S.Ghemawat,H.Gobio,andS.-T.Leung.TheGoogleFileSystem.InProceedings of the Nineteenth ACM Symposium on Operating Systems Principles (SOSP ’03), pages 29–43, 2003.

</div>
</div>
</div>
