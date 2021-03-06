<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [SystemInfo](./puppeteer.protocol.systeminfo.md) &gt; [VideoDecodeAcceleratorCapability](./puppeteer.protocol.systeminfo.videodecodeacceleratorcapability.md)

## Protocol.SystemInfo.VideoDecodeAcceleratorCapability interface

Describes a supported video decoding profile with its associated minimum and maximum resolutions.

<b>Signature:</b>

```typescript
export interface VideoDecodeAcceleratorCapability 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [maxResolution](./puppeteer.protocol.systeminfo.videodecodeacceleratorcapability.maxresolution.md) | [Size](./puppeteer.protocol.systeminfo.size.md) | Maximum video dimensions in pixels supported for this \|profile\|. |
|  [minResolution](./puppeteer.protocol.systeminfo.videodecodeacceleratorcapability.minresolution.md) | [Size](./puppeteer.protocol.systeminfo.size.md) | Minimum video dimensions in pixels supported for this \|profile\|. |
|  [profile](./puppeteer.protocol.systeminfo.videodecodeacceleratorcapability.profile.md) | string | Video codec profile that is supported, e.g. VP9 Profile 2. |

