---
title: Out of memory error when connecting to Azure Virtual Desktop
description: Troubleshooting connection error when trying to connect to Azure Virtual Desktop with the web client.
ms.reviewer: elluthra
ms.topic: troubleshooting
author: Heidilohr
manager: femila
ms.author: helohr
ms.date: 12/03/2021
ms.localizationpriority: medium
---
# "Out of memory" error when connecting to Azure Virtual Desktop

When you're trying to connect to Azure Virtual Desktop from the web client and an error message that says, "Oops, we couldn't connect to 'SessionDesktop,'" appears, then the web client has run out of memory.

To resolve this issue, you'll need to either reduce the size of the browser window or disconnect all existing connections and try connecting again. If you still encounter this issue after doing these things, ask your local admin or tech support for help.

This issue may also be happening because you're using an N SKU without a media features pack. To resolve this issue, [install the media features pack](https://support.microsoft.com/topic/media-feature-pack-list-for-windows-n-editions-c1c6fffa-d052-8338-7a79-a4bb980a700a).
