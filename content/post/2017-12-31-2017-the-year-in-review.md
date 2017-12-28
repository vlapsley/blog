+++
title = "2017 - The year in review"
date = "2017-12-29"
description = "2017 - The year in review."
categories = ["review"]
tags = ["review", "homelab", "minetest", "minecraft", "DIY", "rancher", "docker", "kubernetes", "coreos", "proxmox", "devops", "azure", "git"]
toc = true
comments = true
draft = false
+++

## Docker and Rancher, and Kubernetes, oh my!

Began the year 2017 trying to get [Kubernetes](https://kubernetes.io/) up and running. My homelab server was running Ubuntu 16.04 with KVM/QEMU hypervisor. I had a master VM and 3 worker VM to create a Kubernetes cluster. I tried both [Tectonic](https://coreos.com/tectonic/) from CoreOS and a [Cluster from Scratch](https://kubernetes.io/docs/getting-started-guides/scratch/) but just couldn't get it up and running. Very frustrating.

In July, I replaced the hypervisor on the homelab server with [Proxmox](https://www.proxmox.com/). Wow, what an awesome product. Easy to use, great features and very stable. Promptly tried the Tectonic Kubernetes cluster build and got it working! But alas, one of the worker nodes would fall over with not enough memory to run [Prometheus](https://prometheus.io/) monitoring and other services. Back to the drawing board.

I researched an alternative and decided to build a [Rancher](https://rancher.com/) cluster. I had dabbled with Rancher in 2016 whilst learning some basic [Docker](https://www.docker.com/) functionality. In less than an hour with Proxmox and RancherOS I had a Rancher orchestration VM and 3 worker nodes built. Five minutes later I have a Hello World web page served with Nginx in Docker. I couldn't believe how easy this was to get working.

## Minetest mapgen and mods

I created a [Minetest](https://www.minetest.net/) mapgen in C++ code and had it committed into the [master repo](https://github.com/minetest/minetest/commits?author=vlapsley). This was my first project with C++ code, first time coding with C++ at all! I was pretty happy with the results and stoked that it has been included for all Minetest players to now use as a base mapgen.

[Outback](https://github.com/vlapsley/outback) is a Minetest subgame I created based on my homeland, Australia. I spent considerable time on this project but never got it to a release ready stage. I'm unlikely to ever finish it since discovering Minecraft...

## Minecraft

I have played and developed for Minetest for around five years. I started with it because I was interested in [Minecraft](https://minecraft.net/) and decided to test an open source/free alternative first. Liked what I saw and kept playing Minetest.

In October, I decided to download a Minecraft trial to see what it was like compared to Minetest. Well, I was blown away by the game itself and the polish of the product. I haven't looked back and have been plowing hours into building up resources to eventually battle the Ender Dragon and win the game. Isabella is dead keen to play too, but we don't have a spare computer right now for her.

## Innovation time

At work during October/November, the IT Manager created "innovation time" - three hours a week for six weeks to present a proof of concept to the business on a new IT thing. I was included in the DevOps group, which is somewhat difficult to create a POC for.

But we did end up creating a demo for source code version control using [Git](https://git-scm.com/) and [GitHub](https://github.com/). I led our group of four in learning Git/GitHub and we demonstrated git commits, branches, blame, revert, GitHub pull requests and merge conflicts. We put it all together at the end and presented an [Azure Resource Manager](https://azure.microsoft.com/en-au/features/resource-manager/) virtual server template stored in GitHub and provisioned with a single PowerShell command.

## Adventures with DIY

I [replaced the clothesline](https://twitter.com/vlapsley/status/921921372607062016) in our backyard in October. It promptly started to rain five minutes after completing the install. C'est la vie.

In December I [fixed the power supply](/post/2017-12-27-the-operation-was-a-success/) in our PVR.

## One more thing...

And in December I created this blog. Learnt a little AWS, HTML and CSS in the process.
