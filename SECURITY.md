# Security and data policy

These repositories contain research code. To report a security problem (for example, an exposed
credential or data that should not be public), do not open a public issue: contact the organization
owners listed in SUPPORT.md, or use GitHub's private vulnerability reporting if enabled.

Data rules
- Never commit SEER record-level data, SEER*Stat session exports below the disclosure threshold, data
  covered by a data use agreement, protected health information, or unpublished collaborator data.
- Commit only aggregated calibration targets that the data source allows to be shared, with provenance.
- Never commit credentials, API tokens, `.Renviron`, or `.env` files.
