---
layout:   default
title:    Curriculum vitae
---
# Curriculum vitæ

A virtual *curriculum vitæ*.

## Educational history
---
**University of Washington, Seattle** \\
Doctor of Philosophy in Civil Engineering \\
December 2018 \\
Dissertation: *New Methods for Seismic Performance Evaluation and Retrofit of Nonductile Concentrically Braced Frames* \\
<http://hdl.handle.net/1773/43337> \\
\\
**University of Washington, Seattle** \\
Master of Science in Civil Engineering \\
December 2014 \\
Thesis: *Seismic Performance of Chevron Concentrically Braced Frames with Weak Beams* \\
<http://hdl.handle.net/1773/27443> \\
\\
**North Carolina State University, Raleigh** \\
Bachelor of Science in Civil Engineering \\
Minor in Environmental Science \\
May 2012 \\
Honors: Valedictorian, *summa cum laude*, University Scholars Program \\
\\
**The University of Auckland** \\
Certificate of Proficiency -- Overseas (Study Abroad) \\
July 2011--November 2011

## Employment history
---


| <span style="font-weight:normal"> **Assistant Professor** </span> | <span style="font-weight:normal"> August 2020--present </span> |
| :-- | --: |
| Marquette University, Milwaukee, WI |
| Department of Civil, Construction and Environmental Engineering |
| | |
| **Postdoctoral Scholar**  | September 2018--July 2020  |
| University of Washington, Seattle |
| Department of Civil and Environmental Engineering |

## Publications
---
### Refereed archival journal publications
{% for item in site.data.cv_pubs_journal %}
1. {{ item.authors }} ({{ item.year }}). "{{ item.title }}." *{{ item.journal }}*, {{ item.volume }}. [{{ item.doi }}]({{ item.doi }}).
{% endfor %}

### Refereed archival journal discussions
{% for item in site.data.cv_pubs_journaldisc %}
1. {{ item.authors }} ({{ item.year }}). "{{ item.title }}." *{{ item.journal }}*, {{ item.volume }}.
{% endfor %}

### Conference proceedings and other non-journal articles
#### Fully refereed publications
{% for item in site.data.cv_pubs_nonjournal_ref %}
1. {{ item.authors }} ({{ item.year }}). "{{ item.title }}." *{{ item.collection }}*, {{ item.location }}, {{ item.date }}.
{% endfor %}

#### Refereed by abstract only
{% for item in site.data.cv_pubs_nonjournal_nonref %}
1. {{ item.authors }} ({{ item.year }}). "{{ item.title }}." *{{ item.collection }}*, {{ item.location }}, {{ item.date }}.
{% endfor %}

## Membership
---
Associate Member, American Society of Civil Engineers \\
Educator Member, American Institute of Steel Construction \\
Member, Earthquake Engineering Research Institute \\
Member, Tau Beta Pi Engineering Honor Society

## Licensure
---
Engineering Intern, State of North Carolina, 2012
