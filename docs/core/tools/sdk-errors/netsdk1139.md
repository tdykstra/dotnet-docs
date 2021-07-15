---
title: "NETSDK1139: Target platform identifier not recognized"
description: Target platform identifier not recognized.
author: tdykstra
ms.author: tdykstra
ms.topic: error-reference
ms.date: 07/15/2021
f1_keywords:
- NETSDK1139
---
# NETSDK1139: Target platform identifier not recognized

NETSDK1139 indicates that you're using a target framework moniker (TFM) that specifies a platform, but the .NET SDK can't find a workload for the specified platform. The full error message is similar to the following example:

> The target platform identifier \<identifier> was not recognized.

For example, if the TFM is `net6.0-osx`, the `<identifier>` is `osx`.

* Make sure the platform part of the TFM is spelled correctly.
* Run [dotnet workload search](../dotnet-workload-search.md) to see if there's a workload for the platform.
*  
