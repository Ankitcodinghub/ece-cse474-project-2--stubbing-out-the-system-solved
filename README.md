# ece-cse474-project-2--stubbing-out-the-system-solved
**TO GET THIS SOLUTION VISIT:** [ECE-CSE474 Project 2-“STUBBING OUT THE SYSTEM” Solved](https://www.ankitcodinghub.com/product/ece-cse474-project-2-stubbing-out-the-system-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97564&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE-CSE474 Project 2-“STUBBING OUT THE SYSTEM” Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
1.0 INTRODUCTION

Consider that your team has been contracted to implement a basic battery management system. You’ve been given this document as a basic framework / specification for what the customer wants. The labs in this course break down the development process as ‘milestones’ for the customer.

1.1 Development Phases

This project is the first phase in the development of a simple battery management system for high voltage electric transportation applications. The current phase focuses on “stubbing out the system”: design and development of the basic system architecture, modeling the instrumentation, establishing the high-level data/control flow, managing a basic scheduler (round robin), creating an initial display driver, and alarm annunciation

functions.

The initial deliverables in this project include the high-level system architecture, the ability to perform a subset of the necessary control, and portions of the display components. Subsequent phases (the next few projects) will continue to evolve the system architecture and flow of control, extend the driver development, and incorporate additional capabilities into both the measurement and display subsystems.

The final subsystem will be capable of collecting data from several different types of sensors, processing the data from those sensors, displaying it locally, and then transmitting it over a local area network to a remote terminal.

1.2 Layout of the Project / Guidelines for Success:

This series of projects is intended to mimic the design and development life cycle for bringing up an embedded system. Each project will present a set of software and hardware specifications…. lucky you!… the specs are already written! These specifications will guide you in how to implement both your code and the surrounding hardware which simulates the system.

A revision table, shown in Section 2.0 will serve as your guide in the development process. As we move into further development phases (future projects), the revision table will help you understand what has been changed / added / removed from the previous project. Hopefully

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
&nbsp;

this will get you in the habit of versioning both your specifications and your code. This is vital to traceability and will play an important role in your industry career.

Keep in mind that all projects from this point on will build on each other – it is important to ensure your project functions well!

1.3 Recommended Design Approach

This project involves designing, developing, and integrating a number of software components. On any such project, the approach one takes can greatly affect the ease at which the project comes together and the quality of the final product. To this end, we strongly encourage you to follow these guidelines:

<ol>
<li>Develop all of your UML diagrams first. This will give you both the static and dynamic structure of the system.</li>
<li>Block out the functionality of each module. This analysis should be based upon your use cases.
This will give you a chance think through how you want each module to work and

what you want it to do.
</li>
<li>Do a preliminary design of the tasks and associated data structures. This will give you
a chance to look at the big picture and to think about how you want your design to work before writing any code.

This analysis should be based upon your UML class/task diagrams.
</li>
<li>Write the pseudo code for the system and for each of the constituent modules.</li>
<li>Develop the high-level flow of control in your system. This analysis should be based
upon your activity and sequence diagrams. Then code the top-level structure of your system with the bodies of each module stubbed out.

This will enable you to verify the flow of control within your system works and that you are able to invoke each of your procedures and have them return the expected results in the expected place.
</li>
<li>When you are ready to create the project in the Arduino IDE, it is strongly recommended that you follow these steps:
<ol>
<li>Build your project.</li>
<li>Correct any compile errors and warnings.</li>
<li>Test your code.</li>
<li>Repeat steps a-c as necessary.</li>
<li>Write your report</li>
<li>Demo your project.</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
g. Go play.

2.0 REVISIONS

Table 1 – Project Revision Table (Version Control) Version Date Author Description

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
11 Jan 2021

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
J.Vining

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
First release of initial architecture specification: Working with system architecture, a round robin scheduler, task control blocks, and general I/O to implement the first phase of a battery management system

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
3.0 BACKGROUND

Did well on Project 1, put in at least 100 hours per week. No need to sleep – it’s over rated anyway.

3.1 Cautions and Warnings

Never try to run your system with the power turned off. Under such circumstances, the

results are generally less than satisfying.

Always keep only a single copy of your source code. This ensures that you will always have a maximum amount of disk space available for games, email, and some interesting pictures. If a code eating gremlin happens to destroy your only copy, not to worry, you can always retype and debug it again….

4.0 PROJECT OBJECTIVES

In this lab, we will begin work with the Arduino Mega (the “System Controller”). This work has the following goals:

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
<ul>
<li>Introduce and work with formal design methodologies and specifications:
<ul>
<li>– &nbsp;Utilize UML diagrams to model static and dynamic aspects of the system – Use Cases, Functional Decomposition, Sequence Diagrams, State Charts, and Data
and Control Flow Diagrams
</li>
<li>– &nbsp;Identify major functional blocks</li>
<li>– &nbsp;Architect the system software as a collection of tasks</li>
</ul>
</li>
<li>Use software delay/timing functions to develop a simple time-based operating system kernel and scheduler that will schedule and dispatch tasks</li>
<li>Introduce task control block structures to perform intertask / interprocess communication</li>
<li>Introduce simple tasks and a task queue: Stub out, model, and simulate the desired behavior of tasks</li>
<li>Use basic input/output operations:
<ul>
<li>– &nbsp;Begin the design of a driver to control a touch screen display</li>
<li>– &nbsp;Use external circuits to simulate digital I/O</li>
</ul>
</li>
<li>Implement and test the system</li>
<li>Empirically determine execution time of each such task</li>
<li>Share data between tasks using C pointers and data structs: develop and build
background on C pointers, the passing of pointers to subroutines, and manipulating them in subroutines

This project, project report, and program are to be done as a team – play nice, share the equipment, keep any viruses (software or otherwise) to yourself, and no fighting.
</li>
</ul>
5.0 SYSTEM ARCHITECTURE

The following two sections define the system architecture in terms of both the (1) Hardware Architecture and (2) Software Architecture. The system architecture specifies the functional components and their interactions in hardware and software. As such, the following sections are divided between the hardware and software architectures.

General System Description:

Battery management systems (BMS) are required to ensure the safety, proper operation and long-term reliability of high voltage batteries in electric transportation applications. The system architecture presented is a simplified but representative approach to battery management.

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
6.0 HARDWARE ARCHITECTURE

The hardware architecture described in this subsection presents the system hardware inputs and outputs as well as the overall layout of the system.

We will be simulating a majority of the following inputs with the exception of the touch screen and accelerometer.

6.1 Inputs

For this stage of the project, the digital inputs highlighted in grey will be implemented in

hardware and the analog input sensors highlighted in blue will be stubbed out in code. Digital:

Analog:

• Accelerometer 6.2 Outputs

Digital:

<ul>
<li>Contactor on/off (shown via LEDs)</li>
<li>Touch screen display</li>
</ul>
6.3 I/O Interface Circuits

The circuit diagrams used to model the hardware I/O are provided in Section 7.0 Software Architecture, under the task that accesses the circuit. You will use these as a guide to model/simulate/create the hardware interfaces for your project.

</div>
</div>
<div class="layoutArea">
<div class="column">
• High voltage interlock loop (HVIL) signal – digital input actuated via switch

</div>
</div>
<div class="layoutArea">
<div class="column">
• Touch screen feedback

</div>
</div>
<div class="layoutArea">
<div class="column">
• HV terminal voltage

</div>
</div>
<div class="layoutArea">
<div class="column">
• HV terminal current

</div>
</div>
<div class="layoutArea">
<div class="column">
• Temperature

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
6.4 Block Diagram

The prototype will be implemented using an ATMega development board, a touch screen display, and external circuitry to mimic a HV battery system.

While we will not be implementing everything shown at this point, the diagram in Figure 1 is intended to give you an idea of how the final system architecture will be structured from a hardware perspective. This diagram provides a high-level partially complete block diagram for the system, including all major functional blocks. WE WILL ONLY BE IMPLEMENTING ITEMS IN LIGHT GREY in this project.

Note this is not a complete block diagram, you will need to format the diagram properly by adding hardware I/O information and signal information. ONLY INCLUDE ITEMS IN GREY FOR YOUR BLOCK DIAGRAM.

Figure 1 – High-Level Partially Complete Block Diagram of the Battery Management System (BMS). NOTE: Items in light grey are implemented in this project

7.0 SOFTWARE ARCHITECTURE

The software architecture describes the structure and functionality of the software. Software architecture is about making fundamental structural choices that are costly to change once implemented. These are documented in UML (Unified Modeling Language) diagrams, aka software architecture diagrams.

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
Creating solid code structure is an integral part of embedded system design. Doing so aids in debugging and maintaining/updating code. Your code shall be structured using the TCBs described in the Appendix, Section 9.1 Implementing the TCB.

Your code will include the following tasks:

*Only the tasks highlighted in grey will be implemented at this stage of the project*

<ul>
<li>Measurement History (Data Logging)</li>
<li>Touch Screen Task: Display &amp; Touch Input</li>
<li>Remote Terminal</li>
<li>HVIL Interrupt</li>
<li>Hardware Timer Interrupt
The following subsections describe each of the major functional tasks, as they pertain to this stage of the project. Functionality of each of these tasks shall be modified and expanded as the project moves forward.
</li>
</ul>
7.1 Startup Task: setup()

The Startup Task is the first task to execute and runs only once when the embedded controller wakes up or resets. The startup task shall reside in the Arduino language’s setup() function which is configured to run once during startup.

This task initializes all: • Hardware

o System time base (timers, etc.)

o GPIO (general purpose input/output)

o Communication protocols (UART serial bus, etc) o Interrupts, etc.

• Software (( see Section 9.1 on how to declare &amp; initialize these )) o Task data structures

o Task control blocks (TCB)

</div>
</div>
<div class="layoutArea">
<div class="column">
• Startup

</div>
</div>
<div class="layoutArea">
<div class="column">
• Scheduler

</div>
</div>
<div class="layoutArea">
<div class="column">
• Measurement

</div>
</div>
<div class="layoutArea">
<div class="column">
• SOC (State of Charge Calculation)

</div>
</div>
<div class="layoutArea">
<div class="column">
• Contactor

</div>
</div>
<div class="layoutArea">
<div class="column">
• Alarm

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
&nbsp;

7.2 Scheduling Task

The Scheduling Task is executed in the main loop – for the Arduino language, this is the loop() function. This task takes care of scheduling and executing the system tasks that make the BMS function.

There are several methods for implementing the task queue and scheduling. We will begin with the Round Robin Scheduler, and as the quarter progresses, the complexity of our scheduler will progressively increase until we’ve created a real-time embedded operating system.

7.2.1 Round Robin Scheduler

The Round Robin (RR) scheduler is one of the simplest of all scheduler algorithms. It runs each task from the task queue in succession, assigning each task an equal time slice (time quanta) to run. For now, we will assume that each of our tasks take the same time to execute.

• If a task is not to be run during the current round (i.e. the flag for executing that task is not set), the scheduler skips execution of that task.

• Tasks shall not be pre-emptable (each task will run to completion without interruption).

• If a task has nothing to do, it shall exit immediately.

In this lab, the Arduino software timer function, delay(), shall pace execution of all tasks

within the main loop – more on this below.

7.2.2 Round Robin Task Queue Implementation

How to build the task queue?

The task queue is an array of elements consisting of pointers to variables of type TCB. The Schedule Task executes each TCB in the array and then returns to the main loop where it is called again once the software delay is expired.

The TCB elements in the queue correspond to tasks identified in Section 7.0. Extra elements in the array can provide space for future capabilities.

7.2.3 Creating the Round Robin Scheduler

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
Write a program that will run forever. Typically this consists of an infinite while loop; however in the Arduino language, we use the loop() function which runs indefinitely. Your code should look something like this:

<pre>unsigned long time_in_ms;
void loop()
</pre>
{ Scheduler();

} delay(time_in_ms);

The Scheduler() task should index through the task queue and call each of the functions in turn. Be sure to implement your queue so that when it gets to the last element, it wraps back around to the head of the queue.

7.2.4 Associating Real Time with the Scheduler

You will add a timing delay to your loop so that you can associate real time with your main

loop.

For example, if the Scheduler task takes 80ms to run and the delay is set to 20ms, each task in the scheduler executes once per 100ms. By incrementing a counter each time the loop executes, we can associate that counter with the cycle time of the loop – 100ms in this case.

This is how we will create timers / counters to implement the cycling rates for each of the measurement items – see Section 7.4 Measurement Tasks: Sensor Measurements.

To accomplish this, we use the delay function: “delay(unsigned long time_in_ms)”. Simply call this function with the delay in milliseconds as its argument. Remember Project 1…

The scheduler shall execute all tasks at a 1sec period (1Hz). In other words, each task shall execute once per second. You will need to figure out what delay is required for this to occur.

7.3 Touch Screen Task: Display &amp; Touch Input

The touch screen display task shall include display and touch input functionality.

</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="layoutArea">
<div class="column">
Tips:

•

•

7.3.1

</div>
</div>
<div class="layoutArea">
<div class="column">
You will find it advantageous to create separate functions for touch input and display. For the display: Only update values on the screen that are changing so your code executes faster.

Touch Input

</div>
</div>
<div class="layoutArea">
<div class="column">
The display shall provide user input buttons to scroll through the following screens:

<ul>
<li>Measurement Screen: Scroll thru measurements</li>
<li>Alarm Screen: Scroll thru / acknowledge alarms</li>
<li>Battery ON/OFF Screen: Option to turn ON / OFF battery
You may use “next” and “previous” buttons or a single button for each screen.

7.3.1.1 Screen-Specific Input: Battery ON/OFF Screen

The Battery ON/OFF screen has the same scroll buttons as the other screens PLUS an additional input: an ON / OFF toggle switch. The toggle switch provides user input to turn ON or OFF the battery. See the next section, “Display”, for more details.

7.3.2 Display

The display consists of three screens, described below. The display task shall access shared variables from the following tasks to populate the measurement and alarm screens: Measurement, SOC, and Alarm.

7.3.2.1 MeasurementScreen

The Measurement Screen shall display the following sensor data:
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>State of Charge:</li>
<li>Temperature:</li>
<li>HV Current:</li>
<li>HV Voltage:</li>
</ul>
</div>
<div class="column">
&lt;value&gt; &lt;value&gt; &lt;value&gt; &lt;value&gt;

</div>
</div>
<div class="layoutArea">
<div class="column">
• HVIL (HV Interlock Loop) Status: &lt;value&gt;

Note that only the HVIL Status (highlighted in grey) will be implemented in hardware at this phase. All other data will be software generated according to specifications in 7.4 and 7.5.

</div>
</div>
</div>
<div class="page" title="Page 16">
<div class="layoutArea">
<div class="column">
7.3.2.2 AlarmScreen

The Alarm Screen shall display the value of each of the alarms as listed in Section 7.7.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>High Voltage Interlock Alarm:</li>
<li>Overcurrent:</li>
<li>High Voltage Out of Range:
7.3.2.3 BatteryON/OFFScreen
</li>
</ul>
</div>
<div class="column">
&lt;state&gt; &lt;state&gt; &lt;state&gt;

</div>
</div>
<div class="layoutArea">
<div class="column">
The Battery ON/OFF Screen shall display the current state of the battery contactors as well as a toggle switch to allow user input to turn ON or OFF the battery. The two toggle switch states yield the following actions:

<ul>
<li>Turn ON… (CLOSE contactors by sending flag to the Contactor Task)</li>
<li>Turn OFF… (OPEN contactors by sending flag to the Contactor Task)
Note that the flag is a shared variable that is passed to the Contactor Task. This tells the Contactor Task what state the user wants the battery to be in.
</li>
</ul>
7.4 Measurement Tasks: Sensor Measurements

Measurements shall be taken to provide both the BMS and outside world with the system state according to the block diagram in Figure 1.

At this stage in the project, most of the measurements are simulated by software other than HVIL. As the project progresses, all measurements will be physically sampled.

7.4.1 Temperature, HV Current &amp; Voltage Measurements

The measurement task shall update the following measurement values as described. As mentioned in Section 7.3.2, the touch screen display shall access this data via shared measurement variables.

Each measurement value should be held for the amount time indicated. For a 1s rate, each value is held for 1s.

• Temperature:

o Cycle thru values [-10, 5, 25] at a 1s rate

</div>
</div>
</div>
<div class="page" title="Page 17">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
• •

7.4.2

</div>
<div class="column">
HV Current:

o Cycle thru values [-20, 0, 20] at a 2s rate

HV Voltage:

o Cycle thru values [10, 150, 450] at a 3s rate

High Voltage Interlock Loop (HVIL)

</div>
</div>
<div class="layoutArea">
<div class="column">
At this stage, there is only one physical measurement being taken: • HV Interlock Loop

This measurement shall be stored in a shared variable for inter-task data exchange with the display, similar to the other measurement values.

7.4.2.1 Test Circuit for HVIL: DIGITAL INPUT

Description of circuit in real-world application:

The high voltage interlock loop is a circuit that detects whether or not all high voltage connectors are connected since its circuit runs alongside the high voltage cabling. The circuit provides a safety check for the battery management system to ensure that no exposed high voltage cabling is present under operating conditions.

There are many means to implement one of these loops and the detection circuit that reads whether the HVIL is OPEN or CLOSED. For this project, we will simulate a HVIL detection circuit that provides a digital reading to the microcontroller of whether the loop is OPEN or CLOSED.

Implementation:

The circuit in Figure 2 shows how to simulate the HVIL detection circuit’s connection to the microcontroller by using a DIP switch to OPEN and CLOSE the circuit. The expected input at the microcontroller should be (notice these are states):

<ul>
<li>OPEN DIP switch:

o Produces 5V at the digital input pin (reading logic 1) o LED will not light up

o HVIL is OPEN!</li>
<li>CLOSED DIP switch

o Produces 0V at the digital input pin (reading logic 0) o LED will light up

o HVIL is CLOSED, yay, no danger!</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 18">
<div class="layoutArea">
<div class="column">
Figure 2 – DIGITAL INPUT: Test Circuit for High Voltage Interlock Loop (HVIL)

7.5 SOC Task: Calculating Battery State of Charge (SOC)

The battery management system shall track the state of charge (SOC) of the high voltage battery. There are many methods to calculate state of charge, with more advanced systems using coulomb counting and neural networks to track the charge state of the battery.

For this phase of the project, the following values shall be used for the SOC. As mentioned in Section 7.3.2, the touch screen display task will share access to the SOC variable.

• State of Charge:

o Cycle thru values [0, 50, 100] at a 1s rate

7.6 Contactor Task: Setting Contactors (signified by LED output)

As discussed in Section 7.6.1 “Simulated Contactor Output Circuit”, contactors are a safety mechanism to protect the external world from the high voltage potential inside the battery. Within the context of this lab, the functionality of the Contactor Task is to show that logic exists for actuating the contactors properly so that when a power circuit is made available to actuate an actual contactor solenoid, it would function as specified.

For the purposes of this lab, the Contactor Task shall actuate the digital output pin associated with the contactor simulation circuit defined in Section 7.6.1.

States for contactors are:

1. &lt;state1&gt;: “OPEN” (default/entry state) 2. &lt;state2&gt;: “CLOSED”

</div>
</div>
</div>
<div class="page" title="Page 19">
<div class="layoutArea">
<div class="column">
The logic for moving between these states is as follows:

<ul>
<li>Contactors shall be initially OPEN.</li>
<li>Contactors shall transition to CLOSED when user inputs a request to TURN ON
BATTERY (i.e. CLOSE contactors).

NOTE: Request to OPEN/CLOSE contactors shall come in the form of a flag from the Display Task’s Battery ON/OFF screen. The Contactor Task shall acknowledge the flag after it has acted upon it.

In a real-world system, the OPEN/CLOSE command for the contactors will likely come from another embedded controller in charge of components that the high voltage battery rails interfaces with. This exercise puts that command in the user’s hands and can be considered a debugging tool.
</li>
</ul>
7.6.1 Simulated Contactor Output Circuit: DIGITAL OUTPUT

Description of circuit in real-world application:

High voltage contactors provide a means to disconnect the battery’s high voltage rails from the external world. A typical contactor for this application is actuated by a solenoid, which requires more current to actuate that the microcontroller can source / sink

Important point to note! Microcontrollers are limited in their capability to drive digital outputs over a few watts. Most microcontrollers require external, board-mounted FETs to drive signals requiring higher power levels.

Implementation:

For the purposes of this exercise, the contactor shall be modeled using an LED in series with a resistor as shown in Figure 3. This circuit allows for software simulation with visual confirmation that the output pin is being actuated.

Figure 3 – DIGITAL OUTPUT: Test Circuit for Simulating Contactors

</div>
</div>
</div>
<div class="page" title="Page 20">
<div class="layoutArea">
<div class="column">
7.7 Alarm Task

There are three alarms defined for the battery management system, each has three states:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>&lt;state1&gt;:</li>
<li>&lt;state2&gt;:</li>
<li>&lt;state3&gt;:</li>
</ol>
</div>
<div class="column">
“NOT ACTIVE”

ACTIVE, NOT ACKNOWLEDGED ACTIVE, ACKNOWLEDGED

</div>
</div>
<div class="layoutArea">
<div class="column">
The following values shall be used for the shared global variables associated with each alarm. As mentioned in Section 7.3.2, the touch screen display will access these shared global alarm variables to display.

• HVIL (High Voltage Interlock Alarm):

o Cycle thru values [&lt;state1&gt;, &lt;state2&gt;, &lt;state3&gt;] at a 1s rate

• Overcurrent

o Cycle thru values [&lt;state1&gt;, &lt;state2&gt;, &lt;state3&gt;] at a 2s rate

• High Voltage Out of Range

o Cycle thru values [&lt;state1&gt;, &lt;state2&gt;, &lt;state3&gt;] at a 3s rate

</div>
</div>
</div>
<div class="page" title="Page 21">
<div class="layoutArea">
<div class="column">
8.0 DELIVERABLES

Write your Project Report according to the rubric. The project report will be graded

according to the rubric.

Include figures of the following in the Software Implementation section.

 Each figure must be REFERENCED in the text. Use the figures to explain your

software design…

“…The system block diagram of Figure 1 shows the ports and pin numbers that the inputs X, Y, Z go into…”

“…The data flow diagram of Figure 2 shows how data flows from input X to tasks A, B, C…”

<ul>
<li>System block diagram showing the ATmega input and output ports (and port numbers) labeled per I/O component</li>
<li>Structure chart showing functional decomposition of tasks within the System Controller.</li>
<li>Class/task diagram showing the structure of tasks within the System Controller as reflected in the structure chart.
o These diagrams should include the task name, global variables used in the task and how they are structured with respect to each other.
</li>
<li>Data flow diagrams for all inputs and outputs

o Hint: The touch screen can be considered as one input/output unit</li>
<li>Activity diagram for the showing the System Controller’s dynamic behavior from initial entry into the loop() function.</li>
</ul>
o This will include the Scheduler task and all the tasks that it calls.

o Hint: The scheduler task can be represented by branch and merge – the

branch condition is the for loop index, and each branch is a task. After the

scheduler, the activity diagram should enter the delay function and loop back.

<ul>
<li>Touch screen

Hint: There should be a use case diagram, sequence diagram and front panel display for EACH SCREEN

o Use case diagram for the touch screen display. o Sequence diagram for the touch screen display. o Front panel design for the touch screen display.
</li>
<li>State diagrams:

o Each alarm (Hint: Each alarm value is a state).

o Contactors

o Touch screen display (Hint: Each display screen is a state).</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 22">
<div class="layoutArea">
<div class="column">
• Pseudocode for all tasks per the functions listed in Section 7.0 Software Architecture…. pseudocode makes excellent comments in your code!

o Place pseudocode in the appendix and reference it in the Software Implementation section.. “Pseudocode for each task is located in the Appendix”. Points for pseudocode will be assigned in the Software Implementation section of your report.

Include this in the Questions section:

<ul>
<li>Execution time of each task
o Hint: Execution time can be found by toggling an output port and reading that signal on an oscilloscope OR by using the millis() function.
</li>
<li>What delay is required for a 1Hz cycle time?</li>
<li>List of all inputs and outputs
NOTE: In a formal report, your numbers, raw data, pseudocode, etc. should go into an Appendix. The body of the report is for the discussion, don’t clutter it up with a bunch of other stuff. You can always refer to the information in the Appendices, as you need to.

If any of the above requirements is not clear, or you have any concerns or questions about what you’re required to do, please do not hesitate to ask.

What to do with your CODE???:

<ul>
<li>All code must follow the embedded coding standard.</li>
<li>Code must be commented, explaining intended functionality.</li>
<li>Zip all your code files and submit alongside the report.</li>
<li>Explain code file names in your Appendix.</li>
<li>9.0 APPENDIX</li>
</ul>
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 23">
<div class="layoutArea">
<div class="column">
9.1 Implementing the TCB

9.1.1 Tasks and Task Control Blocks (TCBs)

The BMS is comprised of a number of tasks. The function(s) and data for each task are located in a TCB (Task Control Block) structure – implemented as a C struct. The TCB struct contains all data required to both call the task function and pass data to the task function. Each task has its own TCB.

Each TCB has four members as shown in the C typedef declaration from Figure 4:

<ol>
<li>Pointer to a function taking a void* argument and returning a void.</li>
<li>Pointer to void used to reference the data for the task.

See the next Section 9.1.2 “Data Structures for Task Control Blocks (TCBs)” for a definition of this pointer.</li>
<li>Pointers to the next and previous TCB in a linked list data structure, “next” and “prev”. These pointers are not used for the Round Robin Scheduler and shall be initialized to NULL.</li>
</ol>
Such a structure allows various tasks to be handled using function pointers. The following gives a C typedef declaration for such a TCB:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>struct MyStruct
</pre>
{

<pre>};
typedef struct MyStruct TCB;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>void (*myTask)(void*);
void* taskDataPtr;
struct MyStruct* next;
struct MyStruct* prev;
</pre>
</div>
<div class="column">
<pre>// Pointer to function “myTask()”
// Pointer to data structure “taskData”
// Linked list pointer “next”
// Linked list pointer “prev”
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 4 – C Struct Typedef for the Task Control Block (TCB) with Linked List

NOTE: Within the C language, using “void” as a datatype allows one to type cast to different datatypes at compile-time or runtime. In our case, this type casting would apply to both the task’s function and data structure, “myTask” and “taskDataPtr” respectively from the example above. In this way, the TCB typedef is generic to all functions in our system!

</div>
</div>
</div>
<div class="page" title="Page 24">
<div class="layoutArea">
<div class="column">
Implementation Notes:

<ol>
<li>All function declarations (one function per task) shall accept a pointer to void with a
return of void.
</li>
<li>The pointer in the task argument (function argument for “myTask()” function in
Figure 4) must be re-cast as a pointer to that task’s data structure type before it may be

dereferenced… see the next section on constructing each task’s data structure.
</li>
<li>Each task shall have its own TCB!</li>
</ol>
9.1.2 Data Structures for Task Control Blocks (TCBs)

The TCB data structure consists of pointers to global variable data required/modified by the task (the function “myTask” in this example). This data structure is represented by TCB member “taskDataPtr” as seen in Figure 4.

A representative example of declaring and initializing a task’s data structure is given in Figure 5, where the global variable “fooData” would be an integer required by the “fooTask” TCB’s function.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>/**  Data Structure for the “fooTask” TCB  **/
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>int fooVariable;
typedef struct fooDataStruct
</pre>
<pre>{   int* fooVariablePtr;
} fooTaskData;
</pre>
<pre>fooTaskData fooData;
fooData.fooVariablePtr = &amp;fooVariable;
</pre>
</div>
<div class="column">
<pre>// Create “fooVariable” global variable
</pre>
<pre>// Create data structure typedef
//   “fooTaskData” of type “fooDataStruct”
</pre>
<pre>// Create data structure “fooData” to be
//   used in TCB
// Initialize fooData’s variable(s)
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 5 – Task Data Structure for the “fooTask” TCB: C Data Struct Declaration

The data structure’s variables must have global scope. This facilitates inter-task data exchange/communication through shared variables, meaning that tasks needing to communicate/share data with each other will share a variable (i.e. they both use the same variable). Typical programming practices recommend limiting the number of global variables to reduce chances of data corruption (since all functions can access those variables); however, by encapsulating these variables in a data structure, it strictly limits the variables to which functions have access.

</div>
</div>
</div>
<div class="page" title="Page 25">
<div class="layoutArea">
<div class="column">
Based upon the requirements specification, the shared variables are defined to hold measurement data, status, alarm, and flag information. To properly encapsulate and ensure access by the correct tasks, all shared global variables must be passed to tasks using the task data structures!

9.1.3 Task Queue &amp; Scheduling: Initializing Elements of the Task Queue Array (TCB Pointer Array)

Each element of the task queue array shall be a pointer to type TCB, representing one of the tasks identified in Section 7.0 Software Architecture.

Each of the TCB pointers in the task queue array shall be initialized as shown in Figure 6, summarized as such:

<ul>
<li>The TCB’s function pointer shall be initialized to point to the proper task. For example, TCB element zero should have its function pointer initialized to point to the Measure Task.</li>
<li>The data pointer shall be initialized to point to the proper task data structure used by that task. For example, if “MeasureData” is the data structure for the Measure Task, then the data pointer of the TCB should point to “MeasureData”.</li>
<li>The linked list pointers, “next” and “prev” shall be set to NULL until we transition to scheduler using a linked list.</li>
</ul>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>/**  Function Declaration for “fooTask” TCB  **/
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>   void fooTaskFnc(void*);
</pre>
<pre>/**  Initializing “fooTask” TCB  **/
   TCB fooTask;
</pre>
<pre>   fooTask.myTask = &amp;fooTaskFnc;
   fooTask.taskDataPtr = &amp;fooData;
</pre>
</div>
<div class="column">
<pre>// Function declaration for “fooTaskFnc”
</pre>
<pre>// Initialize TCB using typedef defined in
//    Figure 4
// Initialize TCB “myTask” to point to
//    function fooTaskFnc()
</pre>
<pre>//Initialize fooTask’s data struct
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 6 – Full Initialization of a TCB

</div>
</div>
</div>
<div class="page" title="Page 26">
<div class="layoutArea">
<div class="column">
&nbsp;

9.1.4 How to Access Data from your Task’s Data Structure Pointer, “taskDataPtr”, Variable

You may have trouble implementing your task function since the variable passed to your task function is declared as (void*).

<ul>
<li>Question: How does one access data from the task’s data structure pointer when the function declaration uses the (void*) datatype?</li>
<li>Answer: In the code for your task, re-cast the (void*) pointer as a pointer to that task’s data structure type before it is dereferenced.
In the examples posed in Figure 4 and Figure 5, you would need to recast the (void*) function argument for “fooTaskFnc” to type “TaskData” before being able to access the pointer to variable “data”. The previous examples are used to show the re-casting process in Figure 7.
</li>
</ul>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
/** Accessing the TCB’s Data Structure from within “fooTaskFunc” **/

void fooTaskFnc(void* arg) // Function declaration for “fooTaskFnc”

<pre>   {
       /** Re-cast “arg” to fooTaskFnc’s data structure type “fooTypeData” **/
       fooTaskData* localDataPtr = (fooTaskData*) arg;
</pre>
<pre>       /** Access and increment “fooVariable” **/
       *(localDataPtr-&gt;fooVariablePtr) = *(localDataPtr-&gt;fooVariablePtr) + 1;
</pre>
}

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 7 – Coding the TCB Task: Re-Casting to Access the TCB’s Data Structure Pointer (void*) from within the Task Function Code

</div>
</div>
<div class="layoutArea">
<div class="column">
9.2

</div>
<div class="column">
Tips for Building Circuits

<ol>
<li>Measure the resistance of your ground connections to ensure that there is a good ground connection, i.e. no “floating grounds”…. Grounding problems have brought down even the best at NASA.</li>
<li>Do not place your board on a metal (conductive surface).</li>
<li>Mind the current limits of your I/O pins, you don’t want to release smoke demons in
the lab!

<ol>
<li>Max DC current thru a single Arduino I/O pin is 40 mA</li>
<li>Max DC current thru Vcc and GND pin from Arduino boards is 200 mA</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 27">
<div class="layoutArea">
<div class="column">
4. Reduce the chance of electrostatic shock to your circuits and microcontroller boards by handling them carefully. It is recommended to hold your boards at the edges.

5. Just like your code, think through your physical wiring before starting. This will save you time and headache down the road.

6. LEDs must have series resistors to limit current draw thru microcontroller pins.

7. Software configurable pull-up resistors are available in the Arduino microcontroller

(see Figure 8 below): 50k for Mega, 20k for Uno

Figure 8 – ATMega GPIO showing Internal Pull-Up Resistor, Rpu = 50k (Source: Page 84 of ATmega reference manual)

</div>
</div>
<div class="layoutArea">
<div class="column">
BUT if you really do want to electrostatically shock your board, try shuffling your

</div>
</div>
<div class="layoutArea">
<div class="column">
feet over carpet or rubbing a balloon over your hair, then zap your board… This is

</div>
</div>
<div class="layoutArea">
<div class="column">
an excellent way to ruin your microcontroller!

</div>
</div>
</div>
