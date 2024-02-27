# [Title]

> Status: [One of “Draft,” “Final,” “Accepted,” or “Rejected”]
> Author: [Your Name]
> Created: [...]

(NOTE: The following layout and sections are not mandatory, but highly recommended!)

## BLUF
_A BLUF (Bottom Line Up Front) statement is a concise opening that presents the conclusion or main point at the very start of a communication. Commonly used in military, business, and other areas where clear, quick communication is paramount, the BLUF format ensures that the essential message is understood immediately, without the need for the recipient to read through a lot of background information or explanatory details first. It is particularly effective in written communications such as emails and reports, where the key action, decision, or takeaway is delivered right at the beginning._

## Problem
_Often, your hardest task is identifying the problem clearly and specifically._

_Sometimes the “problem” arises from non-engineering concerns: “we need to implement this new feature” is a good trigger for an engineering design proposal. Sometimes you’re fixing a bug. Other times, it’s more vague to start with: “this system needs to scale” or “this user action is too slow.”_

_The goal of writing the problem statement is to focus on this problem instead of others that might be just to the side. It also pushes you to consider the properties of a good solution, which you must understand when you’re deciding what action to take._

## Background

_Think of this as the research section: How did we get here? Why do we need to act on this now? What’s contributing to the situation? Writing this section pushes you to discover constraints on the solution or requirements that might be lurking. Knowing why a current system behaves the way it does is handy when you’re evaluating a replacement for it._

_Writing this section is meant to help you understand the problem fully and describe it clearly enough that your colleagues can understand it too._

## Possible Solutions
_Is there more than one way to solve this problem? Probably! If you haven’t come up with more than one solution yet, try to do so now. Ponder the possibilities and pull apart their tradeoffs. The research work you did writing the background section sets you up to do this._

_The goal of writing this section is to shift you into thinking about what you’re going to do next._

## Proposed Solution

_Okay: now you drive a stake into the ground and have an opinion. What’s your proposal for solving the problem?_

_Answer these questions if you can:_
* _Why does this proposal meet the constraints better than other solutions?_
* _What are your solution’s requirements? These might range from the technical (“this will be a breaking change, so we’ll need to release a major version number bump”) to the human (“the support team will need a new tool to view this data”)._
* _What are the consequences of your choice?_
* _Which systems will need to change?_
* _Which systems will be replaced?_

_Go into as much detail as you can, given that you haven’t started implementation yet. By trying to answer these questions, you may conclude that you don’t know enough yet, and you need to do more research — and proposing to do more research is a perfectly reasonable proposal._

_Be prepared: this section will be the focus of your colleague’s commentary when they read it. Also, don’t be afraid to make a strawman proposal that you know will be replaced. Reacting to a strawman might be just what your team needs to inspire some new ideas._

## [Make the Request]

_A request for comment is not complete until you’ve requested the comments! Share your RFC with your colleagues and solicit their feedback. Post the RFC to Slack. Tag people whom you especially want feedback from, but the entire company is welcome to read and comment on RFCs. Your colleagues will have insights you don’t, on both the problem and your proposed solution. Use this feedback to revise your RFC as necessary and tune up your proposal. You might need to revise significantly and get another round of feedback, or you might be ready to start implementation work._
