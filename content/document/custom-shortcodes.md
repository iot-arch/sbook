---
title: "Custom ShortCodes 1"
date: 2017-10-17T15:26:15Z
draft: false
weight: 10
description: "calling custom ShortCodes"
---

## Alert panel

{{< panel >}}This is a long contents .{{< /panel >}}

### Alert panel using HTML

{{< panel >}}
<strong>This is a long contents ipsum dolor sit amet</strong>, consectetur aliqua. <a href="https://github.com/thingsym/hugo-theme-techdoc"> next content </a>, quit.

<strong>This is a long contents ipsum dolor sit amet</strong>, consectetur. <a href="https://github.com/thingsym/hugo-theme-techdoc"> next content </a>, quid.
{{< /panel >}}

### Alert panel using Markdown (use the `%` character)

{{% panel title="primary" %}}
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

- One
- Two
- Three
{{% /panel %}}

### Alert panel with titles and colors

{{< panel title="primary" >}}This is a long contents .{{< /panel >}}

{{< panel status="notice" title="notice" >}}This is a long contents .{{< /panel >}}

{{< panel status="success" title="success" >}}This is a long contents .{{< /panel >}}

{{< panel status="caution" title="caution" >}}This is a long contents .{{< /panel >}}

{{< panel status="warning" title="warning" >}}This is a long contents .{{< /panel >}}

{{< panel status="danger" title="danger" >}}This is a long contents .{{< /panel >}}

### Alert panel with Font Awesome

{{< panel status="danger" title="danger" icon="fas fa-download" >}}This is a long contents .{{< /panel >}}

## Button

{{< button url="#" >}}primary{{< /button >}}

{{< button status="success" url="#" >}}success{{< /button >}}

{{< button status="caution" url="#" >}}caution{{< /button >}}

{{< button status="warning" url="#" >}}warning{{< /button >}}

{{< button status="danger" url="#" >}}danger{{< /button >}}

#### Button with Font Awesome

{{< button icon="fas fa-download" url="#" >}}Download{{< /button >}}

{{< button status="success" icon="fas fa-cloud-download-alt" url="#" >}}Download{{< /button >}}
