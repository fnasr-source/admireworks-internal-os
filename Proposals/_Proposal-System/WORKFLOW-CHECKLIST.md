# Proposal Workflow Checklist

1. Create/update the client package under `Proposals/{Client-Folder}`.
2. Run proposal registration script to generate public ID and publish outgoing one-page URL.
3. Capture and store client contact details (email + phone) in the registry and package index.
4. Update package files with generated proposal number:
   - `00-Proposal-Index.md`
   - `06-Offer-and-Proposal.md`
   - `10-One-Page-Proposal.html`
   - client email in `communications/`
5. Add validity period (default: 7 days from sending date).
6. Confirm payment section by region:
   - Egypt: Instapay details
   - International: payment link
7. Keep client email short, with one-page proposal link and payment details.
8. Format email links as action hyperlinks:
   - `👉 [View Proposal](URL)`
   - `👉 [Open Payment Link](URL)` when needed.
9. Use outgoing URL format: `Proposals/_Outgoing/{PROPOSAL_NUMBER}/one-page.html`.
10. Push and share final outgoing URL.
