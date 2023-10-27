---
title:  "Optimizing Desalination Supply Under Uncertainty"
permalink: /projects/desal/
excerpt: "Two-stage optimization model to find robust solutions for integrating desalination in regional water supply"
header:
    #image: /assets/images/construction.png
    teaser: /assets/images/desalopt/prom_logo.png
layout: single-wide
---
<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

<h3 id="project-overview-">Project Overview:</h3>
<font size="3">
This research introduces a two-stage optimization model coupled with multicriteria decision analysis, aiming to assess the impacts and trade-offs of investing in desalination processes for regional water systems in the face of uncertainty. The study specifically zooms in on the Israeli National Water Supply System (INWSS), showcasing the ways desalination investments enhance system robustness and introduce trade-offs between up-front capital costs and expected recourse costs.
</font>

<h3 id="introduction-">Introduction:</h3>
<font size="3">
Water scarcity is an escalating global issue, and to achieve a secure supply, regional water supply system managers must make decisions in the face of a plethora of uncertainties including consumer demands (municipal, agricultural, industrial), population growth, and climate conditions. Water supply systems in arid regions often rely on desalination to augment traditional water sources, thereby providing drought-resistent supply for the consumers but complicating the management decisions for water managers. With the inclusion of desalination, water managers need to consider the variance in salinity between the different supply sources and find the optimal mixing strategy to meet the necessary water quality goals in the system, all while meeting contractual constraints enforced from public-private partnerships that desalination plants are often funded through. Here, we use the Israeli National Water Supply System (INWSS) as a case study to develop an optimization modeling framework that incorporates uncertainty, multi-quality-sources and desalination constraints in order to analyze tradeoffs in up-front costs, expected recourse costs, and system robustness.
</font>

<h3 id="methods-">Methods:</h3>
<font size="3">
The primary framework is a two-stage optimization model supported by multicriteria decision analysis, as outlined in Figure 1. In the first stage, investment decisions for desalination are made without prior knowledge of future scenarios, while the second stage focuses on operational decisions after unveiling these scenarios. The multicriteria analysis method PROMETHEE aids in evaluating the results across different cost and robustness objectives, with the aim of distilling the results into tradeoffs that are accessible and meaningful to project stakeholders. Given many different scenarios that represent the range of uncertainties faced by water managers, the PROMETHEE method finds management decisions that most closely align with stated stakeholder preferences. 

</font>

<table>
<thead>
<tr>
<th style="text-align:left"><img src="/assets/images/desalopt/framework.png" alt="Framework"></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left">Figure 1. Overview of two-stage optimization process + multicriteria decision analysis.</td>
</tr>
</tbody>
</table>
<font size="3">

The performance metrics explored in this work are split into the broad categories of cost and robustness. The cost metrics include the upfront cost of investing in desalination $$I_{DC}$$, expected recourse costs determined from each of the unveiled scenarios $$ I_{RC} $$, and the expected total cost of the system $$I_{TC}$$. The robustness metrics represent the ability of the system to meet consumer demands $$I_{RD}$$, meet water quality thresholds $ I_{RQ} $, and maintain sustainable levels in natural resources $$I_{RS}$$. A sensitivity analysis was performed on stakeholder preferences in the PROMETHEE method to analyze how the preferred decision changes when stakeholders are cost-focus versus robustness-focus.

</font>

<table>
<thead>
<tr>
<th style="text-align:left"><img src="/assets/images/desalopt/scatter_pplot.PNG" alt="Parallel plot"></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left">(a) Scatter plot of the total desalination investment and robustness score for each preferred solution in sensitivity analysis. (b) Parallel plot of cost and robustness performance for each desalination supply strategy (implementable decisions) corresponding to points in scatter plot.</td>
</tr>
</tbody>
</table>
<h3 id="insights-">Insights:</h3>
<font size="3">
While the up-front investment in desalination is expensive, the results display how increases in desalination production mitigate recourse costs in situations of high uncertainty, both decreasing expected total costs and increasing system robustness. Through the explicit modeling of uncertainty in a scenario-based approach, the results can be made accessible for stakeholders where a posteriori analysis can highlight how changes in stakeholder preferences change the preferred strategies, thereby assisting in revealing such win-win scenarios, illuminating tradeoffs, and exposing tails risks. In addition, a participatory modeling approach is emphasized for complex problems, where the inclusion of stakeholders throughout the modeling and solution evaluation process can help identify stakeholder compromises and conflicts
</font>

<ol>
<li><strong><font size="3">Trade-offs &amp; Robustness:</font></strong> <font size="3">The research found that any increase in the desalination investment<h3 id="publications">Publications</h3>
<font size="3">
Hendrickson, G., Housh, M., and Sela, L. (2023). Optimizing desalination for regional water systems: Integrating uncertainty, quality, and sustainability. Journal of Cleaner Production. doi:10.1016/j.jclepro.2023.137785
</font>


</li>
</ol>

