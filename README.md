# [Junie](https://www.jetbrains.com/junie/) Enrichment Information

![](https://img.shields.io/badge/junie-side_project-blue) 

This repo contains advice text designed to be discovered by JetBrains Junie as part of its problem-solving process.

At the moment, this is just an experiment / a playground to understand what can (and can't) be reasonably achieved.

## How it works

By instructing Junie to query the `advice_index`, it is made aware of the available pieces of advice. The index also contains instructions for Junie on how to retrieve the individual pieces of instructions.

## Usage

To have Junie use the advice in this repository, add the contents of `JUNIE_PROMPT.md` to your project's `.junie/guidelines.md`.
