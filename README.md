# local_auth

This is a fork of the [local_auth](https://github.com/flutter/plugins/tree/master/packages/local_auth)

There is an open [Pull Request](https://github.com/flutter/plugins/pull/2489) to merge into bases local_auth package.

Addresses issue: [https://github.com/flutter/flutter/issues/49703]

## Device credentails

The original plugin only supports biometric authentication. This package add a method that allows for device credentials if biometric authentication is not available.

`localAuth.authenticate()` behaves the same as the original plugin's `localAuth.authenticateWithBiometrics()` but also allows device credentials (pin, pattern, passcode) to be use.
