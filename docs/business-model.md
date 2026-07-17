# Business Model: Roofing Crew Scheduling & Logistics Coordination Service

## Classification

- Repository: `cloud-itonami-isco-7121`
- ISCO-08: `7121`
- Occupation: Roofers
- Social impact: worker-safety, housing-durability, local-jobs

## Scope

**This actor coordinates job-site scheduling and logistics only.** It
never performs roofing work itself, never finalizes a
roofing-work-execution decision, and never overrides a site-safety
officer's fall-protection judgment. Roofers work at height on active
job sites — one of the highest fall-risk trades — so every proposal
this actor's advisor can make is limited to coordination, not
execution.

## Customer

- independent roofing contractors
- roofing crews and site foremen

## Offer

- work-record logging (task, materials usage, progress)
- crew/task scheduling proposals
- safety-concern surfacing (fall hazard, weather condition, crew fatigue)
- roofing-materials supply-order coordination

## Revenue

- monthly coordination-platform retainer
- per-site logistics fee

## Trust Controls

- no roofing-work-execution decision is ever finalized by this actor
- no site-safety officer's fall-protection judgment is ever overridden by this actor
- every safety-concern flag always escalates to human sign-off
- supply orders above the registered cost threshold always escalate to human sign-off
- job-site and crew-member provenance is independently verified before any coordination action
- coordination and audit records are auditable, not editable
