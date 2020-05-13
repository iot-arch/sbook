---
title: "Custom Shortcodes"
date: 2017-10-17T15:26:15Z
draft: false
weight: 10
description: "calling custom Shortcodes into your content files."
---

## Alert panel

{{< panel >}}Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.{{< /panel >}}


### Alert panel using Markdown (use the `%` character)

{{% panel title="primary" %}}
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

- One
- Two
- Three
{{% /panel %}}

### Alert panel with titles and colors

{{< panel title="primary" >}}Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.{{< /panel >}}

## Button

{{< button url="#" >}}primary{{< /button >}}

{{< button status="success" url="#" >}}success{{< /button >}}

{{< button status="caution" url="#" >}}caution{{< /button >}}

{{< button status="warning" url="#" >}}warning{{< /button >}}

{{< button status="danger" url="#" >}}danger{{< /button >}}

#### Button with Font Awesome

{{< button icon="fas fa-download" url="#" >}}Download{{< /button >}}

{{< button status="success" icon="fas fa-cloud-download-alt" url="#" >}}Download{{< /button >}}
