# iOS devices logs (in WiFi-only mode)

## "2017-02-09T12:48:54Z" folder

Logs in the 2017-02-09T12:48:54Z folder are from `iOS_chapko_1771` branch but
ThaliReplicationPeerAction.MAX_IDLE_PERIOD_SECONDS is set to 30 seconds.


## "comparable" folder

"comparable" folder contains other modifications:
- testThaliManagerCooridinated.js test runs twice - at the beginning and at the
end
- ForeverAgent's maxSockets in thaliPeerPoolDefault is set to `Infinity`

I included start.log and end.log which contain only timing from the first and last
thali manager coordinated tests for easier comparison
