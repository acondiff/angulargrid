angulargrid
===========

Pinterest like responsive masonry grid system for angular

##Features
<ul>
    <li>Complete responsive, figures out columns and width to completely fit the container based on options provided and container width.</li>
    <li>Animation support on enter or leave of grid items, sorting or resizing using ngAnimate module and css animation.</li>
    <li>Support any grid system (bootstrap, foundation) for number of columns, grid and gutter width.</li>
    <li>Perfect handeling of image load.</li>
    <li>Support left to right or right to left placement of grids.</li>
    <li>Keeps a watch on list model and options to reflect the changes instantly.</li>
</ul>

Demo url : http://ignitersworld.com/lab/angulargrid/index.html#demo

Documentation url : http://ignitersworld.com/lab/angulargrid/index.html#documentation

##Updates
Release 0.4.0 (Major Enhancements) :

1. Implemented #9
  - Support bootstrap or any grid system, enable cssGrid option to true, and then plugin will listen grid system (All items need to be of same grid style)

2. Implemented #10
  - Added direction option which handle direction of grid placement. Default to "ltor" .  You can also define "rtol" if you want grid to be placed from right to left.

3. Implemented #12, #13
  - Added gridNo option to define no of grids at a particular time . (If gridNo is defined plugin does not consider gridWidth option)
  - All options are now dynamic, which can be changed after initialization
  - Added angularGridOptions attribute so that options can be given as single object, or can be defined on controller.

4. Destroying instance and unbinding events on destroy of scope.
