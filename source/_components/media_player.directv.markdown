---
layout: page
title: "DirecTV"
description: "Instructions how to integrate DirecTV receivers into Home Assistant."
date: 2016-07-19 01:0+0000
sidebar: true
comments: false
sharing: true
footer: true
logo: directv.png
ha_category: Media Player
ha_release: "0.25"
---

The [DirecTV](http://www.directv.com/) receivers will be automatically discovered if you enable the [discovery component](/components/discovery/).

The `directv` media player platform can also be forced to load by adding the following lines to your `configuration.yaml`:

```yaml
# Example configuration.yaml entry
media_player:
  platform: directv
  host: 192.168.1.10
  name: DirecTV Living Room
```

Configuration variables:

- **host** *Optional*: Use only if you don't want to scan for devices.
- **name** *Optional*: Use to give a specific name to the device.
