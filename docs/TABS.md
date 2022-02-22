# Tabs

Tabs organize content across different screens, data sets, and other interactions.

## Element

```html
<div class="tabs">...</div>
```

## Most used helpers

**Alignments**
left-align, right-align, center-align

**Triggers**
active

## Example

```html
<div class="tabs">
  <a>Tab 1</a>
  <a>Tab 2</a>
  <a>Tab 3</a>
</div>

<div class="page">
  <h5>Tab 1</h5>
</div>
<div class="page">
  <h5>Tab 2</h5>
</div>
<div class="page">
  <h5>Tab 3</h5>
</div>
```

## Triggers 

#### To active a tab

#### Method 1

Add/remove `active` class on tab and page elements.

```html
<div class="tabs">
  <a class="active">Tab 1</a>
  <a>Tab 2</a>
  <a>Tab 3</a>
</div>

<div class="page active">
  <h5>Tab 1</h5>
</div>
<div class="page">
  <h5>Tab 2</h5>
</div>
<div class="page">
  <h5>Tab 3</h5>
</div>
```

#### Method 2

Add `data-ui="page-selector"` attribute on elements and call `ui()` after html output. All other pages that are in the same level will be hidden.

```html
<div class="tabs">
  <a data-ui="#page1">Tab 1</a>
  <a data-ui="#page2">Tab 2</a>
  <a data-ui="#page3">Tab 3</a>
</div>

<div class="page" id="page1">
  <h5>Tab 1</h5>
</div>
<div class="page" id="page2">
  <h5>Tab 2</h5>
</div>
<div class="page" id="page3">
  <h5>Tab 3</h5>
</div>
```

```js
ui();
```

## Related to
[Icon](https://github.com/beercss/beercss/blob/main/docs/ICON.md), [Media](https://github.com/beercss/beercss/blob/main/docs/MEDIA.md), [Page](https://github.com/beercss/beercss/blob/main/docs/PAGE.md)

## Go to
[Begin](https://github.com/beercss/beercss/blob/main/docs/INDEX.md), [Elements](https://github.com/beercss/beercss/blob/main/docs/ELEMENTS.md), [Helpers](https://github.com/beercss/beercss/blob/main/docs/HELPERS.md), [Settings](https://github.com/beercss/beercss/blob/main/docs/SETTINGS.md), [beercss.com](https://www.beercss.com)