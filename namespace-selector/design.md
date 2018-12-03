# Namespace Selector

The goal of this component to allow users quickly filter and see entities inside a namespace or several namespaces.

## On which pages this selector is relevant
The namespace component should be at the top of each page where applicable.
1. Graph, services, workloads, applications, Istio Config pages
2. Overview page - will have NO selector as each card indicates a namespace anyway.
3. Tracing page - TBD

## Component behavior
1. The namespaces list should always be in alphabetical order, no re-sorting of namespaces based on selected/unselected to prevent things moving a lot on the screen.
2. A checkbox is the selected design (not the +-) to select/unselect namespace
3. "Clear all" option should be implemented ("Select all" should NOT)
4. Auto complete by typing namespace names at the top of the component - so users can more easily locate the namespaces without scrolling. (stretch goal, not a must for first phase)
5. Default value when entering the pages for the first time - no namespace is selected, users will get an indication that they have to select something.
6. Indication what is selected when the selector is closed/collapsed:
When one namespace is selected, its name will appear at the selector top when selector is closed for better visibility. When more than one namespace is selected, then it will appear as "X namespaces" where X is the num of selected namespaces without their names.
7. Saving namespace selection when navigating between pages is a must
8. Saving namespace selection per user as a cookie for a repeating login reuse (stretch goal)
