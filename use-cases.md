Allowing to emulate real-world network conditions in a browser can help in a variety of situations.

# Mostly static network conditions
Most Web pages are loaded via a series of HTTP requests emitted when the page loads initially. In first approximation, the network conditions can be assumed to be fixed in such a context.

Emulating network conditions in such a context can be useful:
* to avoid regression in performance by controlling that a set of network-bound metrics don't deteriorate when the underlying Web app gets updated
* to optimize the behavior or a Web app expected to be used in specific places or specific network conditions
* to help debug unexpected behavior of a Web app (e.g. due to race conditions) in specific network conditions

# Dynamic network conditions
In a number of cases, a Web app will make regular and sometimes frequent requests to the network and will thus be directly impacted by fluctuations in network quality, as is particularly bound to happen in cases where the user is in a mobility scenario.

## Media Streaming

## Cloud gaming

## Real-time conferencing

## PWA Applications
