# zt-attestation-pilot

Public pilot for GitHub artifact attestations (build provenance), tracked in autodesignlab/org-governance#363.

- Contains only a trivial demo script. No secrets, no business data, no infrastructure details.
- Purpose: verify that a CI build produces an attestation that can be checked with `gh attestation verify`.
- Cost: artifact attestations are supported for public repositories on all GitHub plans (per GitHub docs).
