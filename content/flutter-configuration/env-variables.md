---
title: Adding environment variables
description: How to add environment variables in the Flutter workflow editor
weight: 4
aliases: /flutter/env-variables
---

Environment variables are useful for making available for Codemagic the credentials, configuration files or API keys that are required for successful building or integration with external services. For more information about the use of environment variables and a list of Codemagic read-only environment variables, refer [here](../building/environment-variables).

You can add environment variables to your Flutter projects in **App settings > Environment variables**.

1. Enter the name and the value of the variable.
2. Check **Secure** if you wish to hide the value both in the UI and in build logs and disable editing of the variable. Such variables can be accessed only by the build machines during the build.
3. Click **Add**.
