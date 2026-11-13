# Healthcare Encounter Reconciliation

A healthcare operations project using MySQL and Retool to identify unmatched encounters and make follow-up work easier to track.

## Analysis
- Checked **6,612 distinct valid EHR encounters**.
- Matched records using patient, service date and provider.
- Identified **282 unmatched encounters (4.26%)**.
- Built reconciliation KPIs, provider and monthly views, and a searchable follow-up queue.

An unmatched record is a reconciliation exception requiring review; it does not by itself prove lost revenue or an unsubmitted claim.

## Repository contents
| File | Purpose |
| --- | --- |
| [encounter-reconciliation-dashboard.zip](encounter-reconciliation-dashboard.zip) | Exported dashboard package |
| [healthcare-reconciliation-report.pdf](healthcare-reconciliation-report.pdf) | Thought process, findings and solution |
| [project-brief.pdf](project-brief.pdf) | Original project brief |

## Review the project
1. Start with the report to understand matching rules and assumptions.
2. Inspect the dashboard export locally.
3. Import supported app files into your Retool workspace and configure your own MySQL resource.
4. Check that the input schema and matching rules reproduce the stated denominator before comparing results.

The ZIP is an export, not a publicly hosted dashboard. Resource connections and credentials must be configured separately.

## Skills demonstrated
SQL joins and aggregations, data cleaning, record reconciliation, exception analysis, dashboard design and stakeholder communication.

**Author:** Rudra Joyti Maitra Soham
