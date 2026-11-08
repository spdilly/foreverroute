# ForeverRoute

ForeverRoute is a personal addon and route-building project for World of Warcraft: Forever. Its leveling guide prioritizes solo quest routes and offers optional dungeon detours. It reads the character’s quest state and profession skills so a player can resume a guide partway through.

The project includes linked Cooking and Fishing routes, plus separate Tailoring, Mining, and First Aid guides. It uses map waypoints and can work alongside Shortest Path Forever, SkillUp Forever, Gathercraft, and Instance Journal Forever.

## ForeverDB integration

ForeverRoute uses a local Python review tool to compare the authored guide with WoW: Forever data. The initial audit covers recipe ingredients and skill thresholds, trainer and vendor sources, and quest locations. It labels Classic reference data separately from observations in Forever. Findings are reviewed before they are applied to the guide.

**Data from [ForeverDB.net](https://foreverdb.net).** API access is pending. The tool’s current spot checks use the public ForeverDB reference pages. The API key will stay local, outside the addon and repository. This public project page does not distribute API responses or third-party addons.
