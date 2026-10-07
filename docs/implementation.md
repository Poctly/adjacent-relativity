# Applying and evaluating Adjacent Relativity

“Implementation” here means a repeatable interpretive workflow and data model. No working application is included in version 0.1.

## Workflow

1. **Choose a target relationship.** State the ambiguity before selecting an analogy.
2. **Identify its evidence.** Record the specific narrative, language, edition, cultural setting, and uncertainty.
3. **Represent its structure.** List nodes, typed relations, episode, layer, and temporal roles.
4. **Propose a process reading.** Mark whose interpretation it is and what it explains.
5. **Choose an adjacent system.** Explain why the comparison fits more than a generic theme.
6. **Map relations explicitly.** Record both preserved and mismatched properties.
7. **Generate a new expectation.** Identify another passage or case not used to create the mapping.
8. **Compare alternatives.** Include straightforward genealogy, regional variation, political adaptation, ritual practice, and historical development.
9. **Record the outcome.** Retain failed mappings; revise or reject a reading when evidence warrants it.

## Worked starter cases

| Case | Target relationship | Proposed adjacent comparison | What must be investigated |
|---|---|---|---|
| AR-01 | Mixcoatl as generative figure and as member of a later group | Recurring role versus individual iteration | Whether the actual accounts distinguish those levels |
| AR-02 | Father versus Brother status across divine appearances | Precedence within an episode versus parallel roles at another level | Whether this explains more than conflating separate narratives |
| AR-03 | Black/Red/Mixcoatl aspect change | Same system with changed conditions or relational position | Exact transformation wording and the independent tilt claim |
| AR-04 | Itzpapalotl to flint or sacred bundle | Transformation retaining effective or ritual potency | Differences among the flint and ashes narratives |
| AR-05 | Calendar Round and New Fire | Boundary marking and renewed traversal | Ritual meanings beyond simple repetition |
| AR-06 | Mythic establishment versus subsequent Suns | Initiating mechanism versus later iterations | Whether sources actually distinguish those temporal roles |
| AR-07 | Conversation altered by framing | Context changes available responses | Concrete examples and limits of the physical analogy |

These are candidate case studies, not findings that the method is validated.

## Data specification

The CSV uses:

| Field | Meaning |
|---|---|
| id | Stable claim or relation identifier |
| subject | Agent, figure, process, or concept |
| relation | Typed relationship; never an unlabeled arrow |
| object | Target of the relationship |
| layers | Semicolon-separated layer tags |
| context | Narrative, community, or domain; unknown if unspecified |
| evidence_status | One of the repository's labels |
| provenance | Source ID or participant/assistant discussion attribution |
| note | Qualification or required verification |

Future versions should split claims, sources, entities, and interpretations into separate linked tables. Add instance IDs, episode IDs, temporal-role fields, passage locations, date ranges, and conflicting-edge references. Preserve original spelling alongside normalized names. A collective is not interchangeable with an individual deity.

## Evaluation criteria

Evaluate each mapping for specificity, preservation of relationship types, handling of counterexamples, consistency across new cases, and dependence on selective source choices. Do not report a numerical truth score without a defensible scoring method.

A useful test is to choose new cases before fitting the mapping. Compare interpretations on the same evidence and identify what would favor each one. If every mismatch can be dismissed as another hidden “level,” the framework becomes unfalsifiable. Require evidence for a proposed level change.

Positive outcomes may include clearer explanation, fewer unjustified identity collapses, or testable expectations about an additional passage. None alone proves the original authors intended the mapping.

## Practical next implementation

Maintain Markdown case studies and CSV claims first. Later, a graph viewer could filter by source, region, layer, relation type, and evidence status. It should show parallel and conflicting edges, expose provenance, and keep interpretive edges distinguishable from historical ones. A separate comparison view could display a proposed adjacent mapping and its failures.

Do not combine this repository with the Yang–Mills experiment by implying that the lore validates a physical mass-gap hypothesis. If a later cross-project comparison is proposed, document it as a separate analogy with its own evidence requirements.
