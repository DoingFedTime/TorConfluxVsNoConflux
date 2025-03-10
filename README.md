# Conflux Tor Network Visualization

A cyberpunk-styled interactive visualization demonstrating how Conflux multipath routing technology can double the speed of the Tor network.

[![Conflux Tor Network Visualization](https://i.ibb.co/ynwXXzCq/yt.png)](https://www.youtube.com/watch?v=obD8vN7kDnI)

## Overview

This visualization provides a side-by-side comparison between standard Tor routing and Conflux-optimized routing, showing how multipath connections can significantly improve performance while maintaining the same security guarantees.

### What is Conflux?

Conflux is a multipath onion routing technique that enables the Tor network to utilize multiple circuits simultaneously for a single connection. Unlike standard Tor that sends all traffic through a single 3-relay path, Conflux splits traffic across multiple paths and combines them at the exit relay, effectively doubling throughput.

## Features

- **Animated Traffic Flow**: Visualizes data packets moving through both standard and Conflux Tor paths
- **Performance Metrics**: Compares speed, page load times, file download times, and network capacity
- **Technical Accuracy**: Correctly represents how Conflux maintains the 3-hop security model while using dual circuits
- **Responsive Design**: Works on desktop and mobile browsers
- **Educational Tool**: Helps users understand the benefits of multipath routing for anonymity networks


## Usage

Simply open the HTML file in any modern web browser to view the visualization. No additional dependencies or installation required.

```bash
# Clone this repository
git clone https://github.com/DoingFedTime/conflux-visualization.git

# Open the HTML file in your browser
open index.html  # or double-click the file