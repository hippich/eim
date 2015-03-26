Email Messenger
===============

Email Messenger will be an Instant Messenger based on Email as a transport protocol.

Today many corporations provide "cloud" instant messengers, but all of them use proprietary
protocols. Recent one - Facebook is dropping XMPP support from Facebook Messenger. This lead
me to thinking what could be ultimate protocol, which no corporation could "embrace, extend, extinguish"?
And answer for me was - email. Unlike long time ago, today email deliveries are often near-instantaneous,
and with right amount of care can become universal chatting protocol.

On top of it, because it is still email - you can reply from you favorite email client, be it Gmail or
Thunderbird or Outlook.

Following features can be implemented as is on top of email:

* One-on-one chats
* Group chats
* Offline messaging
* Attachments
* Encryption

Following features can be implemented leveraging third-party services via intelligently pre-processing message content:

* Attaching videos (via embedding youtube.com, vimeo.com, etc links for example, and rendering these into
  html in-place)
* Voice/Video calls (via sending unique URL to WebRTC service)
* Public conversations, a-la Twitter (minus 140 characters limit.) Could be implemented via newsletter-like
  service, where all emails in particular thread are shown on website.
