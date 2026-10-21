# Deriv Boom & Crash Signal Provider V1
Signal-only interface based on the uploaded Boom and Crash Signal Provider master project.
Visible interface is narrowed to Boom and Crash markets only. Target instruments: Boom/Crash 300, 500, 600, 900 and 1000, subject to availability on the Deriv account.
No automatic order execution is intended in this build.
Important: the existing analysis engine was preserved rather than rewritten. Its signal timeframe/strategy logic has not been fully converted to the planned M1 entries + M5 trend confirmation, and spike detection is not a guaranteed prediction system. Test live data connection and signal behavior on a demo account before relying on signals.
