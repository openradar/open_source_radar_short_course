OSS for Radar Data Processing
=============================

Render this document as pdf by ``rst2pdf course_outline.rst``

**09:00 - 09:30** `Introduction`_::

   Taking seats, booting notebooks, ... brief introduction of tutors. 
   
   Brief presentation of the course concept and outline.
   
   
**09:30 - 10:30** `Collaborative Software Development`_::
   
   The idea of treating users as co-developers is at the heart of OSS.
   
   We will demonstrate the ease of contributing to OSS projects.
   
   
**10:30 - 11:00** Coffee break


**11:00 - 12:00** `Python Quick Start`_::

   Python will be the key to use the presented radar software tools.
   
   Learn how to use Python for writing scripts and for interactive data analysis.  
   

**12:00 - 12:45** `Hands on Py-ART`_::

   Overview of the Py-ART software.

   Using Py-ART for {@Scott and JJ: add topic selection}
   

**12:45 - 14:00** Lunch break


**14:00 - 14:45** `Hands on wradlib`_::

   Overview of the wradlib software.

   Using wradlib for {@Maik and Thomas: add topic selection}
   

**14:45 - 15:30** `Hands on BALTRAD`_::

   Overview of the BALTRAD software.

   Using BALTRAD for {@Daniel: add topic selection}
   

**15:30 - 16:00** Coffee break


**16:00 - 16:45** `Interoperability Demonstration Experiment`_::

   See BALTRAD, Py-ART and wradlib interact.
   

**16:45 - 17:00** `Feedback round`_::

   Feedback of participants on the use of the presented OSS tools.


.. raw:: pdf

      PageBreak

   
Introduction
------------

Time to settle in and say hello. Course tutors will open the course and introduce themselves and their projects, as well as the general structure and concept of the short course. 


Collaborative Software Development
----------------------------------

We will provide a "real-time" demonstration of collaborative development based on a Distributed Version Control System. 

.. admonition:: Comment by maik

   Py-ART and BALTRAD use git+github while wradlib uses hg+bitbucket. We should only present one of those... git+github might be more common. 
   
The Virtual Machine (VM) already comes with hg and git clients so everyone will be set. Course tutors will demonstrate the following steps::

   User 1
   
      Get github account
       
      Create an empty repository on github

      Clone the repository to local machine

      Add some content to local repository

      Commit the changes to local repository

      Push the changes to github

      Add user 2 as a co-developer with write permission

   User 2
   
      Clone repository

      Apply some local changes
 
      Commit the changes locally

      Push the changes to github
	  
   User 1
   
      Pull the changes

      ...
   

   .. admonition:: Comment by maik

      Ok, we should not overreach; however, we should at least address resolving of conflicts and demonstration of the Fork & Pull concept. 

Then course participants can create their own account and a github or bitbucket repository which they will use to host the code they wrote during the course.


Python Quick Start
------------------

.. admonition:: Comment by maik

   @JJ: Didn't you give a quick tutorial at AMS which we could use as a basis?
   
   Otherwise, we should use http://scipy-lectures.github.io/ as a basis to select from.

The Python quick start should cover e.g.::

   - Installing Python, Python distributions / scientific stacks, most important dependencies
   
   - Starting Python from the shell and "hello world"
   
   - Executing a Python script
   
   - Interactive programming using the IPython notebook
   
   - General guidelines on programming style and syntax in Python
   
   - Control flow
   
   - Array operations in Numpy

   - Plotting with matplotlib


Hands on Py-ART
---------------

@Scott and JJ: Please fill in your content.


Hands on wradlib
----------------

Overview::

   - Brief history and background

   - Package structure and modules

   - How to install and use?

   - wradlib's "flat data model"  

   - How to contribute?

Example::

   - Read polar DX data from German Weather Service
   
   - Clutter detection and removal
   
   - Georeferencing and plotting a PPI
   
   - ...


Hands on BALTRAD
----------------

@Daniel: Please will in your content.


Interoperability Demonstration Experiment
-----------------------------------------

Demonstrate pairwise interaction between the presented OSS tools::

   Py-ART and BALTRAD talk to each other.
   
   BALTRAD and wradlib talk to each other.


Feedback round
--------------

We will discuss, together with the participants, the perspectives for using OSS software in different institutional environments. Participants are invited to feedback on their impression of the presented OSS tools and whether these tools are an option for their future activities.