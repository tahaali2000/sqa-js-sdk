
# Custom Header Signature



Documentation for accessing and setting credentials for api_key.

## Auth Credentials

| Name | Type | Description | Setter |
|  --- | --- | --- | --- |
| api_key | `string` | - | `apiKey` |



**Note:** Auth credentials can be set using `customHeaderAuthenticationCredentials` object in the client.

## Usage Example

### Client Initialization

You must provide credentials in the client as shown in the following code snippet.

```ts
const client = new Client({
  customHeaderAuthenticationCredentials: {
    'api_key': 'api_key'
  },
});
```


