# iOS devices logs

See branch `master_chapko_minidatashifttest`

Expected output (captured from desktop tests):

```
2017-03-16 17:48:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'

2017-03-16 17:48:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-16 17:48:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-16 17:48:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-03-16 17:48:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-03-16 17:48:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-16 17:48:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-16 17:48:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-16 17:48:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'

2017-03-16 17:48:12 - DEBUG UnitTest_app: 'My device name is: '520f7285-9c5c-423f-aa7f-2ec64126e304''
2017-03-16 17:48:12 - WARN testUtils: 'myNameCallback not set!'

2017-03-16 17:48:13 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'

2017-03-16 17:48:13 - INFO testLoader: 'loading file: /Users/eugene.chapko/Workspace/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'

2017-03-16 17:48:13 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.2.1:3000/'

2017-03-16 17:48:13 - DEBUG CoordinatedClient: 'connected to the test server'

TAP version 13

# setup

# Can shift data

2017-03-16 17:48:13 - DEBUG thaliWifiInfrastructure: 'listening 58801'

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'

2017-03-16 17:48:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-16 17:48:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'

2017-03-16 17:48:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'

2017-03-16 17:48:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'

Native connection established. Peer: { peerIdentifier: '34950e33-83f3-4f3b-9a3b-a221672ce4c2',
  peerAvailable: true,
  generation: 0 }

Connecting to the 58804 port on localhost

Connected to the 58804 port on localhost

Client sends data (20 bytes): <small amount of data>

Client data flushed

2017-03-16 17:48:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'

2017-03-16 17:48:13 - DEBUG wifiBasedNativeMock: 'Got error while disconnecting a peer: null'

ok 1 got the same data back

# teardown

2017-03-16 17:48:13 - DEBUG wifiBasedNativeMock: 'received incoming socket - for peerID Incoming connection relay'

Server received (20 bytes): <small amount of data>

Server received all data: <small amount of data>
Server sends data back to client (20 bytes): <small amount of data>
Server data flushed
Server's socket stream finished

2017-03-16 17:48:13 - DEBUG wifiBasedNativeMock: 'outgoingSocket ended  - for peerID Incoming connection relay'

2017-03-16 17:48:13 - DEBUG wifiBasedNativeMock: 'outgoingSocket closed  - for peerID Incoming connection relay'

2017-03-16 17:48:13 - DEBUG wifiBasedNativeMock: 'incomingSocket closed  - for peerID Incoming connection relay'

2017-03-16 17:48:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-16 17:48:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-16 17:48:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 2 Should be able to call stopListeningForAdvertisements in teardown
2017-03-16 17:48:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'

2017-03-16 17:48:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'

2017-03-16 17:48:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'

ok 3 Should be able to call stopAdvertisingAndListening in teardown

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'

2017-03-16 17:48:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# setup

# Can shift data securely

2017-03-16 17:48:13 - DEBUG thaliWifiInfrastructure: 'listening 58818'

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-16 17:48:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-16 17:48:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'

2017-03-16 17:48:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'

2017-03-16 17:48:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-16 17:48:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'

Native connection established. Peer: { peerIdentifier: '46c4085e-a40c-4834-9d3a-b9a6bdaff6a3',
  peerAvailable: true,
  generation: 0 }
Connecting to the 58824 port on localhost

TLS socket sends 116 bytes

TLS socket received 75 bytes

TLS socket sends 177 bytes

Connected to the 58824 port on localhost

TLS socket received 266 bytes

Client sends data (20 bytes): <small amount of data>

TLS socket sends 69 bytes

Client data flushed

TLS socket received 122 bytes

ok 4 got the same data back

# teardown

2017-03-16 17:48:14 - DEBUG wifiBasedNativeMock: 'got an end on peerProxySockets'

2017-03-16 17:48:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'

2017-03-16 17:48:14 - DEBUG wifiBasedNativeMock: 'Got error while disconnecting a peer: null'

2017-03-16 17:48:14 - DEBUG wifiBasedNativeMock: 'received incoming socket - for peerID Incoming connection relay'

Server received psk id: psk-id

Server received (20 bytes): <small amount of data>

Server received all data: <small amount of data>

Server sends data back to client (20 bytes): <small amount of data>

Server data flushed

Server's socket stream finished

2017-03-16 17:48:14 - DEBUG wifiBasedNativeMock: 'outgoingSocket ended  - for peerID Incoming connection relay'

2017-03-16 17:48:14 - DEBUG wifiBasedNativeMock: 'outgoingSocket closed  - for peerID Incoming connection relay'

2017-03-16 17:48:14 - DEBUG wifiBasedNativeMock: 'incomingSocket closed  - for peerID Incoming connection relay'

2017-03-16 17:48:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'

2017-03-16 17:48:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'

2017-03-16 17:48:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'

2017-03-16 17:48:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'

ok 5 Should be able to call stopListeningForAdvertisements in teardown

2017-03-16 17:48:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'

2017-03-16 17:48:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'

2017-03-16 17:48:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'

2017-03-16 17:48:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'

ok 6 Should be able to call stopAdvertisingAndListening in teardown

2017-03-16 17:48:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
2017-03-16 17:48:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
2017-03-16 17:48:14 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'android''
2017-03-16 17:48:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-16 17:48:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-16 17:48:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
2017-03-16 17:48:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"on","cellular":"on","bssidName":"c1:5b:05:5a:41:1e","ssidName":"myWifi"}'
2017-03-16 17:48:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-03-16 17:48:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'

2017-03-16 17:48:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-16 17:48:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'

2017-03-16 17:48:14 - DEBUG CoordinatedClient: 'all tests completed'

2017-03-16 17:48:14 - DEBUG CoordinatedClient: 'test client disconnected'
2017-03-16 17:48:14 - DEBUG CoordinatedClient: 'test client succeed'
2017-03-16 17:48:14 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-03-16 17:48:14 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2017-03-16 17:48:14 - INFO runTests: 'Finished'



1..6
# tests 6
# pass  6


# ok



Exit code: 0. Exit signal: null
```
