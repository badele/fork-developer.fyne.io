---
layout: page
tags: [api]
title: Fyne API desktop
---

# desktop
--
    import "fyne.io/fyne/driver/desktop"

## Usage

#### type Keyable

```go
type Keyable interface {
	fyne.Focusable

	KeyDown(*fyne.KeyEvent)
	KeyUp(*fyne.KeyEvent)
}
```

Keyable describes any focusable canvas object that can accept desktop key events. This is the traditional key down and up event that is not applicable to all devices.