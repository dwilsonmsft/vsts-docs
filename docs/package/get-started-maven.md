---
title: Get Started with Maven Package Management in VSTS and TFS
description: Quickly start hosting Maven artifacts in VSTS or Team Foundation Server
ms.prod: devops
ms.technology: devops-artifacts
ms.topic: quickstart
ms.assetid: C5112218-DA7E-4016-986D-2D0F70DAFA44
ms.manager: jenp
ms.author: elbatk
author: elbatk
ms.reviewer: dastahel
ms.date: 01/31/2018
monikerRange: '>= tfs-2018'
---

# Get started with Maven Package Management in VSTS and TFS

**VSTS** | **TFS 2018**

## Before you start

This guide assumes you've already set up Package Management. You can check out how to install and license the extension in the 
[Install and license Package Management guide](install.md), or go directly to the [Marketplace](https://marketplace.visualstudio.com/items?itemName=ms.feed) 
listing to install it.

### Prerequisites

1. Apache Maven installed. It can be downloaded from the [Apache Maven Site](https://maven.apache.org/download.cgi).

1. Have [Package Management](https://marketplace.visualstudio.com/items?itemName=ms.feed) installed in your VSTS account.

<a name="create-a-feed"></a>

## Create a feed

*Already have a feed? [Skip to the next step](#setup-your-POM-and-settings-.xml).*

[!INCLUDE [](_shared/create-feed.md)]

<a name="setup-your-POM-and-settings-.xml"></a>

## Set up authentication

[!INCLUDE [](_shared/maven/pom-and-settings.md)]

<a name="publish-a-package"></a>

## Publish an artifact

[!INCLUDE [](_shared/maven/publish.md)]

<a name="consume-in-visual-studio"></a>

## Install an artifact from your feed

[!INCLUDE [](_shared/maven/install.md)]

<a name="automate-with-continuous-integration"></a>

## Automate the process with continuous integration

You can use continuous integration systems such as Team Build to automate the installation and publishing of your Maven artifacts. 
To get started with continuous integration, see the [Maven in Team Build guidance](/vsts/build-release/packages/maven).

## What's next?

For more advanced topics, check out the [content summary](overview.md).
