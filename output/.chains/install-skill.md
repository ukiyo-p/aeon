The dry run found one installable skill: `deploy-site` from the Cohesivity pack. Its security scan passed, and it declares `external_api`, `writes_external_host`, and `sends_notifications` capabilities.

I couldn’t proceed with installation because creating the required branch failed: Git could not write under `.git`. The workspace also has pre-existing changes (`CLAUDE.md` deleted; `notify`, `notify-jsonrender`, and `secretcurl` untracked), which I left untouched. No skill files or PR were created.
