---
title: "Battle of Intermittent Water Supply"
permalink: /projects/biws
excerpt: "International hydraulic modeling competition to optimize supply in intermittent water supply systems"
header:
    teaser: /assets/images/biws/iws_logo.png
layout: single-wide
---
<font size="3">
<h3 id="project-overview">Project Overview</h3>
<p>

This research showcases my team's solution approach in the Battle of Intermittent Water Supply (BIWS) competition hosted by the Universitat Politècnica de València in València, Spain. 


<h3 id="introduction">Introduction</h3>
<p>

The background for the BIWS competition can be found <a href="https://wdsa-ccwi2022.upv.es/battle-of-water-networks/#:~:text=The%20Battle%20of%20Intermittent%20Water%20Supply&text=A%20network%20with%20uncontrolled%20demand,on%20intermittent%20supply%20by%20zones."> here</a>. The basic idea is that the teams are given a hydraulic model for a detiorated water network that is operated as an intermittent system. The teams have to make infrastructure investment decisions (replacing pipes, fixing leaks, adding valves, etc.) with a yearly budget along with control decisions (close/open valves, valve settings, etc.) for each year in a five-year time horizon. The final solution is based on 9 metrics built around increasing pressure in the system, supply to the consumers, and equity in supply.


</p>
<h3 id="methods">Methods</h3>

The following methods summarize our team's approach:


<ol>
<li><p><strong>Network sectorization:</strong> Gate valves are installed to sectorize the network into subzones.</p>
</li>

<li><p><strong>Model reduction:</strong> The complex network is reduced to a simplified, hydraulically-equivalent network using <a href="https://github.com/meghnathomas/MAGNets">MAGNets</a> that serves as proxy for the control optimization model. Both networks show in Figure 1.</p>
</li>

<li><p><strong>Investment model:</strong> I developed a <a href="https://en.wikipedia.org/wiki/Greedy_algorithm">greedy optimization algorithm</a> that itertively determines the optimal leaky pipe to replace and continues until all pipes have been replaced. A metric improvement vs cost curve is built from the results for each subzone, and I run a new optimization model which allocates the cost to spend on pipe replacement for each subzone based on the subzone-specific curves. </p>
</li>

<li><p><strong>Control model:</strong> The nonlinear network hydraulics are approximated with a mixed-integer linear model, where the objective is to <strong><font color="#5E7AE4">maximize supply to users</font></strong> and <strong><font color="#CF7300">minimize leak volumes</font></strong> and the decsions are the control valve settings over the model time horizon.</p>
</li>

<center><img src="/assets/images/biws/objective.png" width="500"></center>

<li><p><strong>Iterative optimization:</strong> The investment and control optimization models were iteratively solved for each year of the five-year horizon.</p></li>
</ol>

<center><img src="/assets/images/biws/iws_logo.png"></center>



<h3 id="results">Results</h3>
<ol style="margin-left:-25px">
    <li><p>Volume-driven demand model reveals inequities that traditional demand models don't capture.</p></li>
    <li><p>Hierarchy in supply: Local storage allows consumers with better pressure conditions to be "first in line" for water whenver supply is available</p></li>
    <li><p>Intermittency in source supply exacerbates consequences of supply hierarchy in increases inequity</p></li>
    <li><p>Bayesian optimization shows inmproved computational performance over meta-heursitic optimization methods when objective function is expensive.</p></li>
</ol>
<h3 id="Insights">Insights</h3>
The conference was a lot of fun! Some very interesting research being done on intermittent water systems that inspired some of my dissertation work.

Some photos from the conference / Valencia!

<center><img src="/assets/images/biws/presenting.jpg"></center>

<center><img src="/assets/images/biws/dinner.JPG"></center>

<center><img src="/assets/images/biws/skydiving.JPG"></center>

<h3 id="publications">Publications</h3>


