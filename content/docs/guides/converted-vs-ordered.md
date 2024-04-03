---
title: "Converted vs Ordered Carts"
description: "What is a converted cart vs an ordered cart"
summary: ""
date: 2024-04-02T10:10:48-07:00
lastmod: 2024-04-02T10:10:48-07:00
draft: false
weight: 999
toc: true
seo:
  title: "Converted vs Ordered Carts" # custom title (optional)
  description: "What is a converted cart vs an ordered cart" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

Under Cart Activity you will see multiple statuses, two of them are "Converted" and
"Ordered". 

Converted carts are those that have a checkout completed. Every step of the process has
been done, except for paying for the items in the cart.

{{< callout context="note" title="Important" icon="info-circle" >}}

Converted carts are particular important to monitor. Every step has been taken except
payment. Monitor carts in this state and reach out to prod them to complete their
purchase.

{{< /callout >}}

![Ordered vs Converted Carts](/images/docs/ordered-vs-converted.png)

Once payment has been rendered, the cart will be updated to an "Ordered" state. These are
carts that have officially paid for items in your store.
