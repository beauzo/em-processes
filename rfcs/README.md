# RFC README

(The following is for reference purposes only)

At the heart of our distributed organization, we recognize the importance of managing both historical and forthcoming changes in a structured yet dynamic manner. This is where the Request for Comments (RFC) system becomes pivotal. It doesn’t just facilitate decision-making; it chronicles the evolution of our company's technology and intellectual journey. Please see Use RFCs for a more detailed rationale.

We firmly believe in fostering an open and transparent dialogue among all team members. In line with this belief, we have wholeheartedly adopted the RFC system for several reasons:

* __Inclusivity__: Any member of our company, regardless of their role or seniority, is empowered to initiate a Request for Comment. This inclusivity ensures a diverse range of perspectives and ideas.
* __Timeliness Over Perfection__: We prioritize the timely submission of RFCs over perfection. It’s more important to get the conversation started and ideas flowing than to wait for a flawless proposal.
* __Non-authoritative Nature__: RFCs are not set in stone. They represent ideas and proposals, not final decisions. What ultimately defines our direction is the code and implementations that follow.
* __Scope of Changes__: While most alterations, including bug fixes and documentation enhancements, can be processed through the usual GitHub pull request workflow, we acknowledge that some changes are more substantial. These significant changes warrant a more detailed design process to foster consensus and a shared understanding among the team.
* __Consistency and Control__: The RFC process provides a uniform and regulated pathway for introducing new features or major changes. This system ensures that all stakeholders are informed and confident about the system's evolution.

By integrating the RFC process into our workflow, we’re not just managing changes; we’re weaving the narrative of our technological growth and collective intellectual progress. It's a testament to our commitment to open dialogue, innovation, and collaborative growth.

## When is the Right Time to Write an RFC?
You should consider initiating the RFC process when you have an idea of significance to share, or you're looking at making substantial alterations to our system, architecture, codebase, or procedures. The definition of "substantial" can vary, but generally, it includes:

* Modifications to vital components or dependencies within the system
* Revisions to system-wide schemas or structures
* Overhauls or major changes to key processes
* Enhancements that unequivocally improve measurable quality aspects like performance, error handling, or platform compatibility

On the flip side, here are some scenarios where an RFC might not be necessary:

* Minor tweaks such as rephrasing, reorganizing, or refactoring that don’t materially alter the functionality or meaning
* Changes that are primarily internal and wouldn’t directly impact the end users of our product

## Navigating the RFC Process
To bring a major feature or change to fruition, the first step is crafting an RFC. Once you create and pen down your RFC in our Shared Google Drive (specifically within the "RFCs" folder), it's considered "active" and you can start working towards its potential implementation.

Here’s a step-by-step guide to navigate the process:
* __Start Your Draft__: Create a draft document in the `<rfcs-repository>` under the Text folder (see below). Choose a descriptive title for the document and list the authors at the top. The document file name should be the same as the “descriptive title.”
NOTE: If you have an existing document in another location that you want to promote to an RFC, please feel free to move it into the `<rfcs-repository>`.
* __Detail Your Proposal__: Invest time in detailing your RFC. It should convincingly explain the motivation, understand the broader impact, and be transparent about potential drawbacks or alternatives. Well-thought-out RFCs generally receive a better response. Please use the [RFC Template](./rfc_template.md) as a guide.
* __Related Code? Create a Branch__: If your RFC involves “prototype code,” please create a branch named `rfc/<rfc_number>` and submit a draft pull request. This is where you’ll receive design feedback, so be ready to make revisions.
* __Build Consensus and Integrate Feedback__: RFCs with broad support are more likely to succeed. Engage with the team to gather input and overcome potential obstacles.
* __Expect and Embrace Changes__: It's rare for an RFC to pass through without modifications. As feedback comes in, make adjustments—both small and significant.
* __Request for Final Disposition__: Once the feedback loop seems settled, announce a "request for final disposition" to the entire team.
* __Gather Final Responses__: Each team member should provide their final stance on the RFC – whether to accept, reject, request additional information, or abstain. Authors also have the option to withdraw their RFC if needed. The document will be moved to the appropriate subfolder based on its final disposition.

Remember, RFCs are a collaborative tool. They thrive on open communication, detailed consideration, and collective wisdom. Let's use them to make well-rounded, informed decisions together.
