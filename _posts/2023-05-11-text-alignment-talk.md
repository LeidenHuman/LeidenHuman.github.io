---
title: Text Alignment Talk with Chris Handy
author: Chris Handy
tags:
 - Talk
 - Text alignment
---
# Cross-linguistic Text Alignment: An Evolutionary Approach

Text alignment is the process of finding similar passages across two or more documents. Text alignment is a process that can be useful in examining multiple versions of a document, whether in one or several languages, or in searching for text re-use within a collection of disparate documents. Some examples of the types of projects that benefit from text alignment include: 1) matching parallel readings of Bible passages across different translations, 2) compiling multiple versions of "Little Red Riding Hood" or other popular narratives, and 3) locating thematically similar texts within a larger corpus (e.g. finding medical literature within a Buddhist canon). Traditionally, the process of text alignment is done by a human being, and the determination of the boundaries of aligned segments is largely intuited from the education and experience of the researcher.

However, if we attempt to automate this process, we quickly find that defining formally what similarity means can be a non-trivial task. This talk focuses on one particular solution to this problem, developed initially for a project in Buddhist Studies but then generalised to cover a wide variety of text alignment problems across any languages and genres. The basic idea is that the data presented to us are always in a less than ideal state, and that alignment of any two passages can never have a single correct solution. Instead of attempting to achieve perfect alignments, my method is to approach a hypothetical ideal alignment through an iterative process that begins with a series of educated guesses about aligned passages and then refines those guesses using a customisable scoring system. I use a simple genetic algorithm, designed in Python, to create a population of "agents" that each possess a sequence of data called a "gene" that dictates the alignment guesses each agent makes about a set of texts. Agents assign scores to themselves based on dictionary matches and other information, and a master controller combines the genes of the top scoring agents to create the next generation of agents. Over multiple generations, these agents evolve toward desired alignments, in a way that is similar to dog breeding or other processes of artificial selection among biological organisms. The system I have designed is free, open source and easy to use, allowing a researcher to select population sizes, mutation rates, scoring mechanisms and other variables to suit any particular alignment project. This software is also made to run on nearly any device, including cluster computers (e.g. the Leiden ALICE cluster), personal computers, mobile phones, and even Raspberry Pi and other single board computers.

### Location
Location: PJ Veth 1.16 Time: 12:00-13:00

### Availability
Spots still available