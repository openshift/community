# OKD Working Group Charter

v1.1

2019-09-21 

https://github.com/openshift/community/pull/3
https://github.com/openshift/community/pull/44

## Introduction
The charter describes the operations of the OKD Working Group (OKD WG).

OKD is the Origin Community Distribution of Kubernetes that is upstream to Red Hat’s OpenShift Container Platform. It is built around a core of OCI containers and Kubernetes container cluster management. OKD is augmented by application lifecycle management functionality and DevOps tooling.

The OKD Working Group's purpose is to discuss, give guidance to, and enable collaboration on current development efforts for OKD, Kubernetes, and related CNCF projects. The OKD Working Group will also include the discussion of shared community goals for OKD 4 and beyond. Additionally, the Working Group will produce supporting materials and best practices for end-users and will provide guidance and coordination for CNCF projects working within the SIG's scope.

The OKD Working Group is independent of both Fedora and the Cloud Native Computing Foundation (CNCF). The OKD Working Group is a community sponsored by Red Hat.

## Mission
The mission of the OKD Working Group is:
* To collaborate on areas related to developing, deploying, managing, and operating OKD.
* To develop informational resources like guides, tutorials, and white papers to give the community an understanding of best practices, trade-offs, and value adds as it relates to developing, deploying, and managing applications in cloud native environments.
* To identify suitable projects and gaps in the ecosystem for future collaboration and coordination with those projects.

### Areas considered in Scope
The OKD Working Group focuses on the following end-user related topics of the lifecycle of cloud-native applications:
* Installation of OKD
* Integration with Fedora CoreOS. Other Linux distributions will be gated based on community interests and resource commitments and the establishment of Sub-Working Groups
* OKD delivery and release management
* OKD management and operations

The Working Group will work on developing best practices, fostering collaboration between related projects, and working on improving tool interoperability. Additionally, the Working Group will propose new initiatives and projects when capability gaps in the current ecosystem are defined.

The following, non-exhaustive, sample list of activities and deliverables are in-scope for the Working Group:
* Operator Centric Installer
* Definition and Documentation of requirements for running on Linux
* Identification of requirements
* Submission of code to upstream sources
* Development of Continuous Integration
* Education material to help provide guidance for the community
* Might include a summary of projects available in the community
* Definitions of implementations and patterns for best practices for delivering OKD
* Best practices for OKD management

### Areas considered out of Scope
Anything not explicitly considered in the scope above. Example include:
* Development of any Linux distribution or variant
* Initiation of new open source projects 
* Definition of standards for components like container images other infrastructure-level building blocks of cloud-native applications

## Governance

### Operations
The OKD Working Group is run and managed by the following chairs:
* Red Hat Community Development Liaison - Diane Mueller (Red Hat)
* External to Red Hat - Jaime Magiera (UMich)
* Red Hat Engineering Liaison - Vadim Rutkovsky (Red Hat)
* Fedora CoreOS Engineering Liason - Timothée Ravier (Red Hat)

Note: The referenced names and chair positions will be edited in-place as chairs are added, removed, or replaced. See the roles of chairs section for more information.

A dedicated git repository will be the authoritative archive for membership list, code, documentation, and decisions made. The repository, along with this charter, will be hosted at github.com/openshift/community.

The mailing list at groups.google.com/forum/#!forum/okd-wg will be used as a place to call for and publish group decisions, and to hold discussions in general.

### Working Group Membership
All active members of the Working Group are listed in the `MEMBERS.md` file with their name.

New members can apply for membership by creating an Issue or Pull Request on the repository on GitHub indicating their desire to join.

Membership can be surrendered by creating an Issue stating this desire, or by creating a Pull Request to remove the own name from the members list.

### Decision Process
This group will seek consensus decisions. After public discussion and consideration of different opinions, the Chair and/or Co-Chair will record a decision and summarize any objections.

All WG members who have joined the GitHub group at least 21 days prior to the vote are eligible to vote. This is to prevent people from rallying outside supporters for their desired outcome.

When the group comes to a decision in a meeting, the decision is tentative. Any group participant may object to a decision reached at a meeting within 7 days of publication of the decision on the GitHub Issue and/or mailing list. That decision must then be confirmed on the GitHub Issue via a Call for Agreement.

The Call for Agreement, when a decision is required, will be posted as a GitHub Issue or Pull Request and must be announced on the mailing list. It is an instrument to reach a time-bounded lazy consensus approval and requires a voting period of no less than 7 days to be defined (including a specific date and time in UTC).

Each Call for Agreement will be considered independently, except for elections of Chairs.

The Chairs will submit all Calls for Agreement that are not vague, unprofessional, off-topic, or lacking sufficient detail to determine what is being agreed.

In the event that a Call for Agreement falls under the delegated authority or within a chartered Sub-Working Group, the Call for Agreement must be passed through the Sub-Working Group before receiving Working Group consideration.

A Call for Agreement may require quorum of Chairs under the circumstances outlined in the Charter and Governing Documents section.

A Call for Agreement is mandatory when:
* A Chair determines that the topic requires a Call for Agreement.
* When petitioned by members of the Working Group and submitted to the Chairs to call a vote unless rejected for cause.
* Technical decisions that add, remove, or change dependencies and requirements.
* Revoke a previous decision made by the Call for Agreement process.
* Approval of a Sub-Working Group when such SWG has any delegated authority.

Once the Call for Agreement voting period has elapsed, all votes are counted, with at least a 51% majority of votes needed for consensus. A Chair will then declare the agreement “accepted” or “declined”, ending the Call for Agreement.

Once rejected, a Call for Agreement must be revised before re-submission for a subsequent vote. All rejected Calls for Agreement will be reported to the Working Group as rejected.

### Charter and Governing Documents

The Working Group may, from time to time, adopt or amend its Governing Documents and Charter, using a modified Call for Agreement process:
* A quorum of at least 51% of active Working Group Members must vote.
* A quorum of 3 Chairs is needed
* Two-thirds of the voting quorum must approve the proposal.
* A majority of Chairs must approve the proposal.
* A public notice period of no less than 14 days from the Call for Agreement proposing the change must elapse before voting begins.
* Any Call for Agreement that follows this process is considered a Governing Document. 

For initial approval of this Charter via Call for Agreement all members are eligible to vote, even those that have been a member for less than 21 days. This Charter will be approved if there is a majority of positive votes.

## Organizational Roles
### Role of Chairs
The primary role of Chairs is to run operations and the governance of the group. The Chairs are responsible for:
* Setting the agenda for meetings.
* Extending discussion via asynchronous communication to be inclusive of members who cannot attend a specific meeting time.
* Scheduling discussing of proposals that have been submitted.
* Asking for new proposals to be made to address an identified need.
* Oversee disciplinary action for members. The Chairs have the authority to declare a member inactive and expel members for cause.
* Chairs will serve for one-year revolving terms and will be approved using the [Condorcet Method](https://en.wikipedia.org/wiki/Condorcet_method). Upon the expiration of a Chair’s term, it will continue for another year, unless challenged.

The terms for founding Chairs start on the approval of this charter.

When no candidate has submitted their name for consideration, the current Chairs may appoint an acting Chair until a candidate comes forward.

Chairs must be active members. Any inactivity, disability, or ineligibility results in immediate removal.

Chairs may be removed by petition to the Working Group through the Call for Agreement process outlined above.

Additional Chairs may be added so long as the existing number of Chairs is odd. These Chairs are added using a Call for Agreement. Extra Chairs enjoy the same rights, responsibilities, and obligations of a Chartered Chair. Upon vacancy of an Extra Chair, it may be filled by appointment by the remaining Chairs, or a majority vote of the Working Group until the term naturally expires.

In the event that an even number of Chairs exist and vote situation arises, the Chairs will randomly select one chair to abstain. 

### Role of Sub-Working Groups 
Each Sub-Working Group (SWG) must have a Chair working as an active sponsor. Under the mandate of the Working Group, each SWG will have the autonomy to establish their own charter, membership rules, meeting times, and management processes. Each SWG will also have the authority to make in-scope decisions as delegated by the Working Group.

SWGs are required to submit their agreed Charter to the Working Group for information and archival. The Chairs can petition for dissolution of an inactive or hostile SWG by Call for Agreement. Once dissolved the SWG’s delegated Charter and outstanding authority to make decisions is immediately revoked. The Chairs may then take any required action to restrict access to Working Group Resources.

No SWG will have authority with regards to this Charter or other OKD Working Group Governing Documents.
