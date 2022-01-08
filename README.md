# Accessible Bootstrap 5 Menubar
A modified version of the Bootstrap 5 dropdown JavaScript and CSS that allows for the creation of an accessible menubar with nested dropdown menus. Entire menubar is keyboard accessible according to W3's navigation menubar example: https://www.w3.org/TR/wai-aria-practices/examples/menubar/menubar-1/menubar-1.html

# Features and Bugfixes
* Top-level dropdowns can be navigated through with the left and right arrows or tab keys.
* Top-level dropdowns are opened with spacebar, down arrow, or enter key. First item in dropdown is selected automatically.
* Dropdowns can be navigated with up and down arrows or tab key and selection wraps from beginning to end / end to beginning.
* Sub-dropdowns can be opened with right arrow, spacebar, or enter key. First item in sub-dropdown is selected automatically.
* Dropdowns and sub-dropdowns can be closed with the left arrow or escape key. Only the currently open dropdown or sub-dropdown will close (will not bubble up to all parents and * close everything). The item that opened that dropdown is selected automatically.
* Dropdown and sub-dropdown links can be opened with spacebar or enter key and closes entire menubar.
* Only one dropdown can be open at a time in a menubar.
* Fixed a bug where the spacebar didn't open dropdown items (dropdown.js line 39).
