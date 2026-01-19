# 👥 Teams

## Teams

Having multiple teams provides resilience to Aura.  If one team becomes flawed, other teams can continue to operate with minimal disruption to [providing evaluations to apps](../intro/how-aura-works.md#expert-evaluations).

### Creation and management

[Sybil defenders](https://en.wikipedia.org/wiki/Sybil_attack) can create a team after paying a fee and selecting at least one owner.

Team owners can add or remove other owners with a 2/3 majority vote.

### Scores & Levels

Each team generates scores for its participants independently from other teams. Scores come from participants evaluating each other.

Team owners can define team levels for Subjects, Players, Trainers, and Managers based on scores and other requirements such as receiving evaluations of a certain confidence or from participants with a certain level.

Team scores and levels are combined to create [aggregate scores and levels.](teams.md#aggregate-scores-and-levels)

### Managers

Team owners become the first managers and can begin evaluating each other and other managers and trainers.&#x20;

### Team Membership

Managers and Trainers are responsible for deciding which Aura participants belong to which teams. A Manager or Trainer can choose to add a participant they evaluate to any of the teams they belong to themselves. They evaluate a participant only once per role, but the evaluation will contribute to a score for the participant in each of the teams they've chosen to include.

## Aggregate scores and levels

Most of the time participants will only see one score which is an aggregate of several team scores.

Apps should rely on a mix of team scores to compute an overall score and level for each subject. This provides resilience, allowing Aura to be useful even if one or more teams have become unreliable.\
\
[This article](https://paragraph.com/@adamstallard/decentralizing-brightid-with-collective-intelligence) describes how crowd wisdom through [Updraft](https://www.updraft.fund/) can find the right mix of scores to combine from each team to provide an overall score for subjects and participants.

