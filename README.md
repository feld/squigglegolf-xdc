# Squigglegolf-xdc

This is a fork of [squigglegolf](https://github.com/natedonato/squigglegolf) by Nate Donato. The official version is hosted at https://squigglegolf.com

This is a fork which repackages the game as a [WebXDC](https://webxdc.org) application. The only notable changes are the removal of statistics reporting which make HTTP requests that are not permitted in WebXDC and the bundling of the webfonts that were being sourced from Google. A hole-in-one or a failure to complete a hole is reported as an event to the chat.
