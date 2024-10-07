---
author: Gabin Le Saout
pubDatetime: 2024-10-07T15:44:00Z
title: Binary code injection
draft: true
tags:
  - school_projects
description: This article will describe the project done during ISOS at school
---

This project has been done during the ISOS lab lessons. The objective was to inject some code and execute it into a give ELF binary. It is not binary dependant, as long as it is an ELF one it should work. 

To help us conducting this, the steps have been divided into multiple challenges. Here they are :
1. Initializing things
2. Finding the PT_NOTE segment header
3. Inject the malicious code
4. Overwriting a section header
5. Reorder the section headers
6. Overwriting the PT_NOTE program header
7. Execute the injected code