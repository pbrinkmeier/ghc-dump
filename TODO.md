- [ ] Make ghc-dump-util work with 8.11
  - Blocked by: `regex-base-0.94.0.0`, which uses `!0` ("at index 0") in [Text.Regex.Base.Context][1], which makes GHC 8.11 error with "Bang pattern in expression context". Not sure if this is a GHC bug or if the `regex-base`maintainers are expected to fix that in future versions.
- [ ] Fix types marked with `-- TODO`

[1]: https://hackage.haskell.org/package/regex-base-0.94.0.0/docs/src/Text.Regex.Base.Context.html#line-302
