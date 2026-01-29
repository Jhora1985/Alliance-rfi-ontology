# Alliance-rfi-ontology

Document-scoped ontology derived from the GTS–Energration Alliance response to a DOE/NNSA Request for Information (RFI).

This ontology makes explicit the roles, offerings, capabilities, constraints, stakeholder perspectives, and authority boundaries stated in the response document, without inferring approval, delegation, or implementation details. All modeled statements are traceable to the document itself.

## Purpose

The goal of this ontology is to preserve meaning and governance intent when the RFI response is reviewed, reasoned over, or used by humans or automated systems. It distinguishes:
- what is offered versus what is merely possible,
- what actions are constrained by authority or conditions,
- and why constraints exist from different stakeholder perspectives.

## Scope

This ontology is intentionally limited to the contents of the GTS–Energration Alliance RFI response.
External RFIs, RFOs, site materials, or architectural assumptions are not asserted as truth and are used only as contextual education outside the model.

## Structure

- `ontology/rfi-core.ttl`  
  Core classes and properties for documents, claims, offerings, capabilities, constraints, stakeholders, perspectives, concept clusters, and uncertainty.

- `ontology/rfi-claims.ttl`  
  Document-scoped instances extracted from the RFI response, including stakeholders, perspectives, concerns, concept clusters, and initial claims.

- `ontology/rfi-shapes.ttl`  
  Lightweight SHACL guardrails to preserve truth and prevent over-interpretation.

- `notes/competency-questions.md`  
  Competency questions used to validate the usefulness of the ontology and guide future modeling.

## Design Principles

- Statements in the response are modeled as claims, not assumed facts.
- Authority is never inferred.
- Capabilities, constraints, and offerings are explicitly separated.
- Stakeholder perspectives explain why constraints exist.
- Concept clusters support reasoning without flattening semantics.

## Status

Early structural and semantic foundation complete.  
Claim extraction is intentionally incremental and guided by competency questions.
