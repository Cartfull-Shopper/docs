---
title: "How to Work with Cart Nofitications"
description: "Learn more about how to work with this powerful feature"
summary: "Learn how to create and respond to notifications."
date: 2025-10-03T21:37:51-07:00
lastmod: 2025-10-03T21:37:51-07:00
draft: false
weight: 999
toc: true
seo:
  title: "How to Work with Cart Nofitications" # custom title (optional)
  description: "Learn how to better monitor your carts with cart notifications" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

Cart notifications are a powerful feature to help you respond to carts in real time. You
can set up your notifications with a number of different combinations to target the exact
kind of carts that you care about.

## Create a Notification
In the top navbar, click on "Notifications". This page will list all your notifications
and you'll see a "Create" button at the top. 

![Navigate to create a cart notification](/images/docs/notification-navbar.png)

{{< callout context="tip" title="Modifying a Notification" icon="rocket" >}}

Modifying a current notification is essentially creating a brand new one. If your
notification is not meeting your needs, you can simply delete and create a new one. Any
deleted notifications will not be counted towards your max number of allowed
notifications.

{{< /callout >}}

Click the "Create" button to create a new alert. From here we encourage you to think about
your business needs. What kinds of carts would it be helpful to take immediate action?

Here's a little bit about each attribute of a notification:

![Create a notification](/images/docs/notification-form.png)

### Name
Give it a good, identifying name so you know exactly what kind of carts the notifications
refers to.

### To status 
The status the cart enters into.

### From status 
The status the cart is coming from, i.e carts coming from "abandoned" are good to know
about.

### Customers
Here you can add customers that the cart must belong to in order to be notified about the
cart.

### Products
Here you can list the products that must be associated with the cart. This field _must_ be
accompanied by a Product State.
 
### Product State 
You _must_ include this field if you have specified any products. This allows you to be
notified based on whether the product is already in the cart, was added to it, or was
removed from it.

### Cart Amount
The amount the cart must have to meet this notification criteria. You can specify that the
amount must be greater or less than your specified amount. 

### Occurrences
This is for when you do not wish to be notified of every single event, but do want to be
aware if carts are meeting this criteria on a regular basis. You can specify how many
times within a given period (minutes, days, weeks, etc) the criteria must be met before
you are notified. This is great for getting overall health checks for your store.

### Cart Identifies
This is for when you just want to know that a cart changed from a guest cart to be
identified with a name and/or email.

### Send Email
Check this box if you wish to _also_ be notified via email when a cart meets the criteria
in this notification.

## Per User
Notifications are also per user - not per store.

Plans start at 10 notifications per user.

{{< callout context="note" title="Store Notifications" icon="info-icon" >}}

If you think it would be helpful to have store-wide notifications, drop us an email at
support@cartfull-shopper.com to request that feature.

{{< /callout >}}
 
## Read Notifications

![Read notifications](/images/docs/unread-notifications.png)

Once your notification is in action, you'll be notified via the bell on the top right of
your dashboard. This bell will be filled in whenever you have unread notifications. To
read your notifications, simply click on it. You'll be taken to that cart where you can
learn more about it - for example: the customer name (if available), the products in it,
and the total value. From here, you can treat the cart like any other within Cart
Activity, including modifying and checking out the cart.

And that's all! Get creative and start converting more carts with real time notifications!
