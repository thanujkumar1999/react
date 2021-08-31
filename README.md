We're seeing this in Sentry, too.

OS: Windows 10
Browser: Edge 18.18362
React 16.11.0 (from yarn.lock)

AFAICT it happens before the user did anything; here's the stack trace:

  at Lj(../node_modules/react-dom/cjs/react-dom.production.min.js:5382:1)
  at Anonymous function(../node_modules/react-dom/cjs/react-dom.production.min.js:2829:1)
  at t.unstable_runWithPriority(../node_modules/scheduler/cjs/scheduler.production.min.js:266:1)
  at fg(../node_modules/react-dom/cjs/react-dom.production.min.js:2794:1)
  at ig(../node_modules/react-dom/cjs/react-dom.production.min.js:2824:1)
  at Y(../node_modules/scheduler/cjs/scheduler.production.min.js:203:1)
  at A.port1.onmessage(../node_modules/scheduler/cjs/scheduler.production.min.js:94:1)```
