TODO: Intro

## New Features!

### Category: Title (#533)

Description of feature.

**Docs**: [Title](http://k6.readme.io/docs/TODO)

## Bugs fixed!

* Cloud: Fixed the cloud metrics output to read only `projectID`, `name` and `token` from the `env.loadimpact` map in the exported script `options`. (#848)
* JS: Fixed a Babel transformation issue that caused closing brackets to sometimes be commented out. (#853)
* JS: Fixed environment variable propagation when executing script bundles. (#853)
* HAR converter: Fixed a panic due to a missing nil check (#861)
* Cloud: Limit the amount of samples that k6 sends in a single package to the ingest by splitting them up. (#860)
* Metrics: Fix the incorrect tracing of some corner case HTTP requests (#862)
