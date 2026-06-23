# Episode Version History

Version history should help creators compare meaningful episode changes without exposing low-level file revisions.

## User Goal

A creator should be able to return to an earlier edit state, compare major creative decisions, and understand what changed before exporting or sending a review copy.

## Version Events

Capture creator-meaningful events:

- preset applied
- brand kit changed
- canvas layout saved
- template applied
- caption review completed
- b-roll moments approved
- review copy created
- export readiness warnings resolved
- metadata updated

Avoid showing every automatic render, autosave, or background processing step as a main version.

## Comparison

Creators should be able to compare:

- layout changes
- caption style changes
- approved versus rejected b-roll
- metadata changes
- template changes
- export warning changes

The comparison should use visual preview where possible.

## Workflow Connections

Version history should summarize visible decisions from the workflows that already own them:

- preset and brand changes from `docs/preset-style-picker.md` Preset Cards and `docs/show-brand-kit-setup.md` Reuse
- template application and divergence from `docs/show-template-adaptation.md` Adaptation Flow and Versioning
- caption and spelling fixes from `docs/audio-caption-quality-review.md` Review Flow and `docs/transcript-glossary.md` Application
- review-copy and reviewer decisions from `docs/client-review-copy-flow.md` Resolution States and `docs/review-handoff-summary.md` Review States
- metadata and export decisions from `docs/episode-metadata-publishing.md` Readiness Checks, `docs/publish-checklist.md` Status, and `docs/export-package-handoff.md` Summary

History entries should describe creator-visible outcomes rather than internal render IDs, autosaves, or background jobs.

## Restore Behavior

Restoring a version should explain what will change:

- current episode only
- linked template
- brand kit
- metadata
- review comments

The product should protect final exports and client-approved states from accidental overwrites.

## Restore Checks

Before restoring a version, show whether the restore will:

- reopen resolved export warnings or checklist items
- remove newer review-copy decisions or reviewer notes
- roll back metadata, thumbnail, or sponsor disclosure changes
- change only the current episode or also affect linked template reuse
- replace approved visual moments, captions, or brand choices that collaborators already saw

Restoring should stay reversible and should warn when the selected version predates a final export or client approval state.

## Maintainer Acceptance Notes

Accept work that makes meaningful episode decisions recoverable and understandable. Close work that shows raw autosave logs, treats exports as editable versions, or makes template changes ambiguous.
