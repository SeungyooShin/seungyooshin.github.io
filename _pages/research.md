---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


<h2 id="publications">Publications</h2>

<ul>
  <li>
    <a href="https://www.cambridge.org/core/journals/macroeconomic-dynamics/article/monetary-policy-and-exchange-rate-response-evidence-from-shockrestricted-svar-with-uncertainty-measures/9867905B9A1A2F68B8EA1CD729FFB483#article" style="text-decoration:none" target="_blank">
      Monetary Policy and Exchange Rate: Evidence from Shock-restricted SVAR with Uncertainty Measures
    </a> (with Cheolbeom Park),
    <em>Macroeconomic Dynamics</em> (2026)
    <br>
    <span style="font-size:0.95em; color:#555;">
      This paper is based on my master’s thesis.
    </span>
    <br>
    <button type="button" class="abstract-toggle" aria-expanded="false" aria-controls="svar" onclick="visib(this, 'svar')">Abstract</button>
  </li>
</ul>

<div id="svar" class="research-abstract" hidden>
  We examine the response of the exchange rate to monetary policy shocks using structural vector autoregression (SVAR).
  The SVAR approach in this study differs from previous studies by incorporating uncertainty measures and employing shock-restricted identification constraints.
  Using structural shocks that are in accordance with the event and external variable constraints, we demonstrate that the US exchange rate appreciates immediately
  in response to contractionary monetary policy shocks, with the maximum appreciation occurring within one to two months. 
  Our finding highlights the importance of allowing contemporaneous interaction between interest rate and exchange rate, as facilitated by the shock-restricted SVAR,
  and accounting for uncertainties to address the puzzle of the exchange rate response.
</div>


<hr>
<h2 id="working-papers">Working Papers</h2>

<ul>
  <li>
      When Export-Contingent Tax Incentives End: Multinational Adjustment within and across Countries (Job Market Paper)
  </li>
</ul>



<hr>
<h2 id="work-in-progress">Work in Progress</h2>

<ul>
  <li>
    From Expatriates to Locals: Allocation of Managers in Multinationals
    <br>
    <button type="button" class="abstract-toggle" aria-expanded="false" aria-controls="manager" onclick="visib(this, 'manager')">Abstract</button>
  </li>
</ul>

<div id="manager" class="research-abstract" hidden>
  This paper investigates how multinational firms allocate managerial resources between expatriate and local managers across host countries at different levels of development.
  Using data on Korean multinational affiliates that distinguish workers by both nationality and occupational hierarchy, I document two facts.
  First, the productivity of local managers rises with host-country income, whereas the productivity of expatriate managers varies much less across destinations.
  Second, affiliates entering developing economies rely disproportionately on expatriate managers, but this reliance declines with affiliate age as local managers increasingly assume managerial roles.
  These patterns are consistent with expatriates serving as carriers of firm-specific knowledge whose role is particularly important when local managerial capabilities are initially limited.
</div>


<ul>
  <li>
    Host-Country Financial Developments and Multinational Financing (with Aruzhan Nurlankul)
  </li>
</ul>

<script>
function visib(button, id) {
  var panel = document.getElementById(id);
  var expanded = button.getAttribute("aria-expanded") === "true";
  panel.hidden = expanded;
  button.setAttribute("aria-expanded", String(!expanded));
}
</script>
