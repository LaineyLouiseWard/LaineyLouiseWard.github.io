---
title: Research Literature Monitor
publishDate: 2025-03-14 00:00:00
img: /assets/placeholder.svg
img_alt: Placeholder — image coming soon
description: |
  An automated RSS and LLM pipeline that scans newly published research papers, filters them for relevance to subseasonal-to-seasonal forecasting and compound weather extremes, and logs matched papers for review.
tags:
  - Python
  - RSS
  - LLM
  - GitHub Actions
  - YAML
methods:
  - Automated Literature Screening
  - Keyword and Semantic Filtering
  - Research Monitoring
---

Keeping up with the volume of new research across S2S prediction, compound extremes, and AI weather modelling is a constant challenge. This project automates that process with a lightweight pipeline that pulls new papers from journal RSS feeds, scores them against a configurable research profile using an LLM, and logs relevant hits for later review.

The screening prompt is shaped by a profile derived from my Zotero library using the <a href="https://github.com/54yyyu/zotero-mcp" target="_blank" rel="noopener noreferrer">zotero-mcp</a> server, which extracts key journals, topics, and methods to ground the relevance scoring in my actual reading history.

<a href="https://github.com/LaineyLouiseWard/research-literature-monitor" class="github-btn" target="_blank" rel="noopener noreferrer">
  View on GitHub →
</a>
