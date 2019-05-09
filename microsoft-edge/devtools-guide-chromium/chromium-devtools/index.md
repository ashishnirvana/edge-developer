---
title:
author:
ms.author:
ms.date: 05/09/2019
ms.topic:
ms.prod: microsoft-edge
keywords: microsoft edge, web developement, f12 tools, devtools
---





# Microsoft Edge DevTools 

With DevTools you can view and change any page. Even the Microsoft homepage, as the video
demonstrates.

## Open DevTools 

There are many ways to open DevTools, because different users want quick access to different
parts of the DevTools UI.

* When you want to work with the DOM or CSS, right-click an element on the page and select **Inspect**
  to jump into the **Elements** panel. Or press <kbd>Command</kbd>+<kbd>Option</kbd>+<kbd>C</kbd> (Mac) or
  <kbd>Control</kbd>+<kbd>Shift</kbd>+<kbd>C</kbd> (Windows, Linux, Microsoft Edge OS).
* When you want to see logged messages or run JavaScript, press <kbd>Command</kbd>+<kbd>Option</kbd>+<kbd>J</kbd>
  (Mac) or <kbd>Control</kbd>+<kbd>Shift</kbd>+<kbd>J</kbd> (Windows, Linux, Microsoft Edge OS) to
  jump straight into the **Console** panel.

See [Open Microsoft Edge DevTools](/microsoft-edge/devtools-guide-chromium/chromium-devtools/open) for more details and workflows.

## DevTools for Beginners 

DevTools for Beginners teaches you the **fundamentals of web development** as well as the basics of DevTools.
Check out [Get started](#get-started) below if you'd prefer tutorials that focus on DevTools.

* [Get Started with HTML and the DOM](/microsoft-edge/devtools-guide-chromium/chromium-devtools/beginners/html)
* [Get Started with CSS](/microsoft-edge/devtools-guide-chromium/chromium-devtools/beginners/css)

## Get started 

If you're a more experienced web developer, here are the recommended starting points for learning how
DevTools can improve your productivity:

* [View and Change the DOM](/microsoft-edge/devtools-guide-chromium/chromium-devtools/dom/)
* [View and Change a Page's Styles (CSS)](/microsoft-edge/devtools-guide-chromium/chromium-devtools/css/)
* [Debug JavaScript](/microsoft-edge/devtools-guide-chromium/chromium-devtools/javascript/)
* [View Messages and Run JavaScript in the Console](console/get-started)
* [Optimize Website Speed](/microsoft-edge/devtools-guide-chromium/chromium-devtools/speed/get-started)
* [Inspect Network Activity](/microsoft-edge/devtools-guide-chromium/chromium-devtools/network/)

## Discover DevTools 

The DevTools UI can be a little overwhelming... there are so many tabs! But, if you take some
time to get familiar with each tab to understand what's possible, you may discover that DevTools
can seriously boost your productivity.

Note: In the DevTools docs, the top-level tabs are called panels.

### Device Mode 

<img src="images/device-mode.msft.png" alt="Device Mode" class="attempt-right">

Simulate mobile devices.

* [Device Mode](/microsoft-edge/devtools-guide-chromium/chromium-devtools/device-mode/)
* [Test Responsive and Device-specific Viewports](/microsoft-edge/devtools-guide-chromium/chromium-devtools/device-mode/emulate-mobile-viewports)
* [Emulate Sensors: Geolocation &amp; Accelerometer](/microsoft-edge/devtools-guide-chromium/chromium-devtools/device-mode/device-input-and-sensors)

<div style="clear:both;"></div>

### Elements panel 

<img src="images/panels/elements.msft.png" alt="Elements Panel" class="attempt-right">

View and change the DOM and CSS.

* [Get Started With Viewing And Changing The DOM](/microsoft-edge/devtools-guide-chromium/chromium-devtools/dom/)
* [Get Started With Viewing And Changing CSS](/microsoft-edge/devtools-guide-chromium/chromium-devtools/css/)
* [Inspect and Tweak Your Pages](/microsoft-edge/devtools-guide-chromium/chromium-devtools/inspect-styles/)
* [Edit Styles](/microsoft-edge/devtools-guide-chromium/chromium-devtools/inspect-styles/edit-styles)
* [Edit the DOM](/microsoft-edge/devtools-guide-chromium/chromium-devtools/inspect-styles/edit-dom)
* [Inspect Animations](/microsoft-edge/devtools-guide-chromium/chromium-devtools/inspect-styles/animations)

<div style="clear:both;"></div>

### Console panel 

<img src="images/panels/console.msft.png" alt="Console Panel" class="attempt-right">

View messages and run JavaScript from the Console.

* [Get Started With The Console](/microsoft-edge/devtools-guide-chromium/chromium-devtools/console/get-started)
* [Using the Console](/microsoft-edge/devtools-guide-chromium/chromium-devtools/console/)
* [Interact from Command Line](/microsoft-edge/devtools-guide-chromium/chromium-devtools/console/command-line-reference)
* [Console API Reference](/microsoft-edge/devtools-guide-chromium/chromium-devtools/console/console-reference)

<div style="clear:both;"></div>

### Sources panel 

<img src="images/panels/sources.msft.png" alt="Sources Panel" class="attempt-right">

Debug JavaScript, persist changes made in DevTools across page reloads,
save and run snippets of JavaScript, and save changes that you make in DevTools to disk.

* [Get Started With Debugging JavaScript](/microsoft-edge/devtools-guide-chromium/chromium-devtools/javascript)
* [Pause Your Code With Breakpoints](/microsoft-edge/devtools-guide-chromium/chromium-devtools/javascript/breakpoints)
* [Save Changes to Disk with Workspaces](/web/tools/setup/setup-workflow)
* [Run Snippets Of Code From Any Page](/microsoft-edge/devtools-guide-chromium/chromium-devtools/snippets)
* [JavaScript Debugging Reference](/microsoft-edge/devtools-guide-chromium/chromium-devtools/javascript/reference)
* [Persist Changes Across Page Reloads with Local Overrides](/web/updates/2018/01/devtools#overrides)

<div style="clear:both;"></div>

### Network panel 

<img src="images/panels/network.msft.png" alt="Network Panel" class="attempt-right">

View and debug network activity.

* [Get Started](/microsoft-edge/devtools-guide-chromium/chromium-devtools/network-performance/)
* [Network Issues Guide](/microsoft-edge/devtools-guide-chromium/chromium-devtools/network-performance/issues)
* [Network Panel Reference](/microsoft-edge/devtools-guide-chromium/chromium-devtools/network-performance/reference)

<div style="clear:both;"></div>

### Performance panel 

Note: In Microsoft Edge 58 the Timeline panel was renamed to the Performance panel.

<img src="images/panels/performance.msft.png" alt="Timeline Panel" class="attempt-right">

Find ways to improve load and runtime performance.

* [Optimize Website Speed](/microsoft-edge/devtools-guide-chromium/chromium-devtools/speed/get-started)
* [Get Started With Analyzing Runtime Performance][runtimegs]
* [Performance Analysis Reference](/microsoft-edge/devtools-guide-chromium/chromium-devtools/evaluate-performance/reference)
* [Analyze runtime performance](/microsoft-edge/devtools-guide-chromium/chromium-devtools/rendering-tools/)
* [Diagnose Forced Synchronous Layouts](/microsoft-edge/devtools-guide-chromium/chromium-devtools/rendering-tools/forced-synchronous-layouts)

[runtimegs]: /microsoft-edge/devtools-guide-chromium/chromium-devtools/evaluate-performance/

<div style="clear:both;"></div>

### Memory panel 

Note: In Microsoft Edge 58 the Profiles panel was renamed to the Memory panel.

<img src="images/panels/memory.msft.png" alt="Profiles Panel" class="attempt-right">
Profile memory usage and track down leaks.

* [Fix Memory Problems](/microsoft-edge/devtools-guide-chromium/chromium-devtools/memory-problems/)
* [JavaScript CPU Profiler](/microsoft-edge/devtools-guide-chromium/chromium-devtools/rendering-tools/js-execution)

<div style="clear:both;"></div>

### Application panel 

<img src="images/panels/application.msft.png" alt="Application Panel" class="attempt-right">

Inspect all resources that are loaded, including IndexedDB or Web SQL databases, local and
session storage, cookies, Application Cache, images, fonts, and stylesheets.

* [Debug Progressive Web Apps](/microsoft-edge/devtools-guide-chromium/chromium-devtools/progressive-web-apps)
* [Inspect and Manage Storage, Databases, and Caches](/microsoft-edge/devtools-guide-chromium/chromium-devtools/manage-data/local-storage)
* [Inspect and Delete Cookies](/microsoft-edge/devtools-guide-chromium/chromium-devtools/manage-data/cookies)
* [Inspect Resources](/microsoft-edge/devtools-guide-chromium/chromium-devtools/manage-data/page-resources)

<div style="clear:both;"></div>

### Security panel 

<img src="images/panels/security.msft.png" alt="Security Panel" class="attempt-right">

Debug mixed content issues, certificate problems, and more.

* [Understand Security Issues](/microsoft-edge/devtools-guide-chromium/chromium-devtools/security)

<div style="clear:both;"></div>

## Community 

<style>
  .cdt-but {
    display: inline-block;
  }
</style>

The best place to file feature requests for Microsoft Edge DevTools is the mailing list.
The team needs to understand use cases, gauge community interest, and discuss
feasibility before implementing any new features.



File bug reports in Crbug, which is the engineering team's bug tracker.

If you want to alert us to a bug or feature request but don't have much time,
you're welcome to send a tweet to @EdgeDevTools. We reply and send
announcements from the account regularly.

<a class="button button-primary gc-analytics-event"
   data-category="DevTools" data-label="Home / Twitter"
   href="https://twitter.com/EdgeDevTools">Twitter</a>

For help with using DevTools, Stack Overflow is the best channel.
