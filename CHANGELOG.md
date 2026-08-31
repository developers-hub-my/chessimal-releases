# Changelog

Release notes for the published Chessimal desktop builds. Versions match the application's
`pubspec.yaml` version.

<!-- Newest first. Each release links to its assets on the Releases page. -->

## [0.2.7] — 2026-08-31

**Added** — an optional player account. Guest play stays the primary path: puzzles, lessons,
the journal, Chessimals and cosmetics are all uncapped without one. What an account buys is
engine levels 4 to 8.

- Google Sign-In and email sit side by side with equal weight. A player under 13 cannot hold a
  Google account — Family Link supervised accounts cannot grant OAuth consent — so a Google-only
  wall would lock out the app's primary user.
- Engine levels above 3 stay **visible** and greyed with a lock and a reason, never hidden: a
  child should be able to see the ladder they are climbing. Tapping a locked rung opens the
  account screen, worded as an invitation.

[0.2.7]: https://github.com/developers-hub-my/chessimal-releases/releases/tag/v0.2.7
