---
layout: post
title:  "Apple M1 Processor: What is SoC?"
date:   2020-12-21 7:41=5
categories: SoC
tags: 芯片
excerpt: Design and test of system-on-a-chip
mathjax: true
---


When I chatted with my friends, we talked about the M1 processor that recently launched by Apple.
I was asked what is a SoC, since it's mentioned in many of the technical reports and many people who doesn't works in IC industry may not know it well.

During master study, I did attend the lecture with a title exactly named as 'System-on-Chip'. The content is however a bit general or shadow to my current perspective.
The lecturer had focused mostly on the the performance bottleneck of SoC, namely on-chip communication and memory architecture. Communicationa and memory are obviously important, 
but I believe for the students who will go and work in industry instead of academic institutes, it would be more interesting to have an overview of SoC design, test and manufacture.
Then I found this publicly available lecture notes from Andreas Gerstlauer, University of TEXAS at Austin.

System Architecture:
processing element(PEs):
	Processors:
		General purpose, programmable
		DSP
		Application-specific instruction set processor(ASIP)
		Custom hardware processors
		Intellectual Property(IP)
	Memories
Communication elements:
	Transducers, bus bridges
	I/O peripherals
Busses:
Application mapping:
	Allocation
	Partitioning
	Scheduling
	
re-active programming -> programming paradiagm
