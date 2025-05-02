---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
type: "software"
description: "Descripción corta del software"
downloads:
  - os: "Windows"
    url: "/downloads/{{ .Name }}-windows.zip"
  - os: "macOS"
    url: "/downloads/{{ .Name }}-macos.zip"
  - os: "App Store"
    url: "https://enlace-a-app-store"
---