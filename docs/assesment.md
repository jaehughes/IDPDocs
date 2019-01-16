# IDP: Assessment

###First Presentation

**First Presentation (presented as a group)**

The first presentation should be no longer than 10 minutes, to leave a further 5-10 minutes for discussions and questions.  This should be thought of as a the team acting as a consultancy pitching your overall system to your clients. Each team member is expected to attend the presentation.  This should include a maximum of 10 slides which should cover the following:

* Team Name and Management Structure
* Approach for solving the problem
* Robot Concept and diagram.  *This could be hand-drawn diagrams, CAD models or any format which conveys the approach and concept*
* Overall System Level Diagram.  *Detailing how the electronics, hardware and software interacts*
* Electronics/Sensing.  *This could include circuit diagrams/block diagrams as to the approach*
* Exploration and navigation algorithms
* Integration between hardware electronics and software
* What is the most risky/challenging aspect of the project?
* Gantt Chart (resource/time allocation)

Any cardboard models/diagrams this should be brought a long for discussion.  A printed copy of the *presentation* should be brought to the presentation, and the presentation should also be submitted on Moodle.

You will need, as a team, to think about how the individual contributions ﬁt together and the overall timing, so as to ensure a professional impression. Where possible a projector/screen will be available.  The meeting rooms have a HDMI connector, teams should check connection between laptops/screen prior to their presentation.

**A draft of the mark scheme for the First Presentation can be found [here](First Presentation Mark Scheme.pdf).**

###First Report

**First Report (presented as a group)**

The initial report should provide a more detailed reflection of the planned system, and where possible reflect the feedback given the initial presentation. It should be a maximum of approximately 6 pages of text, with teams free to include diagrams/CAD diagrams/sketches which go beyond this 6 page text limit.  The report focus on the same content as given in the First Presentation, with more in depth information.  The report should contain:

*	A coversheet specifying the team identiﬁer, team name and robot name together with the name, lab group and College of each team member
*	Approach for solving the problem
*	Sketches of the concepts you have considered (which may be photocopied/scanned from your lab book).  Evaluation charts of these concepts together with a brief discussion of the advantages and disadvantages of each
*	Approach for solving the problem
*	**Robot Concept and diagram.** This could be hand-drawn diagrams, CAD models or any format which conveys the approach and concept
*	Overall System Level Diagram. Detailing how the electronics, hardware and software interacts
*	**Electronics/Sensing.** This should include a list of sensors/circuits required, any circuit diagrams/block diagrams which may have already been developed.  Discussion as to if/why some processing will be performed in electronics opposed to software (e.g. obtaining digital outputs from analogue signals)
*	**Software.** Exploration and navigation algorithms.  Interface to electronics, discussion of choice of algorithmns, any failure detection/recovery which will be implemented.
*	Integration between hardware electronics and software
*	What is the most risky/challenging aspect of the project?
*	Gantt Chart (resource/time allocation)

The first report should be submitted online on Moodle, only one must be submitted per team.  

**A draft of the mark scheme for the First Report can be found [here](First Report Mark Scheme.pdf).**
<!---
###Design Acceptance

Design acceptance is documentation that must be produced by teams, and is marked as pass/fail.  Teams are free to test and develop hardware/software before they gain design acceptance, however, where possible no fully permanent manufacturing should be made before design acceptance.  We encourage teams to get design acceptance as early as possible.

**These should be professional standard, well laid out diagrams. Take some care when making these to make them of a high quality. Consider how they are presented.  They should be of a high enough quality to give to another engineering to enable them to make your robot systems.**

*We ask for the final design acceptance to be printed out such that you have it to hand when working on your robots, but it may be useful to first ask for feedback on an electronic copy between printing all documents.*

**Software/Overall Design Acceptance**

For software design acceptance we want to see an overall system diagram, to show how the entire system will integrate together.  **This will require input from all sub-teams.**  Additionally, we require details of the strategy/algorithms that will be used - this could be pictorial/flow-chart or another method of representing the overall approach and strategy.  The DA document should be sufficiently detailed for a programmer to be able to finish the project for you (and perhaps not needing to consult the electrical subteam) - i.e. pins/ports defined, LEDs details specified, strategy described. Specifically we require:

* **System Diagram.**  This should include the physical connections between the Arduino (including pin numbers) and the sensors, any serial connections between the Arduino and PC and information as to how mines detection will be shown (e.g. LEDs) and how the position will be identified.  A drawing or photograph of a model of the robot should be included which has labels to show the key parts and how sensors/actuators are mounted. Make sure you have:
    * Pin numbers of connections between Arduino and external electronics
    * Details of information passing over serial
    * Details of any processing performed on the PC
    * Location of where the sensors are on the robot

* **Code Structure & Algorithms.** The overall strategy and algorithms which are used should be detailed, this could be showed in a diagram.  This should such sufficient to convey your approach (i.e. around a maximum of 10 boxes and units, UML is not required). Additionally information about code structure should be given which includes: list of function prototypes, which source files the different functions will go into (showing code organisation/modularisation), where relevant any details of object types created.  Include consideration of disaster recovery approaches.  Make sure you have:
    * List of different source files (including those running on a PC or on the microcontroller)
    * List of key function prototypes within the different source files (details of any code organisation/modularisation)
    * Details of any object types created (where relevant)

In addition to this document the marker will review have all the code you have developed so far. It will be useful to have a sample of your current code (e.g. that developed in the initial testing stage) that could be looked over by a marker.  

**Electrical Design Acceptance**

The following should be accepted before you solder onto the prototyping board.  

* **Circuit diagrams.**  Produce circuits to show all the electronics and the interface between the sensors and the Arduino.  You should think about including indicator LEDs to show the output from the electronics so they can be tested without software, using variable resistors to set adjustable levels, include LEDs to indicate what has been detected and consider if there are any analogue inputs which would be better suited as a digital input.  
    + Pin numbers
    + IC Part numbers (if you are use multiple ICs of the same type these should be labelled appropriately)
    + Power lines (labelled)
    + All parts (including ultrasound/compass should be included)
    + Consider what is connected as a digital/analog input.  If it is a digital input ensure it is a digital signal
* **Layout diagrams.**  The layout and connections between any sensors and the Arduino must be shown.  Stating with the layout of veroboard and the prototyping board either by hand, powerpoint or another drawing program the layout of where components will be placed should be shown.  In particular you should think through: how to connect sensors/electronics fixed on the robot to the main control electronics to enable them to be separated, where connectors should be mounted (consider putting at the edge of the board such that they can be easily accessed).
    * All connectors should be shown
    * Power rails should be labelled
    * Location of headers should be shown
    * Location of all Parts
    * Location where tracks should be cut
    * Location of any jumper wires required

These can be produced by hand or using CAD software, what matters is that they are clear and correct.   Software such as LTSpice (which is installed on the department PCs) can be used, equally there are free online circuit drawing systems including circuit-diagram or circuitlab. **Fritzing is another online tool (specifically for Arduinos etc. which allows creation of both circuit and layout diagrams and may be a useful tool.**

*Examples and hints and tips on producing materials for electrical design acceptance can be found [here](ElectricalDA.pdf)*

**Mechanical Design Acceptance**

For mechanical design acceptance, we want to.  These should be sufficient for you to construct your robot, and to use the files to laser cut/3D print parts as required.  We want to know what material you have to chosen to use and why as part of the submitted designs.

* **Overall CAD Assembly.** Showing the assembled CAD model.  This should be as near as possible to actual design.  If any changes are made to the mechanical parts by 'hand crafting' attempts should be made to make the CAD model reflect this, or notes should be added to the CAD model.  The assembly should include any sensors mounts, electronics mounts and therefore must be developed in conjunction with the other sub-teams.  Make sure you have a drawing with:
    * Overall assembly showing the entire structure (including any mounts for sensors)
    * 3D view and appropriate plan/side views
    * Include balloon labels which identify each part

* **2D Drawing of parts/subsystems.**  2D drawings of each of the parts should be developed. These should be sufficiently detailed such that if given to another person, they could build and assemble the system. These will also be useful for yourselves when constructing the robot.  The parts should be laid out appropriately on the drawing and should include: Major dimensions (of folded and unfolded structures where applicable), indications if any threads should be applied to holes.  Make sure you have a drawing with:
    * Each part with dimensions
    * Where applicable folded and unfolded views and dimension
    * If tapping holes identify this
    * If you want to include multiple parts per drawing, make sure they are appropriate to mix - don't mix 3D printing/laser cutting drawings

Some examples of good/bad drawings can be found [here](http://www3.eng.cam.ac.uk/DesignOffice/idp/resources/current/da_mech1.pdf).

###Functional Demonstration

The aim of functional demonstration is to show that integration of the different sub-systems has been achieved and to encourage teams to perform early integration.  They are to demonstrate that the core competencies required for the competition task can be achieved.  This is to help evaluate the system, if, the robot fails to achieve as well as expected in competition.

To get functional demonstration ask a demonstrator to asses your system.  You have a **maximum of 3 attempts** to gain functional demonstration.  Check and test your system before asking for Functional Demonstration.  

**Functional Demonstration #1 (50%):** Moving chassis that can navigate without crashing into walls.  The robot must start in the start box, and then move out of the start box and around for 1 minute without getting stuck of crashing into walls.  The robot should not have periods of not moving which are greater than 5 seconds.

**Functional Demonstration #2 (50%):** Correct identification of the test object.  The robot should start in the start box. A mine can be placed in a area of approximate choosing by the team. The robot should run autonomously and detect the type of mine and display this in a way which can be easily seen by the marker.  


-->
###Final Presentation & Competition

The final presentation and competition will have the following format and order:

* 10 minute presentation (in the morning)
* Competition run (approximately 10 minutes)
* 5-10 minutes Q&A.  Allows for reflections and discussion on the robots performance in the challenge.

The final presentation (maximum of 8 slides) should focus on the following:

* Brief review of the overall design strategy (inc. software, electronics and hardware and overall strategy)
* Problems encountered during implementation and any major changes which were implemented
* Review of the program management of the project, and differences between planned timescales and actual timescales
* Key lessons learnt - what would you do differently if you do it again
* Brief statement of likely performance in the competition.

 A printed copy of the report should be brought to the presentation, and the presentation should also be submitted on Moodle.

 **The Competition**

 The competition will take place in the Wednesday afternoon.  Teams should be on their allotted table and ready for their time slot - we recommend being on the table at least 10  minutes before their timed slot; the schedule is tight, there is very little room for delays.

 The scoring sheet which will be used for the M2 competition can be found [here](Score.pdf).  There will be at least two official markers.  Before the competition starts you must give a very brief (max 1 minute) introduction to state how you expect your robot to work.  You should also make sure you have told the markers how the mines will be identified (i.e. where LEDs, and how the list of mines will be displayed).

After the competition you must do the following:

* After the competition, you will move to the benches behind and will have a 5 minute de-brief and will discuss the robots performance: reasons for success/failure and any key lessons learnt.
* Take your robot to be photographed in the white robot area
* Make sure code is uploaded to github and a link is submitted on Moodle
* Tidy your desk in the EIETL. Please return all unused parts to the parts trays, and return all parts and other parts to your tool box.

###Final Report (Individual)

The final report should be a maximum of 2-pages and should include the following:

* Summary of the system developed, the major design decisions and the strategy used.  
* Summary of your contributions to the project - short details of what aspects you worked on, and review of how this performed.
* Major decisions made during the project should be reviewed and comment made on their
correctness.
* Team management aspects of the project – not a narrative describing how you did the work
on a day to day basis, but the managment structure used and a discussion of how well this worked.
* Discussion of how the robot performed in the competition - what went well what didn't.  What would you differently next time?

The final report should be submitted on Moodle.  Each student should submit their own report.
