# Unresponsive Node.js Server with setTimeout

This repository demonstrates a common issue in Node.js servers where a long-running operation (simulated here with `setTimeout`) blocks the event loop, causing the server to become unresponsive to new requests. The server takes 5 seconds to respond. 

The solution showcases how to improve the responsiveness using techniques like asynchronous operations or separate worker threads to prevent blocking the event loop.