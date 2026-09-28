---
title: "{{ replace .File.ContentBaseName `-` ` ` | title }}"
date: {{ .Date }}
endDate:
# Shown in Google results. e.g. "CARPE Raspberry Pi, Arduino, ESP32 & microcontroller meetup — Tue, Oct 13, 2026, 6:30 PM at Worthington Park Library, Worthington, OH. Free, all skill levels welcome."
description: ""
location: "TBD"
mapUrl: ""
meetupUrl: ""
draft: true
outputs:
  - HTML
  - ICS
---

