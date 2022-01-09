---
layout: post
title:  "Golden 10 years: computing architecture?"
date:   2022-01-09 11:43=5
categories: SoC
tags: 芯片
excerpt: HPC machine: CPU, GPGPU, AI accelerator
mathjax: true
---

CAN NEVER tear software from hardware when discussing about computing:
Close coupling of hardware(ISA, microarchitecture) and software(compiler, OS (thread scheduling), drivers)

CPU: the crown in computing kingdom, most sophisticated computing architecture
key players:
emerging players: Apple with its M_x series, Qualcomm

ISA: 
base ISA, plus up-to-date extentions (e.p. Intels Advanced Matrix Extentions, kind of a DSA added to general CPU)

Component of the physical machine(micro-architecture):
from a chip design point of view, we judge the performance by 3 key factors: IPS(instructions per second, frequency dependent), 
power consumption, area(namely cost)

pipeline (up to 22 steps in x86 processors): front-end and back-end

caches(L1, L2, L3) + DRAM interfaces (memory controller): cache area



GPU: the Stark family in the kingdom
key players: Nvida, AMD
emerging players: coming from the oriental continent

API (ISA):GPU used to work under CPU, co-processor so to say. Therefore, its ISA is hidden to programmers

2 dominent applications of GPU>
rendering GPU:
GPGPU:



Performance judgement:
Benchmarks: Perf
Hands on testcases
