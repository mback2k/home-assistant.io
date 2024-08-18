---
title: WMS WebControl pro
description: Instructions on how to integrate WAREMA devices via WMS WebControl pro within Home Assistant.
ha_category:
  - Cover
  - Hub
  - Light
  - Scene
ha_release: '2024.9'
ha_iot_class: Local Polling
ha_codeowners:
  - '@mback2k'
ha_domain: wmspro
ha_config_flow: true
ha_platforms:
  - cover
  - light
  - scene
ha_integration_type: integration
related:
  - url: https://www.warema.com/en/smart-home/wms-webcontrol-pro/
    title: Consumer information about WMS WebControl pro
  - url: https://smartbuildings.warema.com/en/control-systems/radio-systems/wms/wms-webcontrol-pro/
    title: Technical documentation for WMS WebControl pro
---

The WMS WebControl pro integration allows users to integrate their WAREMA devices into Home Assistant.

This integration uses a local API which is available with firmware container version 11H.

See device section for support information: [covers](#covers), [lights](#lights), and [scenes](#scenes).

{% include integrations/config_flow.md %}

The WMS WebControl pro *may* also be discovered on your local network via DHCP.

## Covers

- *Patio awnings* can be opened, closed, set to a certain position and their movement stopped.
- The integration and library *may* already support other types of awnings with a single motor.

## Lights

- Dimmers (regarding their brightness) and switches are fully supported.

## Scenes

- Scenes can be activated, but not changed or monitored.
