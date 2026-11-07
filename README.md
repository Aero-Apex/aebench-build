# aebench-build

Public build runner for [AeBench](https://bench.aerobox.eu.cc). The source lives in a private
repository; this repo's workflow checks it out with a read token and builds the macOS (Apple Silicon)
and Windows x64 installers on GitHub's free public runners.

Downloads: https://bench.aerobox.eu.cc/#download

Run a build: Actions > Build release > Run workflow, enter the tag (for example `v1.0.0`).
