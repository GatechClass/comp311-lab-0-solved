# comp311-lab-0-solved
**TO GET THIS SOLUTION VISIT:** [Comp311 Lab 0 Solved](https://mantutor.com/product/comp311-lab-0-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115122&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp311 Lab 0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
The goal of this lab is to get comfortable with the basic conventions of circuit diagrams such as: power, ground, wires, mechanical switch, and light emitting diode (LED). At the end, you should be comfortable with: – Working with Github Desktop, – designing and testing simple circuits using the Digital software application, and – submitting your solution to Gradescope.

1. Github Desktop

Throughout this semester, you will be responsible for managing (cloning &amp; committing) to your Github repositories so they can be linked to Gradescope for assignment submission and grading. Instead of using git commands in a terminal, we strongly recommend you to use GitHub Desktop.

The links below provide step-by-step intructions along with visual aids about how to use Github Deskop: * Install GitHub Desktop. * Authenticate to GitHub. * Clone a repository from GitHub to GitHub Desktop. * Commit your changes to the repository. * Push your changes to the repository.

2. Digital: Circuit design and simulation software

Follow the instructions on the Digital GitHub page for downloading and running the software program (no installation required). In short, you simply download the .zip file, unzip it, and run the software. Note: A Java Runtime Environment (at least JRE 8) is required to run Digital.

To start Digital on Windows simply double click the provided Digital.exe executable file. To start Digital on Mac and Linux open a terminal and then execute the provided Digital.sh shell script from the command-line.

Within Digital, you can access a useful help document by clicking Help &gt; Documentation. We recommend reading: – Section 1: How to navigate through the program and create simple circuits. – Secion 3.2: LED with two connections. – Sections 6.1 and 6.2: Ground and voltage supply or power. – Section 13.1: Mechanical on/off switch.

3. Circuit Design

Using Digital, we’ll wire up a very simple circuit that uses power, ground, one or more switches, and one LED. In general, when the switch is closed the LED will turn on (color will be red) and when the switch is open the LED will be turned off (color will be black). Adding an LEDs a great way to visually test the output of your circuit.

First, clone the Lab 0 repository using the clone Github Desktop instructions provided above.

3.a First circuit

TODO: After cloning the Github repository for Lab 0, start Digital and open the file Lab00a.dig. You do not need to edit this circuit in any way, it serves simply as an example of what a completed circuit in Digital looks like. Use this file to familiarize yourself with the Digital software. For example, pressing the play button in the top right corner of the Digital software will allow you to simulate the circuit. Try flipping the switch and seeing how it affects the output of the LED. Inspect carefully how the LED is wired, notice which components represent power (logic 1) and which represent ground (logic 0). When you press the play button, certain wires will light up, these wires are the ones that are connected to power. Understanding and analyzing how this circuit works will be crucial to being able to complete the second part of this lab.

3.b Slight enhancement to first circuit

This part is just a slight enhancement of the circuit in Section 3. We’ll modify our circuit to act as a kind of â€œmechanical AND gate,â€ where the LED will only turn on if two switches are both in the closed position. This is simply wiring two switches in series, not using any AND gates (or indeed any logic gates at all).

The one complication in this part of the lab is that we want to wire the two switches in such a way that the LED will only turn on when both switches are in the closed position. This will require some small modification to the switch wiring: one switch will need to select between ground and the output of the previous switch.

There is one important step you must take while constructing Digital circuits for this class. Every time you place a switch, you must right-click (control + click for Mac) the switch. This will open an options menu for the switch, where among other things, you can label the component. You will notice that all components are already labeled for you. For both switches that are placed in this circuit for you, go to the “advanced” options menu, and make sure you check the box labeled “Switch behaves like an input”. This will allow the autograder to work. If you don’t do this step, the autograder will not work! Remember, you must enable this option for every switch in your circuit, and this step must be done in all future Digital labs as well!

TODO: Construct your design in Digital using Lab00b.dig file as a start. You should only need to add wires and delete wires, not add any additional components. Verify that your design works in Digital by using the play button to simulate the circuit. You should only see the LED light up when both switches are in the closed position.

What to submit? After modifying the file Lab00b.dig in order to implement the functionality shown above, you should commit and push your changes to your Lab 0 Github Repo.

4. Submit your assignment

Assignment submissions will be made through GradeScope.

1. Submit modifications using the commit Github Desktop instructions provided above.

2. Update remote (origin) repository using the push Github Desktop instructions provided above.

3. Go to the COMP 311 course in GradeScope and click on the assignment called Lab 00.

4. Click on the option to Submit Assignment and choose GitHub as the submission method. You will be prompted to sign in to your GitHub account to grant access to GradeScope. When this occurs, make sure to grant access to the Comp311-SP22 organization.

5. You should see a list of your public repositories. Select the one named lab-00-yourname and submit it.

6. Your assignment should be autograded within a few seconds and you will receive feedback.
