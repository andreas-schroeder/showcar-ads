
2.1.1 / 2016-08-02
==================

  * destroy ad-slot when ad-slot tracking element is detached - needed for dynamic loading on list page

2.1.0 / 2016-08-01
==================

  * Also refreshing targeting on refresh event
  * googletag is not a function anymore
  * Updated documentation
  * Added logging to test refresh event
  * wrapped slot refresh call in googletag cmd queue
  * Added event for refresh ad slots
  * Removed console log statements
  * Removed timeout inserted between creating ad container and display
  * removed no-defer attribute
  * Removed head element from fragment to allow putting it in various position
  * Put some additional delay testing if issue with unfindable container elements is solved
  * Additional logic for debugging purposes
  * Added timeout after appending container div to fix issue occuring where its not available
  * Removed additional logging for debugging
  * Additional logging for debugging
  * Adapted slotRenderEnded callback to be more general
  * Added callback event for slotRenderEndet when element-id is specified
  * updated changelog

2.0.0 / 2016-07-27
==================

  * Breaking change: slot-id is now called ad-unit

1.0.5 / 2016-07-19
==================

  * updated documentation
  * Removed log messages to help integrating showcar ads in home project.
  * Added log messages to help integrating showcar ads in home project.
  * Added features section in documentation.
  * Merge branch 'release/v1.0.4' into develop
  * Release v1.0.4
  * Made check for resolution range check more readable.
  * added additional stuff to documentation

1.0.4 / 2016-07-05
==================

  * Made check for resolution range check more readable.
  * added additional stuff to documentation

1.0.3 / 2016-07-05
==================

  * added documentation
  * Updated list.html with resolution range sample.
  * Clean up logging code. Added specs for resolution ranges.
  * Parse resolution range array...
  * Added more log info for resolution range debugging
  * Added log info for resolution range debugging
  * Added support for resolution ranges.
  * Catch case where ad container not available and output warning.
  * Added interval for defining ad slot
  * Removed artificial delay for defining/displaying slots
  * Added logging for further investigation
  * Increased the delay to check if it affects the problem behaviour
  * Added small delay between creating div container and definiting slot.
  * incorporated se timeout to avoid googletag not finding div containers.
  * Additional attribute css class for possibility of styling container elements
  * Set display none when ad not rendered cause of resolution restriction
  * Removed console log
  * switched from setting inner HTML to appendChild
  * check if ad container element is available on define slot
  * added ads prefix to fragment variables
  * supporting eleemnt ids in slot definitions
  * Merge branch 'release/v1.0.2' into develop
