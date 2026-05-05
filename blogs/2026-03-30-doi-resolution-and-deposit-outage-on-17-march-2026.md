---
title: "DOI resolution and deposit outage on 17 March 2026"
url: "https://www.crossref.org/blog/doi-resolution-and-deposit-outage-on-17-march-2026/"
date: "Mon, 30 Mar 2026 00:00:00 +0000"
author: "Dominika Tkaczyk"
feed_url: "https://www.crossref.org//blog/index.xml"
---
<p>On 17 March 2026, we experienced an outage that affected DOI resolution for Crossref DOIs and the deposit of metadata records by Crossref members. In this summary, we outline what happened, the impact on our community, and the steps we are taking to strengthen our systems and processes as a result.</p>
<p>Starting around 06:30 UTC, a surge of traffic to the Handle System, governed by <a href="https://www.doi.org" target="_blank">the DOI Foundation</a> and operated by <a href="https://www.cnri.reston.va.us" target="_blank">CNRI</a>, caused instability across several handle servers. As a result, users couldn&rsquo;t resolve Crossref DOIs. Because the Crossref system relies on the Handle System to register new DOIs and update resolution information for existing ones, metadata deposits by Crossref members were also failing.</p>
<p>Although the handle service was <a href="https://doi.statuspage.io/incidents/f4cqcppc1q41" target="_blank">restored by 09:30 UTC</a>, the Crossref system held onto stale authentication sessions and did not automatically recover. Once we restarted the affected servers, deposit processing returned to normal around 10:18 UTC. We later reprocessed the failed submissions to ensure that members did not need to take any action.</p>
<p>While incidents like this are disruptive for our community, several aspects of our response worked well. Our support and technology teams reacted quickly, and we were able to restore the deposit workflow promptly. We were also able to reach CNRI through established communication channels, and they responded out of hours to begin mitigation.</p>
<p>The incident also highlighted areas where we can improve our processes and resilience. In addition to <a href="https://doi.statuspage.io/incidents/f4cqcppc1q41" target="_blank">the changes made by CNRI</a> (more backend handle servers and tighter rate limiting), Crossref is taking the following actions:</p>
<ul>
<li>
<p>Knowledge sharing and documentation: Crossref, like all Registration Agencies, relies on the Handle System. We are reviewing the technical documentation describing how the Crossref system integrates with the Handle System, and we will continue working with CNRI to stay informed as the handle infrastructure evolves.</p>
</li>
<li>
<p>Improving handle session management: We are reviewing how our system manages handle sessions to explore how recovery could occur automatically after connection disruptions.</p>
</li>
<li>
<p>Submission rerun process improvements: We will review, clarify, and document the workflow for identifying and rerunning affected member submissions after disruptions to deposit processing.</p>
</li>
</ul>
<p>Reliable DOI resolution and deposit processing are central to the research ecosystem. We&rsquo;re committed to continuously improving the resilience of our systems and we will continue to learn from incidents like this one to strengthen them further.</p>
<p>If you have any questions, <a href="mailto:support@crossref.org">we are always happy to hear from you</a>.</p>
<p>You can stay informed about the status of our services by subscribing to updates at <a href="https://status.crossref.org/" target="_blank">status.crossref.org</a></p>
