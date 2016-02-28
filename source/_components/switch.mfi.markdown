---
layout: page
title: "mFi Switch"
description: "Instructions how to integrate mFi switches within Home Assistant."
date: 2016-02-07 10:00
sidebar: true
comments: false
sharing: true
footer: true
logo: ubiquiti.png
ha_category: Switch
---


The `mfi` switch platform to allow you to control [mFi Controllable Power Outlets](https://www.ubnt.com/mfi/mpower/).

To add this platform to your installation, add the following to your `configuration.yaml` file:

```yaml
# Example configuration.yaml entry
sensor:
  platform: mfi
  host: IP_ADDRESS
  port: PORT
  username: USERNAME
  password: PASSWORD
```

Configuration variables:

- **host** (*Required*): The IP address or hostname of your mFi controller.
- **port** (*Optional*): The port of your mFi controller. Defaults to 6443.
- **username** (*Required*): The mFi admin username.
- **password** (*Required*): The mFi admin user's password.
