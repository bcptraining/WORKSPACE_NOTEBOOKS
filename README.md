# WORKSPACE_NOTEBOOKS

## Purpose

This repo is a **temporary backup** for Snowflake workspace notebooks (non-legacy) that cannot be saved to git-connected workspaces.

**Background:** Snowflake currently only supports *Legacy Notebooks* in git-connected workspaces. Standard workspace notebooks are stored separately in Snowsight and have no git integration. To avoid losing work when a trial account expires, notebooks are manually exported and saved here.

**Workflow:**
1. Export notebooks from Snowsight (Workspace > Notebooks) before a trial account ends.
2. Save them here for safekeeping.
3. When a new trial account is created, re-import the notebooks into the new Snowsight workspace.

**Long-term:** Once Snowflake adds git support for non-legacy notebooks, this repo will no longer be needed and notebooks can be saved directly to a git-connected workspace.

> Last updated: April 2026