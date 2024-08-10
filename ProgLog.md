# 2024-Summer-Math-Research
Specifics to come.

# Progress log
Each day including general overviews, problems, intended solutions, outcomes, and main takeaways for TL;DR (in that order).

-------------------------------------------------------------

## Pre Sunday 19th May – 
Allanah Neff (PhD candidate at Uni of Edinburgh) and I had a few zoom meetings to discuss a general direction for the summer research, proposals included PDEs with relation to fluid mechanics, as well as DEs with relation to cell membranes, this was something that really interested me. Allanah’s supervisor had previously done a thesis on a similar thing, however hers was very much theoretical as it didn’t utilise experiment-gathered data. This data is now accessible, and the general idea was to create a particular differential equation to model the movement of ions (potassium) through a cell membrane, with interest in voltage too. To explore this Allanah sent me some notes from a module at her masters at Oxford, titled Mathematical Physiology, for me to better understand the idea we were talking about. Up to this point, the specific project is uncertain, but we have a general direction, and planned to meet tomorrow on the 20th May.

### TL;DR | Main takeaways:
1. The project will be in the area of Applied Maths within Biology/Physiology, utilising an data set from an experiment.
2. Prepare directional questions for the meeting on the 20th May
3. Keep on top of UKMT summer school commitments (seperate project)

-------------------------------------------------------------

## Tuesday 21st May -
The meeting was moved to today at 10AM, so to prepare for the meeting I made notes on all of the topics I was unsure on, notably mass-action kinematics, along with some partial differential equations describing the flux of ions through a cell membrane. The meeting was about general understanding, and to correct the direction of my reading. My supervisor (Allanah) gave me a new book to read, Mathematical Physiology II by Sneyder, and told me to grasp an understanding of mass-action kinematics too. The next meeting is on Friday the 24th May, to discuss my findings and point to forward work; as she is away the following week. The research is looking like it'll be into refining a model that her supervisor (Dr Mariia Dvoriashyna) researched/created for a publication a few years ago. I have a better grasp of the general topic idea now from my reading, and hope to be even more confident talking about the idea with my supervisor at the end of this week.

### TL;DR | Main takeaways:
1. Read into 'Mathematical Physiology by Sneyd'
2. Research Mass-action kinematics

-------------------------------------------------------------

## Tuesday 28th May -
Allanah has a research trip this week so I am delving deeper into the reading and having a go at the questions. The real issue at the minute is the notation. A lot of the topics aren't too alien, except some complex differential equations, but the notation since it is a different discipline of Mathematics is proving hard. Having made notes on the relevant chapter of Mathematical Physiology I know that I need to go back over them, and perhaps subsitute other mediums of learning, like articles, videos, lectures to supplement my learning. Mass-action kinematics were simpler than I thought, it was just a rule outlining when you can use the form of differential equation in reaction schemes, and when you can't (when the process is complex and has multiple different steps and stages). I am looking to be able to tackle atleast one question from the exercises section in the chapter before my meeting with Allanah next week (3rd June- 10th June), this is looking very difficult but I am keen to try. I will update this README accordingly.

### TL;DR | Main takeaways:
1. The reading is going well so far, but I need other mediums of learning to supplement the process (lectures, articles).
2. Try and tackle one question from the exercises in the Chapter of Sneyd's book.
3. Be prepared to have a productive meeting with Allanah next week where we can take a big step forward.

-------------------------------------------------------------

## Friday 14th June - 
It's been a while since I updated the log, this is due to there only being one meeting since the previous log, and also both Allanah and I had other things going on. Since the last log, I successfully carried out steps 1, 2 and 3 from the Main takeaways. Moving on, the most recent meeting we went over the equations that Sneyd uses in the book to derive certain characteristics and create specific plots for the pump-leak model, which is what we are looking at right now. The pump-leak model is effectively a process by which a cell uses both active and passive transport in controlling its volume as well as its charge and ion population. When we went over these equations two things were apparent. 

### Problem:

I didn't yet know enough around the subject to fluently communicate my thoughts, and as such didn't understand the topic to a sufficient depth.

### Intended solution:

So coming away from the meeting I knew I had to act on these two things. As such here are my proposed steps to remedy this issue:
1. Take a step back and try and see/understand the larger picture here, I need to really explore the topic in its entirety, not this one model in isolation.
2. Try and find some motivation/real-world reasoning for why we should care about this model, or functions of the cells themselves.

### TL;DR | Main takeaways:
1. I faced my first challenge of the project so far. I have written down and planned steps of how to deal with this, and hope to feel better about it by next week.

-------------------------------------------------------------

## Sunday 16th June -
I've made some progress since the last log, successfully finding where every component came from within the equations that Sneyd lays out to be vital for solving a model of the pump-leak model. This includes an equation that states the rate of change of concentration of an ion equals the volume of passive transport plus active transport (it's not as simple as that), which makes perfect sense. Stepping back helped me understand this whole model that Sneyd explores much more clearly. Including learning about the Gibbs free energy equation, the Nernst equation, and the relationship between membrane equilibrium and chemical potential. On the motivation side of things, I have found some points as to why we should care about the regulation of cell volume, this includes facilitating osmosening in the hypothalamus (this triggers the feeling of thirst), as well as being inherently linked to cancer growth. I haven't yet finished my docx on motivation, I hope to have this done before Tuesday, giving me time to recap my new notes, and find something else to bring to the next meeting. The whole process is becoming more clear now.

### TL;DR | Main takeaways:
1. Continue to develop the docx that lays out the motivation for the research, and here specifically the pump-leak model. Before Tuesday
2. Recap and read further before the next meeting, as to continute the momentum of progress.

-------------------------------------------------------------

## Monday 24th June -
Allanah and I have a meeting today and on Friday. Last meeting we went over the method in Sneyd's book that he uses to solve these complex differential equations. Non-dimensionalisation. It is a method by which you reduce a variable (with it's dimensions) like V m/s to just a constant like A. You do this by dividing by another variable that has the same units. So we could divide two velocities by each other. This allows Sneyd to disregard lots and lots of constants, as well being an integral part of asymptotic analysis. With this method we can see which components of equations are important to what we are looking at. For instance if we were to reduce a voltage equation to a non-dimensional variable and in the variable we had a constant worth 1x10<sup>-10</sup> of the magnitude of other components, we can ignore it for a specific solution. After solving, we then can re-contextualise to make the reader understand. This is a very difficult thing to navigate so I had to do so carefully. Sneyd's book was a little hard to follow given the intended audience, as such I encountered several problems last week.

###  Problem:

Not fully understanding Sneyd's steps in solving the pump-leak model, and not knowing how to properly navigate non-dimensionalisation (or really what it is).

### Intended solution:

This would require a good amount of reading to deal with, so here were the steps:
1. Solve the equations as Sneyd does, trying to navigate the algebra on my own, occasionally checking to see if I was on the right path.
2. Add intuitive notes to explain to myself why certain steps were being taken, what the non-dimensional variables are telling us, coefficient analysis.
3. Write up an overview of all this, in 3 sections. Non-dimensional variables in a short-form, almost like a cheatsheet. Typical values of constants and their dimensions, to allow me to grasp a better intuition. Relationships between the variables, for instance membrane potential and the pump rate of the ATPase.

### Outcome:

An excellent section of notes that really helps me to understand the topic better. Having delved into an example of solving via non-dimensionalisation I feel better prepared to tackle one of these modelling solves on my own later down the line (which will be neccesary). The overview is extremely helpful to recap before today's meeting.

### TL;DR | Main takeaways:
1. I successfully carried out a detailed solution plan to fix the problem of not-understanding the content we are working through at the moment.
2. I look to update the log tomorrow with the direction plan from after today's meeting.
   
-------------------------------------------------------------

## Thursday 25th June - Plot-physiology-first Jupyter NB attached
Monday's meeting with Allanah, was primarily around making plots for what we have found so far. My experience in programming at this point is just R, yet going forward we were just to use Python in this project. The idea before the next meeting (Friday) was quite simple. Re-create Sneyd's plots in the book, look into the Goldman-Hodgkin-Katz Equation, and bifurcation theory. All of these to try and refine all the models we have seen so far, by using non-linear relationships, and to look at how we can move toward actually conducting the new research. In creating the plots I came accross a problem.

### Problem:

The plot that I coded looked nothing like Sneyd's plot. And Sneyd didn't elaborate on the specifics of his plot.

### Intended solution:

1. In detail write down all of the different variables/functions Sneyd could have used i.e. did Sneyd use the precise model for pump rate or did he use the non-dimensional version of it (which would make the model less accurate). 
2. And then try them out in different combinations, to find out what he likely used in the book's plot.

### Outcome:

1. 2 plots that look exactly like Sneyd's plot. With more insight into the technicals behind the plot; a better insight into the relationship between the pump-rate of the cell's pump and cell volume or cell membrane potential. 
2. One HUGE thing that came out of this trial and error, was that it implied that conductance, (gamma = g_na / g_k), in the model played a very important role in the end behaviour of the relation between pump-rate and cell volume. Before, when I was using the precise derivation of gamma, the behaviour was stable at ~0.6 cell volume as pump-rate tended to infinity. However, Sneyd used an assumption that gamma = 0.11, and his end behaviour was that cell volume tended to infinity as pump-rate tended to 14. Giant difference. 
+ + This is good news, as my work with this entire research project is making the variable conductance more accurate in a pre-determined model, by examining experimental data; so it's likely to have a decent impact when I do.

### TL;DR | Main takeaways:
1. I successfully learned how to use Python, NumPy and Matplot to intuitive visualise the relationships between the models I have been studying/deriving mathematically.
2. I successfully discovered the assumptions that Sneyd used in his book, in order to make my plots a more accurate emulation of his.
3. I discovered that conductance is an important component in these models, which foreshadows my research/work on all of this will have a tangible effect.
4. I better understand what the GHK Equation is, and what bifurcation theory is.

-------------------------------------------------------------

## Tuesday 2nd July - Plot-physiology-linear-Allanah Jupyter NB attached
Today's meeting we went over my plots that I had made the week prior, overall they were accurate, but with a few issues. My plot of pump rate against membrane potential didn't include the individual equilibrium potentials of sodium and potassium, and my global minimum didn't quite match up with the book's values. So we decided to add the two equilibrium potentials onto the same plot. This again was an issue for us as we couldn't seem to derive what the equations that led to the plot actually were. This is laid out below.

Other than going over the plotting issue, we also discussed the overall project, Allanah said that she is asking her supervisor about what she wants out of the data. If a specific instruction is given then we will finish up this foundational exploration and begin unique research, if not, we will discuss which direction to go into. In the meantime I am to look at the non-linear model of the Goldman-Hodgkin-Katz Equation and re-do all of the solving using non-dimensionalisation, in order to precisely derive plots for relationships between pump rate and cell volume or membrane potential. Further, with a non-linear model we can conduct some minor bifurcation theory, something that will be very interesting to explore and write up about.

### Problem:

Could not find the equations/code to accurately plot the equilibrium potentials of sodium and potassium in our model. And the general membrane potential against pump rate wasn't perfectly accurate.

### Intended solution: 

Group all equations into two groups, dimensional and dimension-less. And plot them on two different graphs to examine if our error was in the transition between dimensional and dimensionless.

### Outcome: 

Looking at the relationships between the two groups we uncovered that actually the issues were in the original equations rather than in the later stage variations. We were deriving these equilibrium potentials from the same set of differential equations we used to solve for membrane potential, actually they are simply equal to the Nernst Potential, something clearly defined. Once we plotted the Nernt Potential for each ion, we saw an almost perfect fit with Sneyd's model.

Other than going over the plotting issue, we also discussed the overall project, Allanah said that she is asking her supervisor about what she wants out of the data. If a specific instruction is given then we will finish up this foundational exploration and begin unique research, if not, we will discuss which direction to go into. In the meantime I am to look at the non-linear model of the Goldman-Hodgkin-Katz Equation and re-do all of the solving using non-dimensionalisation, in order to precisely derive plots for relationships between pump rate and cell volume or membrane potential. Further, with a non-linear model we can conduct some minor bifurcation theory, something that will be very interesting to explore and write up about.

### TL;DR | Main takeaways:
1. Successfully utilised problem-solving skills to find the exact equations that Sneyd used in his plots of the pump-leak model. By grouping plots by dimension-less and dimensional, and recognising the fault.
2. The next step is to utilise a more complex (but precise) non-linear model, the Goldman-Hodgkin-Katz Equation. By applying non-dimensionalisation to solve the model, and then plotting it, we should arrive at a more accurate end product.
3. After completing the more complex model, I need to look into bifurcation theory to prepare for later on in the project.

-------------------------------------------------------------

## Wednesday 17th July - 
Over the last 2 weeks, I have just been solidifying my understanding of the different mechanisms used in different texts. In Sneyd's book and our earlier plots, we used very simple models, that lacked accuracy yet made up for it in ease of manipulation. Now we are moving into the more complicated components, such as the GHK equation as considered and talked about in the above log (Tuesday 2nd July). More recently, I have been reading Allanah's supervisor's paper, and going through the references. Paying specific detail to Strieter, and Ussing too. My new findings are that the new mechanisms don't rely on linear relationships describing currents, but instead use non-linear ones as it makes the analysis and solving more easy (it doesn't hurt that it is also more precise). The goal for this section of the research is to really build up intuition and broad understanding, as it is soon that we start conducting the research.

### TL:DR | Main takeaways:
1. I now have detailed notes outlining the differences between the mechanisms utilised by Sneyd compared to Mariia (Strieter), and how Ussing plays a part in the latter's development.
2. I feel much more confident in my ability to communicate with my supervisor about the topic as a whole, the difference between now and 2 months ago is vast.

-------------------------------------------------------------

## Saturday 3rd August - Plot-StrieterFlux.ipynb
It's been a while since my last update, as I was working away from home for a good chunk of time. We have a meeting tomorrow about differing mechanisms and the next direction for the project. Attached to this commmit is a notebook of a small intuition exercise I was curious about. In the new mechanisms I wanted to observe the effects of changing intracellular concentrations of sodium and how this would effect the flux in Strieter's model, within Mariia's paper; so I plotted it. I did this ahead of tomorrow's meeting to refresh my mind on the topic.

-------------------------------------------------------------

## Saturday 10th August - InitialAlgPhysioSolve.ipynb
Recently Allanah and I have had several meetings in quick succession. What we have laid out is a general scheme for producing the final report, involving motivation, model setup, model solution and then considerations of a dynamic solution as well as utilising the experimental data we now have, to fine tune our parameters and assumptions around passive transport and the GHK flux equation. From this I have recently (today) been working with SciPy in solving a system of equations, plotting out individual variables and confirming that our results are similar to ones found in other papers. However, I have just ran into an issue surrounding my equation for the cotransporter flux, and specifically an issue that the model has with the concentration inputs. I will lay this out in the following subsection:

### Problem:

'RuntimeWarning: invalid value encountered in log Cotransporter'. This is an issue that SciPy has with small parameters within the flux equation for ion movement through the Cotransporter. Making our overall solution less accurate that we would like it to be. 

### Intended solution: 

1. Assume that the initial inputs into the system of equations is the exact (or near exact) values found in other papers. 
2. Replace one of the concentration variables with a for loop, and plot it against the voltage with Matplotlib.
3. Observe how the voltage changes in hopes of discovering what is going wrong in the Cotransporter equation.
4. Repeat with each concentration.
5. Change the equation accordingly, so that we dont ecounter the run time warning.

### Outcome: 

After carrying out the first 4 steps, I am still a little lost on what the issue is with the Cotransporter equation. This will require some handwritten calculations later on in the day. I will update this log after doing so.
TBC

### TL;DR | Main takeaways:
1. We now have a proper skeleton of what the written up paper/report will look like.
2. I learned how to solve a complex system of differential and algebraic equations with SciPy, utilising Matplotlib.
3. I was able to optimise the system of equations by altering the Cotransporter flux equation to avoid the run time warning.
4. Going forward, before next meeting I want to unassume that the voltage is the same at the intra-apical membrane and the intra-basal membrane, this will involve assuming the system is an open circuit and then solving it; and could result in some interesting conclusions.

-------------------------------------------------------------
