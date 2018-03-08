# Horizontal Filtration, Spring 2018
#### Clare O'Connor, Corson Chao, and Christopher Galantino
#### 3/1/2018

## Abstract
Briefly summarize your previous work, goals and objectives, what you have accomplished, and future work. (100 words max)

Horizontal filtration is a completely new innovation for the AguaClara team, arising from a desire to make the 1 L/s plants easier to make and ship by eliminating the Enclosed Stacked Rapid Sand Filter. To create a horizontal filter, aspects of the sedimentation tanks and current filter design will be used, such as the relationship between backwash and operational speed, as well as the design of the plate settlers. Initial experimentation with the settling of sand during upflow is promising for when construction of the filter prototype begins.

## Introduction

The plantita (1 L/s plant) is a difficult apparatus to construct and implement. Finding a way to make fabrication, assembly, and installation simpler, as well as downsize components, will greatly decrease the cost and make the technology more accessible for global communities.

The concept of an easy to implement, versatile water treatment plant correlates nicely with the [OrigamiWaterLab](https://github.com/OrigamiWaterLab) proposed by AguaClara engineer [Ethan Keller](https://github.com/ethan92429). Essentially, ingenious engineering is found in simplicity and resiliency. Fabricating a plant that transitions from flat into 3D is a innovative area of study that may become more possible with increased exploration.

With this idea in mind, one of the most difficult features to construct in an efficient, mass-producible way is the filter. Currently, the plantita’s filter is characterized by a vertical, enclosed stacked rapid sand filter (EStaRS) which is tall and unfriendly to ship in addition to its complicated geometry of 4 inlet manifolds and 3 outlet manifolds.

To combat these difficulties, a horizontal filter design has been proposed. This filter will not be stacked. Instead, it will use horizontal flow for filtration and vertical flow for backwash. The ratio of the horizontal flow area to the vertical flow area will be designed so that the bed will fluidize during backwash. The inlet and outlets will be designed so that sand/water separation doesn’t require slots. Water will exit through a geometry that has a plate settler style design to ensure that sand settles out and isn’t carried into the effluent. Both current filtration techniques and technologies from the plate settle design in the sedimentation tanks are used in the design of the horizontal filter. This technology might then also  be adapted to replace the slotted pipes in the current Stacked Rapid Sand Filters in the full-sized plants.

The goal is that these design innovations will simplify the current design and facilitate scaleup and mass production of AguaClara technologies.

## Methods

Plan:

1) incorporate our dimensional analysis file in some way
2) can't really do much here until we start doing fabrication


To estimate the length of the filter shelves, several experiments were run.
  -Using an angle of 45 degrees (because most efficient use of space)
  1. 1" and .25"
    a. with 1" vertical tube and .25" outlet tube, dry sand was poured into the top of the apparatus, so that it lined up with the bottom edge of the outlet hole.
    b. An additional 500g of sand were poured in increments of 100g, this corresponded with an additional height of about 2 ft. At no point did dry sand enter into the outlet tube
    c. water slowly added into original amount of sand plus and additional ~150g, during this process water carried sand into the first inch of the outlet tube.
    d. pumps checked for proper flow rate to get proper water velocity in the outlet tube as corresponding to the outlet diameter and speed required for **backwash/operation?** .
    e. water pumped through the now, very wet sand. Sand was moved 3 inches up the length of the outlet tube. Preferential flow paths were observed as the apparatus was tilted.
  2. 1" and .75"
    a. originally, the plan had been to use 1" and 1" but fabrication of the experimental apparatus was extraordinarily challenging, so the outlet tube dimension was changed to reflect what was possible to construct.
    b. welded a .75" inched clear PVC tube to a new 1" diameter tube. ...
    c. add dry sand.
    d. fill with water.
    e. pump water though outlet at new relevant speed





Explain the techniques you have used to acquire additional data and insights. Reserve fine detail for the Manual at the end of the report, but use this section to give an overview with enough detail for the reader to understand your Results and Analysis. Describe your apparatus, and have a justification for every decision you made and every parameter you chose in the design of the apparatus. Be especially careful to detail the conditions your experiments were conducted under, as this information is especially important for interpreting your results

Below, some example sections are given. Sectioning the report is meant to keep similar information together.  Continue making sections as necessary, or delete sections if you do not need them. Feel free to add subsubsections to further delineate the information. For example, under the Experimental Apparatus section below, the EStaRS team might consider having sections such as "Filter Design" and "Filter Fabrication".

### Experimental Apparatus
Explain your apparatus setup using enough detail such that future teams can recreate your apparatus. Make sure to explain why you built it this way.
* Design (calculations, constraints)

  $\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
* Schematic (label parts)

  <img src="https://github.com/jillianwhiting/Jillian-Whiting/blob/master/Images/IMG_0009.jpg?raw=true" height=250 width=200>

* Image (from lab; label parts)
* Materials (dimensions, materials)
* Complications in construction
* If already constructed: write a brief summary of important constraints, include any revisions to apparatus, also reference the prior report where construction is described

### Procedure
Discuss your experimental procedure. How did you run your experiment? What were you testing? What were the values of relevant parameters?

## Results and Analysis
Present an observation (results), then explain what happened (analysis).  Each paragraph should focus on one aspect of your results. In that same paragraph, you should interpret that result.
In other words, there should not be two distinct paragraphs, but instead one paragraph containing one result and the interpretation and analysis of this result. Here are some guiding questions for results and analysis:

When describing your results, present your data, using the guidelines below:
* What happened? What did you find?
* Show your experimental data in a professional way.
```python
from aide_design.play import*
x = np.array([1,2,3,4,5])
y = np.array([1,2,3,4,5])
plt.figure('ax',(10,8))
plt.plot(x,y,'*')
plt.savefig('/Users/jillianwhiting/github/Jillian-Whiting/Images/linear')
plt.show()
```
![linear](https://github.com/jillianwhiting/Jillian-Whiting/blob/master/Images/linear.png?raw=true)
Figure 1: Captions are very important for figures. Captions go below figures.

After describing a particular result, within a paragraph, go on to connect your work to fundamental physics/chemistry/statics/fluid mechanics, or whatever field is appropriate. Analyze your results and compare with theoretical expectations; or, if you have not yet done the experiments, describe your expectations based on established knowledge. Include implications of your results. How will your results influence the design of AguaClara plants? If possible provide clear recommendations for design changes that should be adopted. Show your experimental data in a professional way using the following guidelines:
* Why did you get those results/data?
* Did these results line up with expectations?
* What went wrong?
* If the data do not support your hypothesis, is there another hypothesis that describes your new data?

## Conclusions
Explain what you have learned and how that influences your next steps. Why does what you discovered matter to AguaClara?

Make sure that you defend your conclusions with facts and results.

## Future Work
Describe your plan of action for the next several weeks of research. Detail the next steps for this team. How can AguaClara use what you discovered for future projects? Your suggestions for challenges for future teams are most welcome. Should research in this area continue?

Once the acrylic box for the team comes in, construction of the full filter will begin. This will include construction the filter shelves, sloped bottom, EPDM sealed doors, and the siphon to start backwash.

# Manual
The goal of this section is to provide all of the guidance that would be necessary for a future team to pick up your work where you left off. Please try to be thorough and put yourselves in the shoes of a newcomer to the project. Below are some recommended sections, but the manual will likely take a slightly different form for each team.

## Fabrication Details
Include any information related to the fabrication of equipment, experimental apparatuses, or technologies. Include the purpose of each step and the fabrication methods used. Reference appropriate safety precautions.

-for experiment  with sand settling: welded tubes at angles by cutting angles hole

## Special Components
If your subteam uses a particular part that is unique and you could foresee a future subteam needing to order it or learn more about it, please include basic information like the vendor where it was purchased, catalog/item number, and a link to any documentation.

-tank
-EPDM
-leather punch?
-EPDM adhesive

## Experimental Methods
### Set-up
Step 1.
* Put tasks in a sequential order.
* It is okay to have sub-lists.
  - Like this.

### Experiment
Step 1.

### Cleaning Procedure
Step 1.

## Experimental Checklist
Another potential section could include a list of things that you need to check before running an experiment.

## ProCoDA Method File
Use this section to explain your method file. This could be broken up into several components as shown below:

### States
Here, you should describe the function of each state in your method file, both in terms of its overall purpose and also in terms of the details that make it distinct from other states. For example:
\begin{itemize}
\item \underline{OFF} - Resting state of ProCoDA. All sensors, relays, and pumps are turned off.
\end{itemize}

### Set Points
Here, you should list the set points used in your method file and explain their use as well as how each was calculated.

## Python Code

### Variables
$g$: gravity
$\sigma$: dispersion
$a$: amplitude
$h$: water depth
$H$: distance from wave crest to trough (2$a$)
$T$: wave period
$\lambda$: wavelength
$k$: wavenumber
$c_p$: celerity (wave phase speed)
$P$: pressure
$F$: force
$u$, $w$: x-velocity, z-velocity components

```python
# Comment
```

# Add/Delete/Change this Template as you see Fit
When using this template keep in mind that this serves three purposes. The first is to provide your team feedback on your progress, assumptions, and conclusions. The second is to keep your team focused on what you are learning and doing for AguaClara. Another is to educate future teams on what you've learned and done. This document should be comprehensive, consistent, and well-written. With that in mind, add, subtract, or move sections. Reach out to the RAs and graders for help with figuring out what should or shouldn't include. Focus on how wonderful a reference you are making through this and work hard on communicating amongst yourselves and with future teammates. (Delete this section before submitting)

```python
# To convert the document from markdown to pdf
pandoc Name_of_this_file.md -o TeamName_Research_Report.pdf
```