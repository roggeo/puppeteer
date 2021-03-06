<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Debugger](./puppeteer.protocol.debugger.md) &gt; [SetBreakpointByUrlRequest](./puppeteer.protocol.debugger.setbreakpointbyurlrequest.md)

## Protocol.Debugger.SetBreakpointByUrlRequest interface

<b>Signature:</b>

```typescript
export interface SetBreakpointByUrlRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [columnNumber](./puppeteer.protocol.debugger.setbreakpointbyurlrequest.columnnumber.md) | [integer](./puppeteer.protocol.integer.md) | Offset in the line to set breakpoint at. |
|  [condition](./puppeteer.protocol.debugger.setbreakpointbyurlrequest.condition.md) | string | Expression to use as a breakpoint condition. When specified, debugger will only stop on the breakpoint if this expression evaluates to true. |
|  [lineNumber](./puppeteer.protocol.debugger.setbreakpointbyurlrequest.linenumber.md) | [integer](./puppeteer.protocol.integer.md) | Line number to set breakpoint at. |
|  [scriptHash](./puppeteer.protocol.debugger.setbreakpointbyurlrequest.scripthash.md) | string | Script hash of the resources to set breakpoint on. |
|  [url](./puppeteer.protocol.debugger.setbreakpointbyurlrequest.url.md) | string | URL of the resources to set breakpoint on. |
|  [urlRegex](./puppeteer.protocol.debugger.setbreakpointbyurlrequest.urlregex.md) | string | Regex pattern for the URLs of the resources to set breakpoints on. Either <code>url</code> or <code>urlRegex</code> must be specified. |

