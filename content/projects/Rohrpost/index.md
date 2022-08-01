---
author: Florian Raichle
type: project
tag: WIP
date: '2022'
title: Rohrpost
description: Quickly share something between all of your devices. 
---

If you have a link, snippet of text or an image you just want to get from one device to another, use Rohrpost.
It syncs instantly between all of your devices. 
{{< figure src="media/Simulator2.png" class="flex justify-center" height="150" width="150" >}}

The goal was to find a simple starter project to have a go at app development.
I was using Windows and iOS and wanted an easy way to share small amounts of data between the two operating systems, without having to email myself.
Thus I came up with Rohrpost.
It functions similarly to a messaging app, but only the owner can see their content.
It is not just copied from one tutorial which is important when learning, but I obviously took inspiration from some blog posts and tutorials.

## Technical Highlights
- Instant Sync using Google Firebase
- Cross Platform through Flutter

Using Firebase as a backend enabled easy serverless sync with great compatibility with flutter resulting in responsive design.
Functionality like search uses the power of declarative programming in flutter, which in general made building the UI very easy and a lot of fun.
