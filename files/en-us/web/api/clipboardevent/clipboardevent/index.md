---
title: ClipboardEvent()
slug: Web/API/ClipboardEvent/ClipboardEvent
tags:
  - API
  - Clipboard
  - Clipboard API
  - ClipboardEvent
  - Constructor
  - Cut
  - Reference
  - copy
  - paste
browser-compat: api.ClipboardEvent.ClipboardEvent
---
{{APIRef("Clipboard API")}}

The **`ClipboardEvent()`** constructor returns a newly created
{{domxref("ClipboardEvent")}}, representing an event providing information related to
modification of the clipboard, that is {{domxref("Element/cut_event", "cut")}}, {{domxref("Element/copy_event", "copy")}}, and
{{domxref("Element/paste_event", "paste")}} events.

## Syntax

```js
new ClipboardEvent(type)
new ClipboardEvent(type, options)
```

### Parameters

_The `ClipboardEvent()` constructor also inherits arguments from {{domxref("Event.Event", "Event()")}}._

- `type`
  - : Is a string representing the name of the type of the `ClipboardEvent`.
    It is case-sensitive and can be: `'copy'`, `'cut'`, or `'paste'`.
- `options` {{optional_inline}}

  - : Options are as follows:

    - `clipboardData`
      - : A {{domxref("DataTransfer")}} containing the data concerned by the clipboard event.
    - `dataType` {{non-standard_inline}}
      - : A string containing the MIME-type of the data contained in the `data` argument.
    - `data` {{non-standard_inline}}
      - : A string containing the data concerned by the clipboard event.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- Copy-related events: {{domxref("Element/copy_event", "copy")}}, {{domxref("Element/cut_event", "cut")}}, {{domxref("Element/paste_event", "paste")}}
- The {{domxref("ClipboardEvent")}} interface it belongs to.
- [Clipboard API](/en-US/docs/Web/API/Clipboard_API)
