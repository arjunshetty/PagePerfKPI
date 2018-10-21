Plugin to analyze the current page metrics via windows timing API - requests by type, domain, load times, marks and more 

### Navigation Timing Waterfall

![alt text](https://raw.githubusercontent.com/micmro/resourceTable/gh-pages/readme-assets/perfbook-navigation-timing-waterfall.png "screenshot of navigation timing API waterfall output of bookmarklet on http://walmart.ca/en")

- It also displays markers and measures if you're setting marks with the [User Timing API](http://www.w3.org/TR/user-timing) (`performance.mark` and `performance.measure`)
- Hover over the bars to see a tooltip with the excact Milliseconds/duration

<figure>
  <figcaption><strong>Navigation Timing API Details</strong></figcaption>
  <br/><br/>
  <a href="https://raw.githubusercontent.com/micmro/resourceTable/gh-pages/readme-assets/navigation-timing-overview.svg"><img src="https://raw.githubusercontent.com/micmro/resourceTable/gh-pages/readme-assets/navigation-timing-overview.png" alt="Diagram of the Navigation Timing API as seen on W3C site" /></a>
</figure>

### Resource Timing Waterfall with Markers

![alt text](https://raw.githubusercontent.com/micmro/resourceTable/gh-pages/readme-assets/perfbook-resources-timing-waterfall.png "screenshot of resource timing API waterfall output of bookmarklet on http://stylify.me")

- The small bars inside the resource bar represent the different stages of the request (redirect, domainLookup, connect, secureConnect, requestToResponseStart, response), but are mostly unavailable for cross-domain requests.
- The resource bar colours indicates the initiatorType
- You can filter the waterfall chart by domain

<figure>
  <figcaption><strong>Resource Timing API Details</strong></figcaption>
  <br/><br/>
  <a href="https://raw.githubusercontent.com/micmro/resourceTable/gh-pages/readme-assets/resource-timing-overview.svg"><img src="https://raw.githubusercontent.com/micmro/resourceTable/gh-pages/readme-assets/resource-timing-overview.png" alt="Diagram of the Resource Timing API as seen on W3C site" /></a>
</figure>
