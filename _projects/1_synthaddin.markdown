---
layout: page
title: SYNTH Excel Add-in
description: Developing an interface to make data science available in spreadsheets
img: /assets/img/excel_synth_addin.png
---
<div class="col three caption">
    <img src="{{ site.baseurl }}/assets/img/excel_synth_addin.png" alt="" title="Screenshot of the SYNTH add-in" width="90%"/>
</div>

The <a target="_blank" href="https://synth.cs.kuleuven.be/">SYNTH</a> project has the goal of automating data science.
Automating data science can then allow naive end-users (end users with little knowledge about data science) to perform data science tasks.

Various tools were developed in the context of the SYNTH project to automate different data science tasks.
A list of these tools is available <a target="_blank" href="https://synth.cs.kuleuven.be/content/software-0">here</a>.

To make these tools available to end-users, we decided to focus on spreadsheets, that are a common way to store data.
We therefore developed an add-in for Microsoft Excel. Demos of this add-in are available <a target="_blank" href="https://synth.cs.kuleuven.be/content/software-demo">here</a>.

I was one of the main developers of this add-in, and defined several architectural choices.
I also participated in the definition of interaction mechanisms to allow naive end-users to perform data science in Excel. These mechanisms are presented in this <a target="_blank" href="https://arxiv.org/pdf/2004.11113.pdf">paper</a>.

I used the  Excel Javascript API and React to develop parts of the Excel add-in (the frontend).
I mostly used Python and some of its libraries (Flask, marshmallow, numpy, pandas) to implement the backend.
