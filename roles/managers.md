# 👩‍⚖️ Managers

Manager is an advanced role in Aura. Managers evaluate Trainers in the same way Trainers evaluate Players and Players evaluate Subjects.

A Manager uses evidence by looking at a Trainer's [activity](../evidence/activity.md), meaning the evaluations a Trainer has made, and also how other Managers have [evaluated](../evidence/evaluations.md) the Trainer.\
\
Managers can also evaluate other Managers in the same way they evaluate Trainers. [Team owners](teams.md) are the first Managers for a [team](teams.md).

{% content-ref url="teams.md" %}
[teams.md](teams.md)
{% endcontent-ref %}

## Manager Scores

When Managers in a [team](teams.md) evaluate each other, scores in the Manager role are generated using a [SybilRank algorithm](https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final42_2.pdf) adapted for a directed graph with weighted edges.&#x20;
