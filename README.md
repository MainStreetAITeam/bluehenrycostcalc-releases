# Blue Henry Cost Calculator — releases

Distribution channel for the Blue Henry Cost Calculator WordPress plugin.
Installed sites poll `manifest.json` for the latest version and download the
zip attached to the matching GitHub release; the update then appears on the
site's Plugins screen like any directory plugin.

The plugin is proprietary (© Main Street AI Team, built for Blue Henry LLC);
source lives in the private repository `MainStreetAITeam/bluehenrycostcalc`.
This repository exists only so WordPress can fetch updates without
credentials, and grants no license beyond running the plugin on Blue Henry's
sites.

Publishing a release: `build/publish-release.sh` in the source repository.
