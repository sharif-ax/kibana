[Home](./index) &gt; [kibana-plugin-public](./kibana-plugin-public.md) &gt; [UiSettingsClient](./kibana-plugin-public.uisettingsclient.md) &gt; [get](./kibana-plugin-public.uisettingsclient.get.md)

## UiSettingsClient.get() method

Gets the value for a specific uiSetting. If this setting has no user-defined value then the `defaultOverride` parameter is returned (and parsed if setting is of type "json" or "number). If the parameter is not defined and the key is not defined by a uiSettingDefaults then an error is thrown, otherwise the default is read from the uiSettingDefaults.

<b>Signature:</b>

```typescript
get(key: string, defaultOverride?: any): any;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  key | <code>string</code> |  |
|  defaultOverride | <code>any</code> |  |

<b>Returns:</b>

`any`

