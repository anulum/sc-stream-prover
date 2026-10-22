<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-STREAM-PROVER — repository foundation
-->

# Decision: separate arithmetic checking from circuits and source certification

## Context

A valid bitstream file, passing randomness battery or matching formula does not establish an arithmetic experiment's source law, bound applicability or numerical correctness. Stateful circuits and selector dependence require source-specific independent checks.

## Decision

SC Stream Prover owns arithmetic experiments, independent oracles, finite analysis, applicable inference, tested-length decisions and native reports. SC-NeuroCore retains circuit implementations and counterpart parity. Randomness Witness retains source batteries and certificates; Loop Timing Witness retains capture and timebase. Evidence Manifest Toolkit supplies shared evidence operations and Experiment Ledger supplies generic storage. Consumers use existing admitted reports.

## Consequences

Repository tooling can be qualified before domain execution exists. It does not qualify absent numerical models or physical capture. Whole populations, current source qualification, independently justified methods, full failures and genuine consumer behaviour are prerequisites for domain support. No copied circuit, common evidence implementation or additional service is needed.
