[O3 Framework](../API.md) / getSafeRedirectUrl

# Function: getSafeRedirectUrl()

> **getSafeRedirectUrl**(`url`): `null` \| `string`

Defined in: [packages/framework/esm-api/src/openmrs-fetch.ts:49](https://github.com/omeriinnocent/openmrs-esm-core/blob/main/packages/framework/esm-api/src/openmrs-fetch.ts#L49)

Returns the URL only if it is safe (same-origin or a relative path).
This prevents open redirect attacks where a server-supplied Location header
could redirect users to a malicious external site.

## Parameters

### url

The URL to validate.

`null` | `string`

## Returns

`null` \| `string`

The URL if it is safe, otherwise null.
