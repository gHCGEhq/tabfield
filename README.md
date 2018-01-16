# Desired Task

View [Fund Alert _ Testbed.htm](https://ghcgehq.github.io/tabfield/Fund%20Alert%20_%20RMC%20Testbed.htm) in a desktop browser. It should be identical to [this screenshot](https://ghcgehq.github.io/tabfield/Screen%20Shot%202018-01-15.png).

There are three components to this task. Please submit your solution as a pull request to this repository, by only adding css definitions to the file [css_Va4zLdYXDM0x79wYfYIi_RSorpNS_xtrTcNUqq0psQA.css](https://ghcgehq.github.io/tabfield/Fund%20Alert%20_%20RMC%20Testbed_files/css_Va4zLdYXDM0x79wYfYIi_RSorpNS_xtrTcNUqq0psQA.css) and possibly making minor changes to the html in [Fund Alert _ Testbed.htm](https://ghcgehq.github.io/tabfield/Fund%20Alert%20_%20RMC%20Testbed.htm). Your solution must be compatible with desktop browsers in [this matrix](https://developer.mozilla.org/en-US/docs/Web/CSS/animation#Browser_compatibility).

First, make the initial view of the page match [this screenshot](https://ghcgehq.github.io/tabfield/Desired%20Initial.png). Specifically:
1. The grey background of the left sidebar extends to the bottom of the browser window
1. The "Edit", "Delete", and "Devel" tabs are visually hidden
1. The bottom of the tab-menu component has rounded corners matching its top edges
1. The "Ridgeleigh Management Company" menu appears roughly 30 px below the bottom of the tab-menu component
1. There is no grey horizontal line between the tab-menu component and the "Ridgeleigh Management Company" menu

Second, after a user clicks the "•••" button in the tab-menu component, the page should match [this screenshot](https://ghcgehq.github.io/tabfield/Desired%20Expanded.png).
1. The "Edit", "Delete", and "Devel" tabs are visible and have pushed the "Ridgeleigh Management Company" menu down the page (no overlap)
1. The bottom edges of the "View" & "•••" elements are now square, and the bottom edges of the last tab-menu item ("Devel") has rounded corners

Third, using CSS animation, clicking the "•••" button will "open" the tab-menu component similar to the way that submenu items are revealed upon clicking "Ridgeleigh Management Company". It is not required to replicate the rubber-band/snapback effect of the "Ridgeleigh Management Company" menu, as long as it appears to drop down from the initial tab-menu component.
