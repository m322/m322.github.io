---
layout: post
title:  Brainstorming for the project
date:   2024-12-16 10:00:00 +0100
tags:   [AISF, Project]
---

Those are the ideas that I currently have for the Capstone project, in no significant order:
1. Replicate (a part of) the [Best-of-N Jailbreaking](https://jplhughes.github.io/bon-jailbreaking/) [paper](https://arxiv.org/abs/2412.03556). I would try to jailbreak an LLM asking for harmful information by repeatedly providing a textual prompt with a combination of augmentations (word scrambling, random capitalization of letters, and character noising). The paper claims that even frontier models can be reasonably expected to be broken with less than 10k prompt variations.
2. Assess the _billing_ (professional deformation :wink:) aspect of LLMs. Investigate prices and limitations for the usage of the most popular models. This would be relevant for AI safety because cash-strapped research projects could allocate their resources more efficiently.
3. Evaluate the state of the art of Agentic AI. AI agents (such as [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT), [AG2](https://github.com/ag2ai/ag2), [Open Interpreter](https://github.com/openinterpreter/open-interpreter)) autonomously perform tasks on behalf of a user/system by designing their workflow and using available tools. _Agency_ refers to the ability to make decisions, take actions, solve complex problems and interact with external environments. In particular, do current AI agents possess some kind of control on their actions/decisions? For instance, something like checking their reasoning with [HarmBench](https://github.com/centerforaisafety/HarmBench).
4. Create a (basic) tool for data input controls. Something like a [Spark](https://spark.apache.org/)-based framework for common data filtration tasks. The starting point would be a series of [regex](https://en.wikipedia.org/wiki/Regular_expression) expressions to identify and remove potentially dangerous content.