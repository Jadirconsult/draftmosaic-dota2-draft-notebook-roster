# Verification plan — Dota 2

Status: NOT RUN. There is no executable implementation to test.

## Module acceptance criteria

### 1. Draft scenario sheets

- [ ] Define a versioned input fixture specifically for draft scenario sheets.
- [ ] Document the expected output and units before implementation.
- [ ] Test valid, missing, malformed, and unsupported-version inputs.
- [ ] Repeat with the same fixture and compare results.
- [ ] Confirm that source files and unrelated settings remain unchanged.

### 2. Role coverage matrix

- [ ] Define a versioned input fixture specifically for role coverage matrix.
- [ ] Document the expected output and units before implementation.
- [ ] Test valid, missing, malformed, and unsupported-version inputs.
- [ ] Repeat with the same fixture and compare results.
- [ ] Confirm that source files and unrelated settings remain unchanged.

### 3. Patch-tagged matchup notes

- [ ] Define a versioned input fixture specifically for patch-tagged matchup notes.
- [ ] Document the expected output and units before implementation.
- [ ] Test valid, missing, malformed, and unsupported-version inputs.
- [ ] Repeat with the same fixture and compare results.
- [ ] Confirm that source files and unrelated settings remain unchanged.

## Release gate

- [ ] Implement the proposed modules and add automated tests.
- [ ] Record exact tested versions; leave untested versions marked unknown.
- [ ] Verify backups and restoration where state changes are supported.
- [ ] Review privacy, permissions, and product rules.
- [ ] Publish source and reproducible build instructions before claiming a working release.
- [ ] Do not present the retained external resource as a verified download.

## Scope

Manual entry and user-authorized post-session data only. No game memory reading, hidden opponent information, automated input, or game client modification.
