# Namespace Overview

## Summary
The namespace overview would give a high-level summary of the health of the services in each namespace.

![card view of namespaces](img/namespace-cards.png)

### Namespace Cards
- **Title:** Displays the name of the namespace. May wrap to a second line if necessary.
- **Service Count:** The total number of services in the namespace.
- **Status Counts:** Shows the number of services with each status. Icons should only be shown for a given status if there are services in the namespace that have that status.


### Card interactions
- Clicking on a card links to a view of the services list filtered by the relevant namespace
- Clicking on a status count links to a view of the services with that status in the selected namespace
- Hovering over a status count displays a tooltip with a list of the names of services with that status.
  - If more than 6 services with a given status exist, the tooltip should show the names of the first 5 followed by the message "and # more..." to describe the total number
