---
title:  "Intermittent Water System Modeling"
permalink: /projects/intermittent/
excerpt: "Bayesian optimization model to maximize equity in water access for consumers"
header:
    #image: /assets/images/construction.png
    teaser: /assets/images/iwsopt/fcv_flows.png
layout: single-wide
---
<font size="3">
<h3 id="project-overview">Project Overview</h3>
<p>This research showcases a new hydraulic modeling approach for intermittent water supply (IWS) systems that more-accurately reflect consumer behavior in these systems. A Bayesian optimization approach is coupled with the IWS hydraulic model to determine an optimal flow control schdule that strategically limits flow to some consumers in order to increase access to water for many more, thereby maximizing the supply equity in the system. The highlights of this research include: </p>
<ol>
<li>A hydraulic model that reveals inequity in water access that is not captured with traditional methods</li>
<li>A Bayesian optimization model that improves the equity in water supply through the imposition of a flow control schedule</li>
<li>The revealed mechanisms through which private tanks and disparate hydraulic conditions engender inequity </li>
</ol>
<h3 id="introduction">Introduction</h3>
<p>IWS systems are water distribution systems that are characterized by their inability to provide continuous 24/7 access to water, where as many as 1.3 billion people worldwide are affected by such discontinuous access [1]. To adapt to the the challenges associated with IWS system, many people use private water tanks in their home that they use to store water for periods of non-supply. While providing increased water security for some, the widespread use of private storage tanks exacerbates inequity in supply as those with better pressure conditions are able to consistenty replinish their tanks at the expense of those with less-favorable pressure coniditions. This research aims to (1) explore the mechanisms through which this difference in hydraulic conditions manifests as supply inequity, (2) improve the local supply and global equity through the implementation of an optimized FCV setting schedule, and (3) assess the effects that intermittency in source supply has on the global equity and efficacy of the flow control strategy.</p>
<h3 id="methods">Methods</h3>
</font>

<table cellspacing="0" cellpadding="0">
<thead>
</thead>
<tbody>
<tr>
<td style="text-align:left" style="width:50%">
<ol style=margin-left:"0px">
<li style="1"><p><strong>Hydraulic model:</strong> A volume-driven demand method is used to augment an EPANET model with artificial elements in order to represent IWS consumers with local storage tanks, shown in Figure 1.</p></li>
<li><p><strong>Performance metrics:</strong> The local supply ratio and global equity are calculated for each hydraulic simulation in order to define the performance of the system. The supply ratio is the total supply to a consumer divided by the total demand. The global equity is the normalized average deviation of all the supply ratios in the network, where the greater the difference in supply ratios, the lower the equity value.</p></li>
<li><p><strong>Control model:</strong> Bayesian optimization model implemented in which the objective is to maximize the global equity in the system, the decision variables are FCV settings for each designated time step, and the constraints are the hydraulic equations imposed through the simulation </p></li>
<li><p><strong>Intermittent supply:</strong> The simulation optimization approach is tested under different intermittent source supply schedules</p></li>
</ol>


</td>
<td style="width:50%"><img src="/assets/images/iwsopt/results.png">
Figure 2. Caption. </td>
</tr>
</tbody>
</table>


<h3 id="references">References</h3>
<h3 id="publications">Publications</h3>


