---
title: "Reinforcement Learning-Enhanced Cloud-Based Open Source Analog Circuit Generator for Standard and Cryogenic Temperatures in 130-nm and 180-nm OpenPDKs"
collection: publications
permalink: /publications/2024-11-20-reinforcementOpenfasoc-number-1/
excerpt: 'Ali Hammoud*, Wen Tian*, Anhang Li*, Ayushman Tripathi, Karthik Lakshmanan, Harsh Khandeparkar, Ryan Wans, Gregory Kielian, Boris Murmann, Dennis Sylvester, Mehdi Saligane'
date: 2024-06-01
venue: '2024 ACM/IEEE International Conference on Computer‑Aided Design (ICCAD 2024)'
paperurl: 'http://wen-tian-pineapple.github.io/files/1500_Final_Manuscript.pdf'
citation: # 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

This work introduces an open-source, Process Technology-agnostic framework for hierarchical circuit netlist, layout, and Reinforcement Learning(RL) optimization. The layout, netlist, and optimization python API is fully modular and publicly installable. It features a bottom-up hierarchical
construction, which allows for complete design reuse across provided PDKs. The modular hierarchy also facilitates parallel circuit design iterations on cloud platforms. To illustrate its capabilities, a two-stage OpAmp with a 5T first-stage, commonsource second-stage, and miller compensation is implemented. We instantiate the OpAmp in two different open-source process design kits (OpenPDKs) using both room-temperature models and cryogenic (4K) models. With a human designed version as the baseline, we leveraged the parameterization capabilities of the framework and applied the RL optimizer to adapt to the power consumption limits suitable for cryogenic applications while maintaining gain and bandwidth performance. Using the modular RL optimization framework we achieve a 6x reduction in power consumption compared to manually designed circuits while maintaining gain to within 2%.

[Download paper here](http://wen-tian-pineapple.github.io/files/1500_Final_Manuscript.pdf)