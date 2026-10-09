# CATMAYOR Real Civic Reserve Episodes v3.1

This repository hosts the participant-safe release for **CATMAYOR — Two-Stage Civic Reserve Control**. Download `CATMAYOR_Participant_Data_v3_1.zip` from the [v3.1.0 release](https://github.com/anjalikhatri019-hub/catmayor-feline-civic-reserve-dataset/releases/tag/v3.1.0). Earlier releases have superseded prepared-data contracts.

The ZIP contains `train.csv` (457 distinct weekly anchors), `test.csv` (the same 94 held-out anchors as v3.0), `train_targets.csv`, `sample_submission.csv`, a dataset description, README, and license. The contest submission is a complete two-stage reserve-control policy (`case_id,policy_json`), with all continuation branches committed in advance. Branches are alternative actions within an anchor, not additional training examples. Training targets include recorded training replays; private held-out replays are excluded. Data derive from public-domain Austin animal-center and 311 records; original transformations are CC0 1.0 Universal.

The underlying source-event rows, exact held-out dates, private answers, and organizer-only preparation/provenance are intentionally absent from this participant release. The benchmark is retrospective: reserve allocations are hypothetical and are not measured effects on animal welfare. See the included dataset description for units, limitations, and generalization risks.
