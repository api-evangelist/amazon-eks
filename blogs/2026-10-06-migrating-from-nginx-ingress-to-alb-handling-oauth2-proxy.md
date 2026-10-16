---
title: "Migrating from NGINX Ingress to ALB: Handling oauth2-proxy"
url: "https://aws.amazon.com/blogs/containers/migrating-from-nginx-ingress-to-alb-handling-oauth2-proxy/"
date: "2026-10-06"
author: "Ali Sanhaji"
feed_url: "https://aws.amazon.com/blogs/containers/feed/"
---
The NGINX Ingress Controller is retired. If you run oauth2-proxy with NGINX for OpenID Connect authentication, switching to the AWS Load Balancer Controller can silently break your auth. This post shows two ways to keep OIDC working on an Application Load Balancer: run oauth2-proxy in reverse proxy mode, or use ALB native OIDC.
