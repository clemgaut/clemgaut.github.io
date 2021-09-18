---
layout: page
permalink: /teaching/
title: Teaching
description: Courses I helped teaching and students I supervised
---
## Student supervision

I supervised Master students for their thesis on a variety of topics:
 - Emile Valcke (2020-2021), on developing a model to help football scouts in planning their trips. (co-supervised with <a target="_blank" href="https://scholar.google.com/citations?user=Tdj5P38AAAAJ&hl=en">Mohit Kumar</a>)
 - <a target="_blank" href="https://be.linkedin.com/in/ignace-bleukx-a6341b17a">Ignace Bleukx</a> (2020-2021), on developing a tool to automatically recover data from binary files. (co-supervised with <a target="_blank" href="https://scholar.google.be/citations?user=TmU3sKMAAAAJ&hl=en">Gust Verbruggen</a>)
 - <a target="_blank" href="https://www.linkedin.com/in/shuo-sun">Shuo Sun</a> (2019-2020), on developing a system to intuitively query for soccer actions.
 - <a target="_blank" href="https://in.linkedin.com/in/nirmal-s-kartha-05b73952">Nirmal S Kartha</a> (2019-2020), on explaining the predictions of Isolation Forests (paper submitted at the <a target="_blank" href="https://sites.google.com/view/xaiworkshop/topic">XAI workshop</a> at AAAI21). (co-supervised with <a target="_blank" href="https://scholar.google.be/citations?user=6hNLTrAAAAAJ&hl=en&oi=ao">Vincent Vercruyssen</a>)
 - Boris Doux (2015-2016), on detecting strategic moves in HearthStone games (<a target="_blank" href="https://hal.archives-ouvertes.fr/hal-01412432/">Paper</a> accepted at the <a target="_blank" href="https://dtai.cs.kuleuven.be/events/MLSA16/">MLSA workshop</a> at ECML/PKDD 2016). (co-supervised with <a target="_blank" href="https://www.lamsade.dauphine.fr/~bnegrevergne/webpage/">Benjamin Negrevergne</a>)

## Teaching

{% for item in site.teaching %}
  <div>
    <em>{{ item.period }}</em>:
    <strong>
        {{ item.course }}
    </strong>

  	{% if item.note %}
	    <p>
	    	{{ item.note }}
	    </p>
  	{% endif %}
  </div>
{% endfor %}