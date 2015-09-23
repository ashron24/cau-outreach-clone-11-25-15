# cau-clergy
Draft multilayer Leaflet map with clergy, cbo, and demographic layers

This is a demo of an interactive web mapping application, utilizing leaflet, cartoDB, and a little JQuery. Data sets from NYC DCP (Bytes of the Big Apple), NYC DOT, OpenData, US Census Bureau and the MO-CAU. 

This is a draft version. Lots of kinks to be worked out.

#TODO:
1. Create a legend for layers that need them (i.e. choropleths). This legend needs to either be in a sidebar DIV element or in a popup.
  >>  a. Make the legend hide-able
  >>  b. Make the legend items "active" only when the corresponding layer is displayed.
2. Make hover-over interactivity (or info-window) for polygons and points. (preferably with D3-style info / box).
3. Move layer selector to a collapsible/minimizable sidebar.  (with a tab for instructions)
4. Add a secure log-in page.
5. Convert choropleth items to radio-button type of selector
6. Add nesting/ layer tree groups - style ala ArcGIS.
7. Add Map Title
<I>8. Rotate legend item lables.</i>
9. Fix layer selector to be compatible with mobile/touchscreen devices (scroll issue)

