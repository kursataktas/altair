# SimpleAuthorizationRequestParams

## Extends

- `Record`\<`string`, `string`\>

## Extended by

- [`CodeChallengeAuthorizationRequestParams`](CodeChallengeAuthorizationRequestParams.md)

## Properties

### client\_id

> **client\_id**: `string`

The client ID of your application

***

### redirect\_uri

> **redirect\_uri**: `string`

The URL in your app where users will be sent after authorization

***

### response\_type

> **response\_type**: `"code"`

***

### scope

> **scope**: `string`

A space-separated list of scopes

***

### state

> **state**: `string`

A random string generated by your application, which you'll verify later