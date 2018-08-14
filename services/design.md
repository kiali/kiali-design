# Services

## Metrics

![service metrics page](img/service-metrics.png)
- Service metrics charts are grouped by the metric that they represent and displayed next to one another.
- Chart legends are not visible in the non-expanded state, but are visible by hovering over the graph.
- Adding the option to show different percentiles into the settings dropdown would effectively enable people to replicate the hiding and showing feature of the legend for every graph at once rather than one at a time.
- Charts should be displayed at a fixed height, but if this is not possible/practical both charts in each pair should have the same height.

![alternative service metrics page](img/service-metrics-alt.png)
- Alternatively, charts could be grouped into cards by the metric that they represent. In this case, they would exhibit the same behaviors described above.

![expanded metrics chart](img/service-metrics-expanded.png)
- Clicking the `expand` action on a given chart expands it to the full with of the page and displays the chart legend.
- The `collapse` action returns the user to the full list of charts. Leaving the page and returning should also display the full list.
- Clicking on items in the legend would hide and show individual lines on the graph.
