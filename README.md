# Introduction to Computation for the Physical Sciences

### Hello!  

The files in this repo comprise syllabus, tutorial notebooks, and data files from **PHY 220** *Introduction to Computation for the Physical Sciences* at [Washington & Jefferson College](https://www.washjeff.edu/).
These materials build on a computational physics laboratory course that was offered annually from 2014 to 2021.
PHY 220 was first offered as a stand-alone course in the Spring 2022 semester, and will be taught annually thereafter.
Files in this repository should be updated at least as frequently as the course is taught until they achieve educational and literary perfection.

Here is the course description for PHY 220, the copy that "attracts" students to the course:

> Computing has become an integral part of knowledge generation in many areas of the natural and behavioral sciences. Computing drives the cutting-edge research in diverse fields such as protein folding, astrophysics and cosmology, dynamic properties of molecules, and artificial intelligence. This course is an introduction to fundamental computing concepts and programming skills relevant to the quantitative sciences. Students will investigate techniques such as iteration, recursion, functions, data I/O, data visualization, curve fitting, and simulation in an interactive laboratory setting. PHY 220 is intended to prepare students to leverage computational techniques in courses, research, and careers.

### Audience

PHY 220 is a 2-credit (*i.e.*, half) course required of all physics and engineering students in their first or second years of study.  The course is also intended for students majoring in chemistry, biology, mathematics, economics, or any other field where intermediate quantitative literacy and basic programming skills related to data science could be an asset.  

For a significant fraction of our students PHY 220 is a first experience using a computer outside of the MS Office suite.  Other students who take PHY 220, however, have some (and in some cases quite extensive) prior programming experience.  I think that it's possible to present an impactful experience for both of these groups.

For the n00bs, material is presented in a "let's not get bogged down in the details -- let's focus on what computers can *do*".  It's pretty easy to create a high-impact course for these students that increases their confidence and leaves them with many transferrable skills.

For the students who are seasoned programmers, I've found that few of them have used computers to investigate quantitative problems.  Many of these students have experience coding apps or database access/management.  While things like control structures might be old hat to these students, concepts like numerical integration and fitting are new (and often exciting).  

In short, it's not too difficult to make a class that is meaningful for a diverse group like this.

### Philosophy and goals

The course takes a "software carpentry" approach, covering several types of techniques in a way that builds "capability" rather than "proficiency" or "expertise".  For example, after taking the course, a student might not be able to sit down and independently bang out an Euler algorithm for a second-order partial differential equation, but she should be able to do some light Googling, read other people's code, and cobble together an Euler implementation that works for her particular application.  This early skills approach is part of a larger effort in the department to prepare students for meaningful research and internships as early as possible in the college career.

The student learning objectives are given in the syllabus, but they are worth reproducing here:
use basic control structures (loops and conditionals)
- write and use functions
- read, plot, and write data
- fit functions/models to data and histograms
- investigate distributions and correlations of data
- demonstrate basic skills of large-scale data analysis and visualization using common
file types
- perform numerical integration and numerical solution to differential equations
- parse, analyze, and generate text files
- implement basic Monte Carlo techniques
- perform basic operations using `circuitpython` on a compatible microcontroller

These skills are reinforced and expanded in courses in the third and fourth year of study in the Physics Major at W&J.  Many students leverage these skills in research experiences at W&J and beyond.

### Course structure

Ideally this course will meet weekly or twice weekly for a combined 180 minutes.  Each week of class centers on a new skill or set of skills introduced in a single interactive python notebook.  Homework problems are provided at the end of each notebook.

### Topics/curriculum

- Week 1: Basics, computer as a \\$2k calculator
- Week 2: Control structures
- Week 3: Data types, containers, lists
- Week 4: File I/O
- Week 5: Data visualization with `matplotlib`
- Week 6: Text as data, forming and testing hypotheses
- Week 7: Numerical simulations of ordinary differential equations

### Getting started

These materials use `python`, but the skills and structure of the course could easily ported to other prominent languages provided they have some workable graphing capabilities.  

Installing the [Anaconda python](https://www.anaconda.com/) distribution maintained by Contiuum is the easiest way to get all of the necessary packages.  The code contained in this repo will work with any python version 3.6 or higher.

To get started, open Jupyter Lab from Anaconda Launcher, and use the file browser in the left pane to navigate to and open any of the `.ipynb` files in this repository.


### License

These materials are provided under the MIT license (see LICENSE.txt for more info).
