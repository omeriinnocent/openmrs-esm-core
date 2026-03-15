[O3 Framework](../API.md) / getSafeRedirectUrl

# Function: getSafeRedirectUrl()

> **getSafeRedirectUrl**(`url`): `null` \| `string`

Defined in: [packages/framework/esm-api/src/openmrs-fetch.ts:48](https://github.com/omeriinnocent/openmrs-esm-core/blob/main/packages/framework/esm-api/src/openmrs-fetch.ts#L48)

Returns the URL only if it is same-origin (to prevent open redirect attacks).
Returns null for cross-origin or invalid URLs.

## Parameters

### url

The URL to validate.

`null` | `string`

## Returns

`null` \| `string`

The URL if it is same-origin, otherwise null.
