---
title: Local and cloud run large language models(LLM)
date: 2024-06-27 16:40:16
categories:
  - Web application
  - AI application
  - LLM System
tags:
  - AI
  - LLM
  - Coding
  - Web
---

## Why Use Local and Cloud LLM Systems?

People use local LLM (Large Language Model) systems for enhanced data security and privacy. Administrators need full control over the system and the ability to customize features and functions. Additionally, local systems can be more cost-effective compared to cloud solutions.

<!--more-->

## Local Device Tech Specs

CPU: 13th Gen Intel Core i7-13620H 2.4 GHz
GPU: Nvidia GeForce RTX 4060

## Local LLM System Performance

According to implementation tests, there are some differences in performance. For general questions, the processing time is quite different between using the CPU and the GPU.

{% img /images/LLM/LLM_gnernal_cpu.png 550 "General Local CPU" %} {% img /images/LLM/LLM_gnernal_gpu.png 550 "General Local GPU" %}

Moreover, for professional questions, such as programming queries, the GPU processes faster compared to the CPU. Specifically, the CPU processes at 8 tokens per second, while the GPU processes at 29 tokens per second.

{% img /images/LLM/aiprofessional_cpu.png 550 "Local CPU" %} {% img /images/LLM/aiprofessional_gpu.png 550 "Local GPU" %}

## Cloud LLM System Performance

In cloud LLM systems, there is no difference between processing general and professional questions. Both types of queries show a performance of 1250 tokens per second.

{% img /images/LLM/qiprofessional_cloud.png 550 "Cloud" %}

## Conclusion

The cloud LLM is the best choice when users need the LLM to respond to various data requests or questions efficiently.

## Software and Applications

Local LLM Application: GPT4All

Cloud System: groq.com
