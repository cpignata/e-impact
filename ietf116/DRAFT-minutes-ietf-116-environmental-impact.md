# IETF116 “Environmental Impact” Side Meeting

## Table of Contents

<!-- MarkdownTOC autolink="true" autoanchor="true" -->

- [Meeting Minutes](#meeting-minutes)
   - [Administrativia](#administrativia)
- [Part 1. Introduction](#part-1-introduction)
   - [Introduction, Purpose, and Goals – Carlos Pignataro](#introduction-purpose-and-goals-%E2%80%93-carlos-pignataro)
   - [E-Impact IAB Workshop Summary – Jari Arkko](#e-impact-iab-workshop-summary-%E2%80%93-jari-arkko)
   - [Next steps towards a net zero IETF – Greg Wood](#next-steps-towards-a-net-zero-ietf-%E2%80%93-greg-wood)
- [Part 2. Internet-Drafts](#part-2-internet-drafts)
   - [Challenges and Opportunities in Green Networking – draft-cx-green-ps – Alex Clemm](#challenges-and-opportunities-in-green-networking-%E2%80%93-draft-cx-green-ps-%E2%80%93-alex-clemm)
   - [Green Networking Metrics – draft-cx-green-metrics – Alex Clemm](#green-networking-metrics-%E2%80%93-draft-cx-green-metrics-%E2%80%93-alex-clemm)
   - [Sustainability Insights – draft-almprs-sustainability-insights – Marisol Palmero](#sustainability-insights-%E2%80%93-draft-almprs-sustainability-insights-%E2%80%93-marisol-palmero)
   - [A Framework for Energy Aware Control Planes – draft-retana-rtgwg-eacp – Alvaro Retana](#a-framework-for-energy-aware-control-planes-%E2%80%93-draft-retana-rtgwg-eacp-%E2%80%93-alvaro-retana)
   - [Energy-related Effort within the IETF – draft-eckert-ietf-and-energy-overview – Toerless Eckert](#energy-related-effort-within-the-ietf-%E2%80%93-draft-eckert-ietf-and-energy-overview-%E2%80%93-toerless-eckert)
- [Part 3. Outro and Next Steps](#part-3-outro-and-next-steps)
   - [Open Mike & Discussion – All](#open-mike--discussion-%E2%80%93-all)
   - [Wrap & Next Steps – Carlos Pignataro](#wrap--next-steps-%E2%80%93-carlos-pignataro)
- [Webex Chat \(copy/paste\):](#webex-chat-copypaste)

<!-- /MarkdownTOC -->


<a id="meeting-minutes"></a>
## Meeting Minutes

Date and Time: THURSDAY 30 March, 13:00-14:30 UTC+9  
Scribe: Marisol Palmero (with thanks!)



<a id="administrativia"></a>
### Administrativia

After checking that the in-room mic/speakers worked with Webex and remote attendance, Carlos Pignataro reviewed the [Agenda](https://github.com/cpignata/e-impact/blob/main/ietf116/Agenda.md), which includes 3 parts:
1. Intro, context, goals
2. Internet-Drafts
3. Outro (discussions and next steps)

Agenda: [Agenda](https://github.com/cpignata/e-impact/blob/main/ietf116/Agenda.md)


<a id="part-1-introduction"></a>
## Part 1. Introduction

<a id="introduction-purpose-and-goals-%E2%80%93-carlos-pignataro"></a>
### Introduction, Purpose, and Goals – Carlos Pignataro

Goals for the side meeting:
continuation of the work from the IAB Environmental Impact workshop (December 22), and most importantly, 
discuss potential mechanics for continuation, what's next from here.

> Comments from John Klensin:
Leaving aside general passion for the world, define sustainability and the objectives for IETF.

> Comments from Eve M Schooler:
Move from volunteering to required, in the sense that IETF will be ready and prepared, once the regulatory requirement is there.

> Some other comments:  
offsetting: needs further analysis  
IETF needs to keep getting better at hybrid events  
how to be more efficient in Participation  
travel: reducing in-person meetings?


<a id="e-impact-iab-workshop-summary-%E2%80%93-jari-arkko"></a>
### E-Impact IAB Workshop Summary – Jari Arkko


Jari provided a summary from the IAB workshop:
From the point of view of the submissions of position papers: it was a success.
Jari also provided a high level summary from the different presentations and papers from the workshop:
what can we do related to the cost of energy, to benefit the environment, and research work, etc.

The full report is available as an IAB submission:
Report from the IAB Workshop on Environmental Impact of Internet Applications and Systems, 2022 draft-iab-ws-environmental-impacts-report.
A mailing list is also created.

Some of the comments from Jari:
Diversity on papers submissions, showing interest in network protocols, collaborating with other technical minds.
High-level conclusions being important on how the Internet can be important to society.
Remote vs hybrid meetings.
Also the list of technical matters:
metrics, data format, clever way of saying things, how to use proof of work, ...
try to get an open discussion with the audience:
how to relate to the non-protocol design,
how to improve the measurements,
how to get the data,
how to enable more dynamically enable elements.

from Jari: Metrics, encoding, sleep modes.


What's next and what are the suggestions?
From the above, it has been more on the starting points: 
Getting the understanding from IETF... keep on talking, interact with others, better data formats, etc.



<a id="next-steps-towards-a-net-zero-ietf-%E2%80%93-greg-wood"></a>
### Next steps towards a net zero IETF – Greg Wood


IETF administration, 
trying to understand what the Carbon footprint is for: meetings, travel to participation, hotels... 
IETF has been developing a calculator to understand the Carbon footprint for meetings. 

Main objectives from IETF at the moment:
Calculation of the  carbon footprint.
How we can improve the fidelity of those calculators?
Defining offsetting as how we can improve what we do on current meetings: from signing to the badges, food waste plans, looking for how to find more offsetings options.


<a id="part-2-internet-drafts"></a>
## Part 2. Internet-Drafts

<a id="challenges-and-opportunities-in-green-networking-%E2%80%93-draft-cx-green-ps-%E2%80%93-alex-clemm"></a>
### Challenges and Opportunities in Green Networking – draft-cx-green-ps – Alex Clemm

Challenges and opportunities on green networking, presented in NMRG
identify research challenges and opportunities to run better network support.

Some of the points discussed by Alex:
Network level, protocol level, and architecture level. 
Virtualize energy. 
How do we manage energy sources, how do we distribute energy to different flows, certifying and assess carbon footprint?
carbon footprint might be optimized based on some of those parameters
production aware routing.
AI/ML methods.
Traffic steering.
Protocols: how to do better.
Instrumentation from the flow, path, etc.

> Comments from Lars:
Operational carbon: very long time if you want to recover...  

> Comments from Carlos Pignataro:
For networking gear it is 70+ % is in the use phase, as opposed to the manufacturing and procurement.
Optimizing use phase is a high return.  

> Comments from Dean Bogdanovic:
The car industry is different: 70 % is in the manufacturing.
Optical components within the system are the highest investment in carbon footprint.


<a id="green-networking-metrics-%E2%80%93-draft-cx-green-metrics-%E2%80%93-alex-clemm"></a>
### Green Networking Metrics – draft-cx-green-metrics – Alex Clemm


The draft presented in OPSAWG. 
A big opportunity is agreeing on Metrics.

Data models: visibility and instrumentation, how to assess and take actions.
From the device perspective: energy sources to be taken into consideration, enhancing 
Flows, path, network at large: traffic volume ... how to align carbon intensity on paths.

Additional considerations:
Energy consumption vs carbon footprint.
Taxation factors.
Accuracy considerations ... ranges vs absolute values.

> Open for comments: no further comments

<a id="sustainability-insights-%E2%80%93-draft-almprs-sustainability-insights-%E2%80%93-marisol-palmero"></a>
### Sustainability Insights – draft-almprs-sustainability-insights – Marisol Palmero

Marisol presented.

> Comments from Eve (learning experience forums), we need to also go beyond IETF. 
Forums that Eve thinks would be interesting to investigate would be: (1) the Open Group's OFP (Open Footprint Forum) that aims to standardize the carbon footprint data model, and CNCF's OCP (Open Compute Project) that is more focused on data centers but still has interesting participation and output.
Another might be to see how far along the [NGMN](https://www.ngmn.org/) community has come with their metrics analysis in the wireless/cellular realm.




<a id="a-framework-for-energy-aware-control-planes-%E2%80%93-draft-retana-rtgwg-eacp-%E2%80%93-alvaro-retana"></a>
### A Framework for Energy Aware Control Planes – draft-retana-rtgwg-eacp – Alvaro Retana


Main point on the presentation: there are tradeoffs to consider.

TVR proposal: instead of using 4 hops, it could be 3 hops... include jitter or delay. 
How regrouping depending on the service that I'm offering this might be more significant or less 
provider backbone.

The objective: it is to improve but there are tradeoffs, doing something that will affect others, and environmental consensus, but things to take into account.
How to put that service, if we reduce infrastructure... 
if I need to recover the network it might be some impact... Time variant way ... how I respond to the loss, considering convergence size.

> Comment from Carlos:
waking up for devices is more time-consuming than putting them to sleep.
Top-down approach, it isa  multi-objective optimization: at first glance even opposing objectives. Research work needed.

> Comments from Jari: 
Well presented. Two levels of impact: (1) Influence outcomes and (2) Technical impact.
Latency impact, it depends on who is using the network ... 
Should we add more energy to the Internet or be safe?

> Alvaro's responses: BT is a coauthor, they consider that the level of business consideration is there.

> Comments from Carlos: SOFT and HARD requirements.

> Comments from Dean Bogdanovic: 
Optimizing some of the router decisions, adding some parameters is something that can be taken into routing decisions.

> Additional Comment: Impact on two levels: (1) network metrics, and (2) UX metrics.

> Comments from Toerless: 
Optimization on new equipment vs legacy. The separation between the control plane and data plane (which is CPU intensive)



<a id="energy-related-effort-within-the-ietf-%E2%80%93-draft-eckert-ietf-and-energy-overview-%E2%80%93-toerless-eckert"></a>
### Energy-related Effort within the IETF – draft-eckert-ietf-and-energy-overview – Toerless Eckert


(To be?) adopted as WG draft in OPSAWG 

Toerless draft is a summary of the IETF-related work to energy-related efforts that have been done in the past.

The fastest the network is, the better energy efficiency.
Toerless refers to bad and good energy. If all the energy is bad and produces Co2 when consumed, try to minimize it. If good energy, how we can reuse it?
Goal might be to bring digital workload to the places with a positive impact.

Detailed low-power networks: 
Protocols and mechanisms, and working groups and technologies.
Technology enables, power awareness on routing protocols from 2011 

> Comments from Lars:
Excellent Presentation, useful.


<a id="part-3-outro-and-next-steps"></a>
## Part 3. Outro and Next Steps


<a id="open-mike--discussion-%E2%80%93-all"></a>
### Open Mike & Discussion – All


Comments from  Lars:
Agreed on some drastic scoping, simplifying. 
For example, consider: "All energy is bad."
That results in goals of reduction of the use of energy versus of scheduling.

Comments from  Lars:

Is more Internet better to save carbon? 
Assume: less energy on the Internet is better.
Start from use cases, scope for interop:
Data Centers, etc. 

Comments from Suresh:
Provide the visibility, to see the impact
more networks are built up, 
devices that are consuming a lot.



Comments from Alissa: 
Agrees with Lars... we don't control how much Internet is used. Therefore, reduce energy. 
To become NetZero... I need to produce this because this is what I consume.
What is quantifiable? Interest from implementers to achieve. The obvious is to define those metrics

Comments from Dean Bogdanovic:
Many places where the internet needs to look at energy. Build Internet in other places.
We can add as a criterion to the routing decisions, how power is consumed? To optimize the routing.


Comments from Jari:
Focus on one thing. Focus on what we can control.
Trust to avoid cross-domain solutions, and also try to avoid the need to trust what others say.
A point to start might be: try to qualify exercise considering all energy is bad.
Green energy is not available for everything. So, think short term and do.


Comments from Rob Wilton: 
Define short-term or longer term.
Measuring energy. 
Work on a charter. Start the work.



<a id="wrap--next-steps-%E2%80%93-carlos-pignataro"></a>
### Wrap & Next Steps – Carlos Pignataro 

Summary of what has been said:
* Focus on what we can control, on phased approach. 
* I heard three groupings: (1) Metrics, (2) Proportionality of topology, (3) Operations.


Questions to the audience:
* Support for coordinating this work?
   * Show of hands: All (not considering Webex chat)


* How do we continue from here: Do we support a BOF Submission for IETF117?
   * Show of hands: 90% up (not considering Webex chat)

Will send summary and minutes to the list.

EOF.

---

<a id="webex-chat-copypaste"></a>
## Webex Chat (copy/paste):


```plaintext
from David (Guest) to Everyone:    6:38  AM
What does ISO stand for? International Standards Organization?
from David (Guest) to
 Everyone:    6:39  AM
(referring to "ISO Lifecycle" in the current presentation)
from David (Guest) to Everyone:    6:40  AM
ISO 14004?
from Jan Lindblad (Cisco) to Everyone:    6:41  AM
ISO 14040, I think
from Rob Wilton (Cisco) to Everyone:    6:48  AM
Can you hear Dean, remotely?
from Jan Lindblad (Cisco) to Everyone:    6:48  AM
We could hear
from Rob Wilton (Cisco) to Everyone:    6:49  AM
Thanks
from Jan Lindblad (Cisco) to Everyone:    6:49  AM
Eve comes through loud and clear. Whatever she does, everybody else should copy :-)
from Rob Wilton (Cisco) to Everyone:    6:50  AM
@Jan, i.e., attend remotely :-)
from Cedric Westphal (Guest) to Everyone:    6:50  AM
saving energy too!
from Jan Lindblad (Cisco) to Everyone:    6:51  AM
Yeah! That explains it. For us remote, it's not easy to know. Many speakers are not in view when speaking, so apart from audio quality, it's hard to tell
from Marisol Palmero Amador (Cisco) to Eve Schooler (Guest) (privately):    6:52  AM
thanks, Eve for your comments, for the notes, I could not take the names that you raised
from Marisol Palmero Amador (Cisco) to Eve Schooler (Guest) (privately):    6:53  AM
could you please list here those organizations you mentioned, will be good to collaborate/coordinate the next steps
from Cedric Westphal (Guest) to Everyone:    6:55  AM
in fairness, it seems to have been fixed, we can hear Alvaro nicely
from Jan Lindblad (Cisco) to Everyone:    6:56  AM
Yes, it's pretty good, esp. compared to how it was initially. But it's still a long way off using meet echo with multiple mics etc.
from Eve Schooler (Guest) to Everyone:    6:57  AM
Two that I think would be interesting to investigate would be: (1) the Open Group's OFP (Open Footprint Forum) that aims to standardize the carbon footprint data model, and CNCF's OCP (Open Compute Project) that is more focused on data centers but still has interesting participation and output
from Jan Lindblad (Cisco) to Everyone:    6:57  AM
Thanks Eve!
from Alexander Clemm (Guest) to Everyone:    6:57  AM
In the room we can all hear perfectly...  goes to show, it is all about tradeoffs - QoE vs energy savings (if attending from remote)
from Eve Schooler (Guest) to Everyone:    6:57  AM
Another might be to see how far along the NGMN community has come with their metrics analysis in the wireless/cellular realm
from Eve Schooler (Guest) to Everyone:    6:58  AM
ngmn.org
from Toerless Eckert (Guest) to Everyone:    7:01  AM
+q
from Alexander Clemm (Guest) to Everyone:    7:04  AM
+q
from Alexander Clemm (Guest) to Everyone:    7:06  AM
-q
from Jan Lindblad (Cisco) to Everyone:    7:27  AM
Great proposition, Rob!
```
