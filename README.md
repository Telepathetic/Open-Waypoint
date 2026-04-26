# Open Waypoint — System Architecture

*CC BY-SA 4.0*

-----

## What It Is

An open source conversational mental health support framework, evaluated on disengagement. Success is measured by users needing it less over time, not more. Designed to run offline or airgapped. Conversation data stays on device. Research partners interface with the person, not the data.

## What It Isn’t

Therapy. Diagnosis. A replacement for human care. A companion.

-----

## Core Architecture

Two models in conversation before any response reaches the user.

### Model A — The Conversation Model

Handles the actual therapeutic dialogue. Fine-tuned on CBT/DBT frameworks, trauma-informed communication, and motivational interviewing. Trained to actively build capacity in the user rather than dependency on the system. Explicitly prompted to notice and name attachment patterns — including attachment to itself.

### Model B — The Safety/Integrity Checker

Reviews Model A’s output before delivery. Flags sycophancy, over-validation, harmful advice, scope creep beyond competence, and language that increases rather than decreases dependency. Only clean responses reach the user.

-----

## The Disengagement Metric

The novel research contribution. Defines what healthy graduation looks like vs. dropout vs. crisis.

The core measurement problem — whether a person stopped because the tool worked or because it didn’t — is unsolvable from inside the app alone. Designed around needing collaboration with clinical partners with IRB capacity for longitudinal follow-up. This is the thing universities publish papers on.

-----

## Versioning

Hosted on HuggingFace. Each university research partner forks, tunes, evaluates against the disengagement benchmark, and publishes results. The framework evolves from evidence, not from engagement metrics.

-----

## Licensing

CC BY-SA 4.0. Model weights, framework, and evaluation suite: open.
