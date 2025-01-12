# Loak Lightship ARDK Template

A simple template project for Lightship ARDK experiences with useful tools from the Loak team.

## Description

This repo can be forked or cloned and used to create Lightship AR experiences. It is a tool to help you get started faster in which we provide several of our in-house tools and assets so you can focus on making a great experience rather than spending time on small details.

This template is also made to be perfectly compatible with the Loak platform and makes submission easy!

## Getting Started

### Dependencies

* Unity Editor version 2021.3.9f1+ (This template was created with this version and may have problems with newer versions.)
* Lightship ARDK v2.5.1 (included in the repo)
* Gradle v6.9.4+

### Installing

* Fork or clone this repo to your local dev environment.
* Open with a supported Unity version.
* Go to Edit > Preferences > External Tools and scroll to the bottom.
* Ensure that "Gradle installed with Unity" is unchecked and the path is pointing to your Gradle v6.9.4+ binaries.
* Exit the preferences window and find your project view.
* In the project view, go to Resources > ARDK and select the ARDKAuthConfig asset to view in the inspector.
* Fill in the API Key field by following steps 2 and 3 of this guide: [Authentication](https://lightship.dev/docs/ardk/ardk_fundamentals/authentication.html#doxid-authentication)
* You can rename the "Your Project" folder in Assets to the name of your experience.
* Choose a scene template that fits your needs! We provide several, each with different features already set up for you.

## Help

### What can I do with this template?

Anything! The scene included is a barebones ARDK setup that can be used in any way you see fit. If you need any ideas or want to get more familiar with what the ARDK provides, check out the [Lightship wesbite](https://lightship.dev/). You can also check out the experiences hosted on our platform to see what us and other people have made with these tools: [Our Website](https://www.loak.co/)

### How do I use the Loak Scanner?

The "Template (Meshing)" scene has it set up already, but if you wish to use it elsewhere just drag the prefab into your scene. You can find the Loak Scanner prefab by searching in the Project window or at Assets/Loak/Prefabs.

Ensure that you have Lightships ARMeshManager component somewhere in your scene or the scanner will not work. If you don't already have one you can add it to the Loak Scanner object or anywhere else as you see fit. We recommend creating your own object to house your Lightship scripts. Don't forget that your mesh root object needs to have a negative y scale.

After adding the prefab to your scene you can customize its behavior in the inspector. Each value has a tooltip to help you understand what it does. The most important value is the Scan Threshold. This value determines how much mesh needs to be generated before the scan is complete. You will likely need to adjust this value up or down depending on the needs of your experience and your ARMeshManager settings.

### I have questions that aren't answered here.

If you still need help, feel free to reach out to us through our [Discord server](https://discord.gg/y8wzR8MKKk). If your problem is with a Lightship feature and not the Loak tools provided in this template, you may get better results by asking in Lightship's forum or Discord server.

## Features

### Available

These are the Loak features and tools that we currently provide in this template:

* Loak Scanner - A smooth meshing setup phase for use with any real-time meshing experience.

### Roadmap

These are some of the Loak features and tools that we plan to add to this template in the future. Feel free to suggest some in our [Discord server!](https://discord.gg/y8wzR8MKKk)

* Loak Leaderboards - A simple score submission and leaderboard display system for games that want a more competitive feel.