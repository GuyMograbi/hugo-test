---
type: post100
title:  Notify Container
categories: XAP100
parent: event-processing.html
weight: 200
---

<br>

{{%section%}}
{{%column width="10%" %}}
![fifo-groups.png](/attachment_files/subject/pubsub.png)
{{%/column%}}
{{%column width="90%" %}}
The notify event container uses the space inherited support for notifications (continuous query) using an XAP unified event session API.
A notify event operation is mainly used when simulating Topic semantics.
{{%/column%}}
{{%/section%}}

<br>

{{%fpanel%}}

[Overview](./notify-container.html){{%wbr%}}
The notify event container wraps the Space data event session API with event container abstraction.

[Transaction support](./polling-container-transactions.html){{%wbr%}}
The notify container can be configured with transaction support, so the event action can be performed under a transaction.


[Session Based Messaging API](./session-based-messaging-api.html){{%wbr%}}
The Notify Session API provides a unified and consistent mechanism for event registration.
{{%/fpanel%}}

<br>

#### Additional Resources

{{%youtube "GwLfDYgl6f8"  "Event Processing"%}}
