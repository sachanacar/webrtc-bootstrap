---
layout: page
title: WebRTC Dictionary
permalink: /webrtc-dictionary/
---

WebRTC is hard, you need to be familiar with a lot of new concepts. Here is a dictionary that will help you understand all the components of WebRTC.

###Signalling

Signaling is the process of coordinating communication between two endpoints - two browsers, two phones, etc. In order for a WebRTC application to set up a 'call', its clients need to exchange information. It is currently not defined by the WebRTC standard, so you have to built it yourself. [Resources here](/starter-kit/#signalling-frameworks).

###STUN

A host uses Session Traversal Utilities for NAT (STUN) to discover its public IP address when it is located behind a NAT/Firewall. [Resources here](/starter-kit/#turnstun-servers).

###TURN

If the NAT/Firewall still won't allow the two hosts to connect directly, they make a connection to a server implementing Traversal Using Relay around NAT (TURN), which will relay media between the two parties. [Resources here](/starter-kit/#turnstun-servers).

###ICE

Interactive Connectivity Establishment (ICE) is a blanket standard that describes how to coordinate STUN and TURN to make a connection between hosts.[Resources here](/starter-kit/#turnstun-servers).
