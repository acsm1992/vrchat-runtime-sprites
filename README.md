# VRChat runtime sprites

Public delivery for the separate VRChat Sprite Injector service.
Only validated active sprites and display-name assignments belong here.
Never commit Discord identities, VRChat persistent IDs, credentials or private drafts.

The Pages workflow publishes catalog.json and slots/*.json as one deployment.
The retry workflow invokes the authenticated website publication worker.
GitHub may delay scheduled workflows; the website also attempts publication immediately.
Slots are stable per account; revisions increase when the active character changes.
Removing a catalog assignment does not erase Git history or downloaded copies.
