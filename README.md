#evilgooglesearch
####Sometimes, searching the internet isn't as easy as it seems.

#### LEVEL 1 TODO:
- Evil Search functionality:
	- Tab access keeps sliding away from search bar element
	- 'Search' button click from nav shelf doesn't work (how is TBD)
	- evil script prevents me from moving mouse onto search bar directly


- ~~Integrate Live Chat: https://barbariangroup.atlassian.net/browse/MIGR-24~~ (basic implementation)
- ~~jQuery 1.7.2 implemented~~
- ~~Populate subnav image content (KS)~~
	- ~~Clean up Kyle's dummy nav images~~
- ~~Fix nav arrows~~
- ~~Integrate Header Search~~
- ~~Integrate Footer Search~~
- ~~Integrate Tablet / Mobile Non-Predictive Search~~
- ~~Integrate Shopping Cart~~
	- ~~Cleanup Cart Styles / Code~~
- ~~Integrate Login~~
	- ~~Funcitonality cleanup~~
	- ~~Integrate mobile login~~
- ~~Integrate Cookies~~
- ~~Concat / Minify JS~~
- ~~Social / Share shelf~~ (seems to be working)
- Investigate Rich Relevance Issue
- ~~Existing page implementation example~~
- ~~Dynamic Breadcrumbs~~
- ~~Consolidate 1900+ Bower Components~~
- ~~Update icons~~
- ~~Update subnav images~~
- /us/scripts/jquery.js will need to be updated to v1.7.2 (this seems to be what aboutsamsung is leveraging)
	- QA aboutsamsung to make sure that this upgrade does not break anything
- explicitly state font sizes (ongoing)
- Hover Intent

#### LEVELS
Level 1: User must perform a Google search, but when user attempts to move mouse into box, an evil script bounces the mouse away.

If user tries to tab to the search box, evil script pushes the tab index elsewhere

Level 2: Huzzah!  User finally searched.  But now the DOM crumbles and falls to the bottom of the screen.
User must build a tower from the DOM pieces at least [x] high.
	- x = 600 pixels, or 12 DOM elements stacked on one another

### OTHER NOTES

##### Action.js 