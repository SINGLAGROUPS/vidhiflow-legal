# vidhiflow-legal

Public legal pages for the Vidhiflow app, served by GitHub Pages at https://legal.vidhiflow.com (Compass #3102).

Rules (EM #48): static HTML/CSS only, no scripts, trackers or analytics; changes only by reviewed PR; policy text must be Legal-approved (#280) and approved by Mohit before it changes. Source of truth for the text: BCC artifact 007e990b (v1.0).

## Dangling-record rule (EM #48)
`legal.vidhiflow.com` is a DNS-only CNAME to `singlagroups.github.io`. **Delete that DNS record (bcc cf-dns-delete) BEFORE** turning off Pages, removing the `CNAME` file, or archiving this repo — never the other way round. A record left pointing at GitHub with no site claiming it can be taken over.
