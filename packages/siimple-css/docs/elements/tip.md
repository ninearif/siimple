---
title: "Tip"
description: "A special alert to grab attention in something important"
---

> Redesigned in **v4.0.0**.

<style>
.siimple-tip:last-child {
    margin-bottom: 0px !important;
}
</style>

A **siimple tip** is a special alert element designed to grab attention in something important in your website or application. To create a basic tip element, just add the `siimple-tip` class to a `<div>` element:

:::snippet title="Basic tip example" lang="html"
<div class="siimple-tip siimple-tip--primary">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
:::


#### Colored tip

All the different colors specified in the [theming](/css/getting-started/theming.html) section can be used to customize your tip element:

:::snippet title="Colored tip example" lang="html"
<div class="siimple-tip siimple-tip--primary">
    Primary tip
</div>
<div class="siimple-tip siimple-tip--secondary">
    Secondary tip
</div>
<div class="siimple-tip siimple-tip--success">
    Success tip
</div>
<div class="siimple-tip siimple-tip--warning">
    Warning tip
</div>
<div class="siimple-tip siimple-tip--error">
    Error tip
</div>
:::


#### Tip with an icon

You can also add a heart icon adding the `siimple-tip--heart` class, an exclamation icon adding the `siimple-tip--exclamation` class or a question icon adding the `siimple-tip--question` class.

:::snippet title="Tip with an icon" lang="html"
<div class="siimple-tip siimple-tip--error siimple-tip--heart">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
<div class="siimple-tip siimple-tip--warning siimple-tip--exclamation">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
<div class="siimple-tip siimple-tip--primary siimple-tip--question">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
:::


#### New tip icons

> Added in **v4.0.0**

Tip now accepts `siimple-tip--info` for displaying an info icon, `siimple-tip--check` for displaying a check icon  and `siimple-tip--cross` for displaying a cross icon.

:::snippet title="New tip icons example" lang="html"
<div class="siimple-tip siimple-tip--primary siimple-tip--info">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
<div class="siimple-tip siimple-tip--success siimple-tip--check">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
<div class="siimple-tip siimple-tip--error siimple-tip--cross">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
:::


