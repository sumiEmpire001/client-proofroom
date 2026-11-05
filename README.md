# Client Proofroom

A responsive design proof review demonstration in HTML, CSS and JavaScript. Add proof entries, approve them, request changes with comments, and create new revisions. Each revision resets approval status and increments the version number.

## Run

Start `python -m http.server 8000` and open http://localhost:8000.

## Tests

Requires Node.js 18+. Run `npm test` for eight tests. GitHub Actions runs tests on pull requests.

## Scope

This is a browser-only workflow demonstration, not a secure client portal. No image upload, client login, shared storage, or immutable approval history is provided. All records live in localStorage on one device.
