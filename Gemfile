source "https://rubygems.org"
gemspec
gem "webrick", "~> 1.7"

## Explicitly pin sass-embedded to a pre-3.0 version
## This stops deprecation warnings for @import in hydeout.scss. 
##  TODO: Eventually the website will need updating to work with latest versions though.
##  Affected functions `@import`, `lighten()`, and `darken()`
gem "sass-embedded", "< 3.0"
