---
title: Dev stuff
created: '2019-10-08T06:18:12.646Z'
modified: '2019-10-09T08:20:47.378Z'
---

# Dev stuff

### Sylvains animation tipps:

start with Illustrator, export the «finished» illustration in svg, then I cleanup manually the svg within a text editor. You could then revert your animation and do a «explosion», start with the regrouped state and move then each part randomly. And finally revert the whole animation.
That means that your pieces in the final regrouped state have all ‘transform’ set to 0 (xy values are defined in illustrator). You can then set manually random ‘transform’ values for the initial exploded state

Yep. And another advice: Try to play only with ‘transform’ values (translate, rotate, scale) or opacity. Avoid transitions on margins, top or left or padding

## vue review adrien

inital page load: 
- inital watcher shouldnt trigger request!!!
- is logging in state -> while it is active do not request data!
- data loading by initial user loading!
- instead of language watcher use a side effect in dispatch!
- when more than 1x component need the same data then initialize their data in the top level component, self contained components ONLY when they need it alone!!!!!!
- if you need data on screen initialy then you can use beforeRouteEnter in vue router, with an await you can defer the routing until loaded!
- when an action is needed on multiple locations then you MUST be sure that the side effects are needed on multiple locations, multiple commits in one action are ok and also synchron but other async dispatches are dangerous!!!
- if you have multiple loadings and want one state then you can use a counter, if you are done in then or catch you can go loading --, on request you can do loading ++ 
- when you got a new component always start with component state, only go into store if you really really really need it on one more place !!!!
- prefix services and models and (store)modules, you can then search in files like "searchstring" in *.service.js
- always use mapactions, mapgetters, mapstate, never this.$store.dispatch crap
- always use vuex router with sync(store, router, {moduleName: "Router"}) so you always have the router state everywhere
