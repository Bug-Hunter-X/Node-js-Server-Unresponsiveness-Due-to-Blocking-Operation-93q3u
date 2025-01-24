# Node.js Server Unresponsiveness

This repository demonstrates a common Node.js issue: server unresponsiveness caused by a long-running synchronous operation within the request handler.  The `bug.js` file contains the problematic code, which blocks the event loop. The `bugSolution.js` file provides a solution using asynchronous operations to prevent blocking.