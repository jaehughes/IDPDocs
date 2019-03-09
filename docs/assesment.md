# IDP: Assessment

###First Presentation

**First Presentation (presented as a group)**

The first presentation should be no longer than 10 minutes, to leave a further 5-10 minutes for discussions and questions.  This should be thought of as a the team acting as a consultancy pitching your overall system to your clients. Each team member is expected to attend the presentation.  This should include a maximum of 10 slides which should cover the following:

* Team Name and Management Structure
* Approach for solving the problem
* Robot Concept and diagram.  *This could be a prototype, hand-drawn diagrams, CAD models or any format which conveys the approach and concept*
* Overall System Level Diagram.  *Detailing how the electronics, hardware and software interacts*
* Electronics/Sensing.  *This could include circuit diagrams/block diagrams as to the approach*
* Exploration and navigation algorithms
* Integration between hardware electronics and software
* What is the most risky/challenging aspect of the project?
* Gantt Chart (resource/time allocation)

Any cardboard models/diagrams/prototypes should be brought a long for discussion.  A printed copy of the *presentation* should be brought to the presentation.

You will need, as a team, to think about how the individual contributions ﬁt together and the overall timing, so as to ensure a professional impression. Where possible a projector/screen will be available.  Meeting rooms should have a HDMI connector, however teams should check connection between laptops/screen prior to their presentation.

**The mark scheme for the First Presentation can be found [here](First Presentation Mark Scheme.pdf).**

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
*	**Software.** Exploration and navigation algorithms.  Interface to electronics, discussion of choice of algorithms, any failure detection/recovery which will be implemented.
*	Integration between hardware electronics and software
*	What is the most risky/challenging aspect of the project?
*	Gantt Chart (resource/time allocation)

The first report should be submitted online on Moodle, only one must be submitted per team.  

**The mark scheme for the First Report can be found [here](First Report Mark Scheme.pdf).**

###Progress Meetings

There will be two progress meetings which will be held between each team and an academic and demonstrator.  These are designed to allow the academic and demonstrator to provide advice and feedback on the teams progress, team and project management and technical developments.   These meetings will last approximately 20-30 minutes.  These are not formal presentations, but teams should be prepared to give and show an update on the follow areas, which may be best presented as slides, or print outs or diagrams:

* Updated Gantt chart, and progress the last week
* Electronics - details of the approach and up-to date circuit diagrams
* CAD assembly showing all major parts
* Software flow chart and representation of the overall strategy
* Remaining challenges which need to overcome and current plans for achieving this
* Plans for the next week

The more information you can provide, the more we can support you and provide feedback and advice.

We expect teams to keep updated circuit diagrams, layout diagrams, CAD diagrams and software flow-charts/strategy diagrams.

###Final Presentation

The final presentation (maximum of 8 slides) should focus on the following:

* A review of the overall design strategy (inc. software, electronics and hardware and overall strategy).  What is clever, innovative about your approach, try and 'sell' this to your assessors.  
* How was the approach physically implemented, what problems encountered during implementation and any major changes which were implemented to overcome these problems.
* Review of the program management of the project, and differences between planned timescales and actual timescales and what were the key lessons learnt - what would you do differently if you do it again
* Brief statement of likely performance in the competition.


###Competitions

 **The Competitions**

 The competitions will take place on the Monday morning and the Wednesday afternoon.  Teams should be on their allotted table and ready for their time slot - we recommend being on the table at least 10  minutes before their timed slot; the schedule is tight, there is very little room for delays.

There will be at least two official markers.  Before the competition starts you must give a very brief (max 1 minute) introduction to state how you expect your robot to work.  You should also make sure you have told the markers where the LEDs or other identifiers will be.


###Final Documentation: CAD Assembly, Circuit Diagrams & Code

Documentation must be produced and used throughout IDP.  The final version must be handed in at the end of the project and will be used to assess the robot quality.  The documentation should be printed out and hard copies handed in by the monday following the competition (by 4pm).  

**These should be professional standard, well laid out diagrams. Take some care when making these to make them of a high quality. Consider how they are presented.  They should be of a high enough quality to give to another engineering to enable them to make your robot systems.**


**Software/Overall Documentation**

For software documentation we want to see an overall system diagram, to show how the entire system will integrate together.    Additionally, we require details of the strategy/algorithms that will be used - this could be pictorial/flow-chart or another method of representing the overall approach and strategy.  

For the software documentation we require:

* **System Diagram (Max 1 A4 page)**  This should include the physical connections between the Arduino (including pin numbers) and the sensors, any serial connections between the Arduino and PC and information as to how mines detection will be shown (e.g. LEDs) and how the position will be identified.

* **Code Structure & Algorithms (Max 1 A4 Page).** The overall strategy and algorithms which are used should be detailed, this could be showed in a diagram.  This should such sufficient to convey your approach (i.e. around a maximum of 10 boxes and units, UML is not required). You should represent how you have structured the code. This could be lists of prototypes of functions, or diagrams showing how different sub-modules interact.  

* **Code which is appropriately commented.**  This can either be printed out and submitted, or, a link can be given (please print the URL to the code clearly on the code structure/algorithms diagram page.)

**Electrical Documentation**

* **Circuit diagrams.**  Produce circuit diagrams to show all the electronics and the interface between the sensors and the Arduino.  You should think about including indicator LEDs to show the output from the electronics so they can be tested without software, using variable resistors to set adjustable levels, include LEDs to indicate what has been detected and consider if there are any analogue inputs which would be better suited as a digital input.  
    + Pin numbers
    + IC Part numbers (if you are use multiple ICs of the same type these should be labelled appropriately)
    + Power lines (labelled)
    + All parts (including ultrasound/compass should be included)
    + Consider what is connected as a digital/analog input.  If it is a digital input ensure it is a digital signal
* **Layout diagrams.**  The layout and connections between any sensors and the Arduino must be shown.  Stating with the layout of veroboard and the prototyping board either by hand, powerpoint or another drawing program the layout of where components will be placed should be shown.  In particular you should think through: how to connect sensors/electronics fixed on the robot to the main control electronics to enable them to be separated, where connectors should be mounted (consider putting at the edge of the board such that they can be easily accessed).
    * All connectors should be shown
    * Power rails should be labelled
    * Location of headers should be shown
    * Location of all parts
    * Location where tracks should be cut
    * Location of any jumper wires required

These can be produced by hand or using CAD software; what matters most is that they are clear and correct.   Tools which maybe useful include circuitlab/circuit.io (for circuit diagrams), veroboard layout/fritzing for layout diagrams.  

*Examples and hints and tips on producing materials of a sufficient standard can be found [here](ElectricalDA.pdf)*

**Mechanical Documentation**

The CAD diagrams submitted should be sufficient to allow another engineer to assemble your robot, and to use the files to laser cut/3D print parts as required.  We want to know what material you have to chosen to use and why as part of the submitted designs.

* **Overall CAD Assembly.** Showing the assembled CAD model.  This should be as near as possible to actual design.  If any changes are made to the mechanical parts by 'hand crafting' attempts should be made to make the CAD model reflect this, or notes should be added to the CAD model.  The assembly should include any sensors mounts, electronics mounts and therefore must be developed in conjunction with the other sub-teams.  Make sure you have a drawing with:
    * Overall assembly showing the entire structure (including any mounts for sensors)
    * 3D view and appropriate plan/side views
    * Include balloon labels which identify each part

* **2D Drawing of parts/subsystems.**  2D drawings of each of the parts should be developed. These should be sufficiently detailed such that if given to another person, they could build and assemble the system. These will also be useful for yourselves when constructing the robot.  The parts should be laid out appropriately on the drawing and should include: Major dimensions (of folded and unfolded structures where applicable), indications if any threads should be applied to holes.  Make sure you have a drawing with:
    * Each part with dimensions
    * Where applicable folded and unfolded views and dimension
    * If you are tapping holes identify this
    * If you want to include multiple parts per drawing, make sure they are appropriate to mix - don't mix 3D printing/laser cutting drawings

Some examples of good/bad drawings can be found [here](http://www3.eng.cam.ac.uk/DesignOffice/idp/resources/current/da_mech1.pdf).


###Final Report (Individual)

The final report should be a maximum of 2-pages and should include the following:

* Summary of the system developed, the major design decisions and the strategy used.  
* Summary of your contributions to the project - short details of what aspects you worked on, and review of how this performed.
* Major decisions made during the project should be reviewed and comment made on their
correctness.
* Team management aspects of the project – not a narrative describing how you did the work
on a day to day basis, but the management structure used and a discussion of how well this worked.
* Discussion of how the robot performed in the competition, what went well what didn't and how you meet the task specification.  What would you differently next time?
* Short discussion on what changes would be needed to produce the robots on mass, and how production would scale.

The final report must be submitted as a pdf, must not exceed two pages and should be submitted on Moodle.  Each student should submit their own report.
