# Team Planner

Weekly capacity planning for one development team: what each MVP needs, who works on it, and when releases close.

## Planning

**Plan**:
The whole picture for the team: its people, releases, MVPs, assignments and leave.

**Week**:
A Monday-to-Friday column of the plan. This is the unit in which work is shown.

**Package**:
A group of one to five MVPs that together deliver one piece of functionality. It is identified by a key such as SRCH.
_Avoid_: Feature, epic, project

**MVP**:
A unit of deliverable work within a package, with its own dev phase, test phase, BAC, target release and due date. It is numbered within its package, as in SRCH-1, and it is not a whole product.
_Avoid_: Story, milestone

**BAC**:
An MVP's feature estimate in hours: one total covering both dev and test work.
_Avoid_: Estimate, budget

**Dev phase**:
The weeks in which developers work on an MVP. It is planned by hand, never derived from the BAC.

**Test phase**:
The weeks in which testers work on an MVP. It may overlap the dev phase freely, because individual stories can go to test early.

**Assignment**:
A team member working on an MVP for a range of weeks at a percentage of their capacity.

**Due date**:
The date by which an MVP must be done. By default it is the beta code stop of its target release. It can be set earlier, for example when another team depends on that MVP.
_Avoid_: Deadline

**Target release**:
The release an MVP is planned to ship in. It can be changed, for example when the MVP misses beta code stop.

## Releases

**Release**:
A delivery cycle of about six months that MVPs target. It is named after its release month, either April or October, as in 26.10 or 27.4. The next release starts at the current one's beta code stop.

**Milestone**:
A named date in a release, such as beta code stop or system test.

**Beta code stop**:
The milestone by which all feature work for a release must be finished.

**Final code stop**:
The milestone that closes a release. Between beta code stop and final code stop, the release only gets bug fixes, while developers may already work on MVPs for the next release.

**System test**:
A period of about four weeks that starts at each code stop.

## People

**Team member**:
A person on the team, with one fixed role.
_Avoid_: Resource, user

**Role**:
Either developer or tester. A team member never changes role.

**Capacity**:
The working days a team member has in a week: five, minus leave.

**Leave**:
Working days a team member is absent in a given week. Absences of three or more working days are flagged.
_Avoid_: Holiday, PTO, vacation

**Defect duty**:
Time explicitly set aside for a team member to fix or verify defects, for a range of weeks at a percentage.

**Load**:
The share of a team member's capacity in a week taken by their assignments and defect duty.

**Overbooked**:
A team member whose load in a week is over 100% of their capacity.

**Running out of work**:
A team member whose load drops below the plan's threshold (50% by default) in a week they are not on leave. It is flagged one week ahead.
_Avoid_: Idle, bench

**Spare capacity**:
Capacity not taken by load. A team member with spare capacity could pick up defects.
