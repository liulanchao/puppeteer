<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Overlay](./puppeteer.protocol.overlay.md) &gt; [InspectNodeRequestedEvent](./puppeteer.protocol.overlay.inspectnoderequestedevent.md)

## Protocol.Overlay.InspectNodeRequestedEvent interface

Fired when the node should be inspected. This happens after call to `setInspectMode` or when user manually inspects an element.

<b>Signature:</b>

```typescript
export interface InspectNodeRequestedEvent 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [backendNodeId](./puppeteer.protocol.overlay.inspectnoderequestedevent.backendnodeid.md) | [DOM.BackendNodeId](./puppeteer.protocol.dom.backendnodeid.md) | Id of the node to inspect. |

