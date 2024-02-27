# Use RFCs

Status: Draft
Author: Beau Albiston
Created: Nov 1, 2023

## BLUF

I'm firmly of the belief that rallying our scientists and engineers behind a unified vision requires a tool more impactful than individual tech specs, fuzzy PRDs, or misguided sprints of work. That tool is the RFC (Requests for Comments). Writing an RFC demonstrates you have thought enough about a problem to devise a working solution that is not rash, but also admittedly, not perfect. RFCs are so much more than technical prose. They are context, history, rationale and consensus all at once.

Unfortunately, there is a reluctance to embrace RFCs, often due to their perceived clunky user experience. Many jump immediately to the “convenience” of collaboration tools and the simplicity of diagrams. While these tools are great for quick comments and visibility, they often lack the gravitas and permanence of an RFC. The artifacts these tools produce can be fleeting, and typically fail to capture the full depth of our science and engineering discussions.

One of the unsung benefits of writing an RFC is seeing how others interpret your ideas. It's a revealing and often enlightening process that sharpens our communication skills. After all, to truly win a scientist’s or engineer’s heart, speaking their language—clear, logical, and structured—is key.

Regardless of what you think about the concept of RFCs, our team requires a robust, yet lightweight document management strategy to prevent further knowledge loss and inefficiency. Implementing a Request for Comments (RFC) process will address this need by structuring collaboration, decision-making, and information retention in one place.

## Problem

Navigating the complexities of a distributed work environment can pose significant challenges, particularly when it comes to collaboration and execution. In a landscape where teams are geographically scattered, fostering effective collaboration can be a formidable task. Companies with distributed teams often encounter hurdles in maintaining a consistent approach to processes and decision-making. Crucial decisions and the underpinning logic behind them can become obscured over time, giving rise to repetitive discussions or confusion. Tracking the genesis and evolution of decisions can be daunting, and as organizations scale, the decision-making process can grow cumbersome and lose its agility. There's a pressing need to empower team members to explore innovative ideas and contribute fresh perspectives.

The absence of a structured documentation system is a silent adversary in the battle against information attrition. When documents are disorganized, critical information becomes as elusive as a whisper in the wind, and knowledge that should be readily accessible slips through the cracks of collective memory. Over time, this disarray leads to a subtle yet insidious form of information loss—where insights, decisions, and historical data fade into obscurity. Teams find themselves retreading old ground, not because the knowledge was absent, but because it was entombed within the chaos of an unstructured document landscape. This not only leads to inefficient use of time and resources as efforts are duplicated and decisions are delayed but also erodes the foundational understanding that drives informed decision-making and innovation.

Disagreements are a natural part of any organization’s dynamics. Uncovering such conflicts late in the development cycle, such as after software deployment, can lead to exorbitant costs. These disputes can breed frustration among all parties involved and potentially disrupt the harmony of the collaborative culture within the project. A typical scenario where such disagreements come to light is when a change request (pull request) remains unresolved for an extended period because the author and the project maintainers fundamentally disagree on the necessity of the proposed change.

While acknowledging their utility, it's crucial to recognize that RFCs (Requests for Comments) are not a panacea for all collaborative woes, especially if there are underlying dysfunctions. They are a tool, and their effectiveness largely depends on how they are utilized. It's essential to understand that RFCs are not mere “requests for permission,” nor are they an open invitation to “reinvent the wheel.” They should be perceived as a proactive inquiry: “Here’s the path we envision taking – have we overlooked anything?” This approach should be aligned with and guided by a clear product or technological roadmap. The overarching aim of RFCs is to foster participation and ensure transparency across the organization, enabling a cohesive and informed decision-making process.

## Background

### Summary

This document serves as a formal proposal advocating the integration of RFCs (Requests for Comments) into our organizational workflow. The RFC system, with its proven track record, has been the cornerstone of several eminent open-source groups for decades, including but not limited to Linux and Git. Furthermore, it has garnered widespread adoption among numerous high-performing distributed companies such as Google and GitLab. The RFC framework offers a structured and methodical approach to managing ideas and ensuring meticulous documentation.

Requests for Comments (RFCs) are formalized documents that serve as a pivotal tool for collaborative decision-making, particularly in the realms of science, software development and network engineering. They act as both a blueprint and a forum for proposing, detailing, and discussing potential changes or new features within a system. RFCs facilitate an open and transparent dialogue among team members, inviting diverse input to meticulously vet ideas, ensuring that every aspect of a proposal is scrutinized and refined before implementation. This process not only aids in building consensus but also serves as a vital archive for the reasoning behind decisions, preserving the institutional memory and guiding future endeavors.

It’s important to emphasize that not every idea, decision or change warrants an RFC. Overuse of this tool can potentially hinder the agility and responsiveness of a company. However, given the transformative potential of implementing RFCs in our workflow, it's fitting that this very proposal be presented as an RFC. This approach allows us to thoroughly elucidate the rationale and reasoning behind this suggestion. It will enable us to collectively examine the benefits and potential challenges, ensuring that our decision is informed, transparent, and aligned with our organizational goals.

The essence of this proposal is to cultivate an environment where careful consideration, cooperative engagement, and perpetual enhancement are the cornerstones, all the while maintaining a steadfast stance against the inevitable tide of disorder. We seek to establish a culture where every voice contributes to a symphony of deliberate progress, where collaboration isn't just a buzzword, but the very fabric of our daily operations, and where the drive for improvement is relentless and unfazed by the chaos that growth often brings. This is our bulwark against entropy, ensuring that as we evolve, we do so with intention and collective wisdom.

### Rationale

RFCs, as a strategic framework, offer a more robust solution than establishing an “Architecture Council” or “Leadership Group” (LG). The impulse to form these groups often arises from the inability to forge consensus on critical topics. However, these “group meetings” can devolve into sessions of semantic debates, frequently culminating in indecisiveness regarding proposed changes within the domain. A prevalent issue with “group meetings” is their occasional myopia; they may lack a comprehensive view or miss the intricate subtleties of science and engineering domains. Without appropriately diverse representation to address the multifaceted needs of these domains, making well-rounded decisions becomes a challenging endeavor.

In contrast, RFCs inherently drive towards decisive outcomes with every RFC mandating a decision, by empowering all stakeholders to contribute feedback. This inclusive approach ensures diverse perspectives are considered, leading to more informed and balanced decisions. Moreover, the asynchronous nature of handling RFCs circumvents the logistical complexities associated with organizing regular meetings, enhancing efficiency and participation.

Furthermore, RFCs provide a more encompassing solution compared to Architecture Decision Records (ADRs) and “whydocs.” While ADRs and “whydocs” are effective in documenting decisions made during the software development phase, they fall short in encapsulating the genesis of ideas and intentions. Understanding the rationale behind not pursuing certain paths is as crucial as knowing the reasons for the chosen directions. This calls for a process that not only records decisions but also captures the broader context, including rejected ideas and alternative paths considered. RFCs fill this gap by providing a platform for a thorough deliberation of all aspects, including potential and discarded options.

In essence, RFCs foster a culture of transparency and accountability. They provide a clear, traceable record of how and why decisions are made, which is invaluable for future reference and continuous learning. By democratizing the decision-making process, RFCs encourage a sense of ownership and engagement among team members, leading to higher levels of motivation and satisfaction.

### Relation to Agile Scrum

An RFC, or Request for Comments, is a structured approach to soliciting feedback and consensus for proposed changes before they transition into actionable items. In the context of Agile Scrum, an RFC can be a critical precursor that informs the creation of Epics—large chunks of work that encompasses many smaller, more manageable tasks (BLIs).

Utilizing RFCs in the planning phase of Epics and BLIs ensures that all aspects of the proposed idea, or change have already been carefully considered and documented. Simply put, RFCs should be used in the formulation of Epics and BLIs. The collaborative nature of the RFC process means that input from various stakeholders is used to refine the proposal, ensuring that it is robust, viable, and aligns with the organization's goals. This early-stage consensus-building and risk assessment contribute to a well-defined scope and clear objectives for the Epic, providing the team with a comprehensive understanding of what needs to be accomplished and why.

Moreover, an RFC can provide an initial technical design or architecture, crucial for guiding the Epic’s implementation. It lays the groundwork for transparency, allowing team members to appreciate the context of their work fully. The result is an Epic that is not only well-planned concerning objectives, risks, and resources but also one that carries the team’s agreement and understanding, ensuring smoother execution and a greater likelihood of successful delivery.

## Solution

Please see README for details on the RFC workflow, and [RFC Template] for insights on the content of an RFC.
