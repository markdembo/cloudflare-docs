---
title: Analytics
pcx_content_type: reference
weight: 2
meta:
  title: DDoS analytics
---

# DDoS analytics

You can view DDoS analytics in different dashboards, depending on your service and plan:

- The [Security Events dashboard](/waf/analytics/) provides you with visibility into L7 security events that target your zone, including HTTP DDoS attacks and TCP attacks.

- The [Network Analytics dashboard](https://support.cloudflare.com/hc/articles/360038696631) provides you with visibility into L3/4 traffic and DDoS attacks that target your IP ranges or Spectrum applications.

## Availability

{{<table-wrap>}}

| Service       | Free              | Pro                | Business           | Enterprise         |
| ------------- | ----------------- | ------------------ | ------------------ | ------------------ |
| WAF/CDN       | Activity log only | Security Events    | Security Events    | Security Events    |
| Spectrum      | –                 | –                  | –                  | Network Analytics  |
| Magic Transit | –                 | –                  | –                  | Network Analytics  |

{{</table-wrap>}}
