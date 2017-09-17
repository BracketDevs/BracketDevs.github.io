---
layout: page
title: Projects
permalink: /projects/
---

<p class="message">
This is an "under construction" message, don't judge me
</p>

## Some cool things I've worked on over the years
{:.no_toc}

* TOC
{:toc}

### 2016 - Financial Reporting System

Designed system for FinTech startup, to digitize & automate the lengthy process of using various business data to create customer reports

  * Mapping details of Finance domain to the world of computing, worked closely with business-side.  Set of tools
  * Tech: Python, Pandas, Django, PostgreSQL, PDI/Kettle

### 2015 - Framework for Hardware-In-The-Loop Simulation of ECUs

  * For: Audi and Technical University of Munich (TUM)
  * What:
  * What I learned:
  * Tech: C++, VIRES Virtual Test Drive (VTD), EB-Assist Automotive Data and Time-Triggered Framework (ADTF), Altera Cyclone or Atratix FPGA

<img style="max-width: 80%; height: auto; position: relative; display: block; margin: 0 auto; top: 0px;" src="{{ site.baseurl }}assets/projects/4_framework.svg" alt="Framework">

<img style="max-width: 80%; height: auto; position: relative; border: 1px solid black; border-radius: 1%; display: block; margin: 0 auto; top: 0px;" src="{{ site.baseurl }}assets/projects/4_adtf_run.png" alt="System running">


Design and Implementation of a Framework for Hardware-In-The-Loop Simulation of Electronic Control Units

A framework for hardware-in-the-loop simulation of Electronic Control Units (ECU) is
developed and applied within a virtual automotive safety scenario wherein a Driver Assis-
tance System (DAS) helps maintain vehicle position within the lane. A high-performance
C++/OpenCL image processing algorithm for lane detection and tracking runs on Altera
Cyclone V FPGA hardware utilizing its parallel processing capabilities; this represents a
Lane Departure Warning (LDW) FPGA-based ECU. VIRES Virtual Test Drive (VTD) pro-
vides a graphical virtual environment, simulating a vehicle navigating a city. Synthetic im-
ages representing a driver’s view of the road are streamed to the FPGA; lane detection re-
sults then used by a driving algorithm to steer the VTD simulation vehicle in real-time. The
framework also comprises EB-Assist Automotive Data and Time-Triggered Framework,
providing a ﬂexible and modular development, communication and testing environment.
The set-up provides for a closed-loop hardware-in-the-loop simulation environment for
development and validation of the Lane Departure Warning ECU. Results showed frame-
work performance was sufﬁcient for use in development and validation of vision-based
DAS, however use of larger images imposes more processing requirements on the Altera
Cyclone FPGA than it can handle in a real-time HIL setting. Thus the viability of low-cost
FPGAs for vision-based DAS ECUs remains limited.

6.1.  Summary
A framework for HIL simulation was developed and used to test a high-performance lane
detection and tracking algorithm running on an Altera Cyclone V SoC FPGA. Portions of
the algorithm ran on the FPGA itself while others ran on embedded ARM-based processor.
Results showed that while the algorithm itself and the framework are capable of running
in-real time with sufﬁcient processing speeds, the FPGA hardware struggled with process-
ing larger images.  The lane detection itself was robust and capable of handling brighter
and darker segments of our test drive scenario.  VTD and ADTF operated smoothly and
their ﬂexibility allowed us to develop and test scenarios and conditions without any is-
sues. Overall, the framework was found to be suitable for development and validation of
Driver Assistance Systems, including image processing applications.

6.2.  Future work
In the future, testing of the overall performance using more powerful FPGAs could be
done in order to better assess the viability for their use with DAS ECUs involving image
processing. Implementing portions of the algorithm in a lower level Hardware Description
Language should also result in performance gains.  When it comes to the HIL Simulator
portion of the framework, improvements could be made to the steering algorithm which
makes use of lane detection results to maintain vehicle position within the lanes


Possible Solution over traditiona CPU-based ECUs,: Heterogeneous, High-Performance,
  Energy Efficient Hardware (GPUs and FPGAs) which are more energy efficient, and result in less cabling and lower vehicle weight.

  •  OpenCL (Open Computing Language)
– First industry standard that supports programming
heterogeneous high performance devices like GPUs,
FPGAs, DSPs and Multi-Core CPUs.
– ‘C’ like computing language – convenient for s/w
developers
– Used in the current work to run lane detection and lane
tracking algorithm on GPUs and an FPGA.

Port the C/C++ code to Open Computing Language
 (OpenCL) that will enable us to test LDS algorithm
 developed in (1), on high-performance, energy
 efficient, heterogeneous hardware

 FLOPS/watt  Performance delivered per energy
 consumed.
 • FPGAs can reach 6 times the energy efficiency of CPUs  
 • GPUs can reach 3 times that of CPUs  


  Hardware used in the current work:
•    GPU: NVIDIA GeForce GTX 660 Ti
•    GPU: NVIDIA GeForce GTX 285
•    FPGA: Altera Stratix-V

### 2014 - Mobile Apps
#### BMWSocial - Android
  * Client:  BMW, TUM
  * Designed app for BMW, with team at Technical University of Munich (TUM)
  * Tech: Android, apis etc..

#### Unicase - iPad UML Modelling & Meeting app

### Web Apps

### 2008-2011 Assistive Technologies, TechBridgeWorld Projects

#### Braille Writing Tutor
  *
  * Worked on stand-alone and initial smart-phone version
#### MADA

### Robotic Receptionist - Hala
  * Worked on codebase

### Fractals

### CMU

### CMU


#### Desarrollo de aplicaciones
Tengo experiencia desarrollando aplicaciones basadas los siguientes lenguajes.

  * C#
  * Java
  * Python
  * Ruby

  {% highlight js %}
  // Example JS code hightlight

  // Create a function that takes two arguments and returns the sum of those arguments
  var adder = new Function("a", "b", "return a + b");
  {% endhighlight %}

  <div class="message">
    Howdy! This is an example blog post that shows several types of HTML content supported in this theme.
  </div>

  <table>
    <thead>
      <tr>
        <th>Name</th>
        <th>Upvotes</th>
        <th>Downvotes</th>
      </tr>
    </thead>
    <tfoot>
      <tr>
        <td>Totals</td>
        <td>21</td>
        <td>23</td>
      </tr>
    </tfoot>
    <tbody>
      <tr>
        <td>Alice</td>
        <td>10</td>
        <td>11</td>
      </tr>
      <tr>
        <td>Bob</td>
        <td>4</td>
        <td>3</td>
      </tr>
      <tr>
        <td>Charlie</td>
        <td>7</td>
        <td>9</td>
      </tr>
    </tbody>
  </table>
