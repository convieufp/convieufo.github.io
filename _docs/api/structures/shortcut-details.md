---
version: v1.4.13
category: API
redirect_from:
  - /docs/v0.37.8/api/structures/shortcut-details
  - /docs/v0.37.7/api/structures/shortcut-details
  - /docs/v0.37.6/api/structures/shortcut-details
  - /docs/v0.37.5/api/structures/shortcut-details
  - /docs/v0.37.4/api/structures/shortcut-details
  - /docs/v0.37.3/api/structures/shortcut-details
  - /docs/v0.36.12/api/structures/shortcut-details
  - /docs/v0.37.1/api/structures/shortcut-details
  - /docs/v0.37.0/api/structures/shortcut-details
  - /docs/v0.36.11/api/structures/shortcut-details
  - /docs/v0.36.10/api/structures/shortcut-details
  - /docs/v0.36.9/api/structures/shortcut-details
  - /docs/v0.36.8/api/structures/shortcut-details
  - /docs/v0.36.7/api/structures/shortcut-details
  - /docs/v0.36.6/api/structures/shortcut-details
  - /docs/v0.36.5/api/structures/shortcut-details
  - /docs/v0.36.4/api/structures/shortcut-details
  - /docs/v0.36.3/api/structures/shortcut-details
  - /docs/v0.35.5/api/structures/shortcut-details
  - /docs/v0.36.2/api/structures/shortcut-details
  - /docs/v0.36.0/api/structures/shortcut-details
  - /docs/v0.35.4/api/structures/shortcut-details
  - /docs/v0.35.3/api/structures/shortcut-details
  - /docs/v0.35.2/api/structures/shortcut-details
  - /docs/v0.34.4/api/structures/shortcut-details
  - /docs/v0.35.1/api/structures/shortcut-details
  - /docs/v0.34.3/api/structures/shortcut-details
  - /docs/v0.34.2/api/structures/shortcut-details
  - /docs/v0.34.1/api/structures/shortcut-details
  - /docs/v0.34.0/api/structures/shortcut-details
  - /docs/v0.33.9/api/structures/shortcut-details
  - /docs/v0.33.8/api/structures/shortcut-details
  - /docs/v0.33.7/api/structures/shortcut-details
  - /docs/v0.33.6/api/structures/shortcut-details
  - /docs/v0.33.4/api/structures/shortcut-details
  - /docs/v0.33.3/api/structures/shortcut-details
  - /docs/v0.33.2/api/structures/shortcut-details
  - /docs/v0.33.1/api/structures/shortcut-details
  - /docs/v0.33.0/api/structures/shortcut-details
  - /docs/v0.32.3/api/structures/shortcut-details
  - /docs/v0.32.2/api/structures/shortcut-details
  - /docs/v0.31.2/api/structures/shortcut-details
  - /docs/v0.31.0/api/structures/shortcut-details
  - /docs/v0.30.4/api/structures/shortcut-details
  - /docs/v0.29.2/api/structures/shortcut-details
  - /docs/v0.29.1/api/structures/shortcut-details
  - /docs/v0.28.3/api/structures/shortcut-details
  - /docs/v0.28.2/api/structures/shortcut-details
  - /docs/v0.28.1/api/structures/shortcut-details
  - /docs/v0.28.0/api/structures/shortcut-details
  - /docs/v0.27.3/api/structures/shortcut-details
  - /docs/v0.27.2/api/structures/shortcut-details
  - /docs/v0.27.1/api/structures/shortcut-details
  - /docs/v0.27.0/api/structures/shortcut-details
  - /docs/v0.26.1/api/structures/shortcut-details
  - /docs/v0.26.0/api/structures/shortcut-details
  - /docs/v0.25.3/api/structures/shortcut-details
  - /docs/v0.25.2/api/structures/shortcut-details
  - /docs/v0.25.1/api/structures/shortcut-details
  - /docs/v0.25.0/api/structures/shortcut-details
  - /docs/v0.24.0/api/structures/shortcut-details
  - /docs/v0.23.0/api/structures/shortcut-details
  - /docs/v0.22.3/api/structures/shortcut-details
  - /docs/v0.22.2/api/structures/shortcut-details
  - /docs/v0.22.1/api/structures/shortcut-details
  - /docs/v0.21.3/api/structures/shortcut-details
  - /docs/v0.21.2/api/structures/shortcut-details
  - /docs/v0.21.1/api/structures/shortcut-details
  - /docs/v0.21.0/api/structures/shortcut-details
  - /docs/v0.20.8/api/structures/shortcut-details
  - /docs/v0.20.7/api/structures/shortcut-details
  - /docs/v0.20.6/api/structures/shortcut-details
  - /docs/v0.20.5/api/structures/shortcut-details
  - /docs/v0.20.4/api/structures/shortcut-details
  - /docs/v0.20.3/api/structures/shortcut-details
  - /docs/v0.20.2/api/structures/shortcut-details
  - /docs/v0.20.1/api/structures/shortcut-details
  - /docs/v0.20.0/api/structures/shortcut-details
  - /docs/vlatest/api/structures/shortcut-details
source_url: >-
  https://github.com/electron/electron/blob/master/docs/api/structures/shortcut-details.md
title: ShortcutDetails Object
excerpt: ''
sort_title: shortcut-details
---
# ShortcutDetails Object

*   `target` String - The target to launch from this shortcut.
*   `cwd` String (optional) - The working directory. Default is empty.
*   `args` String (optional) - The arguments to be applied to `target` when launching from this shortcut. Default is empty.
*   `description` String (optional) - The description of the shortcut. Default is empty.
*   `icon` String (optional) - The path to the icon, can be a DLL or EXE. `icon` and `iconIndex` have to be set together. Default is empty, which uses the target's icon.
*   `iconIndex` Number (optional) - The resource ID of icon when `icon` is a DLL or EXE. Default is 0.
*   `appUserModelId` String (optional) - The Application User Model ID. Default is empty.
