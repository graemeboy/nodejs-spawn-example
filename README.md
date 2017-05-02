## Using spawn and communicating between processes in Node

Based on this article: https://medium.com/@graeme_boy/how-to-optimize-cpu-intensive-work-in-node-js-cdc09099ed41

This repo shows how to communicate between two running processes in Node.js.

The point of doing this is generally to prevent blocking the event loop with long-running processes - instead these get spawned as child processes.
