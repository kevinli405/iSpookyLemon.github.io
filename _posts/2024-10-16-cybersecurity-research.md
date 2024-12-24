---
layout: post
title: "Cybersecurity Research"
date: 2023-10-16
description: "Research published in 2023 ACM CCS conducted with professors and PHD students at the University of Kansas - Summer 2023"
permalink: "cybersecurity-research"
tags: [Python, Web Scraping]
---

![ACM Website Screenshot](assets/images/cybersecurityresearch.png)

Working with a team at the University of Kansas, I analyzed the trends of ethical considerations in cybersecurity papers over roughly the past decade. 

First, we looked at existing ethical guidelines regarding cybersecurity research. We found that many cybersecurity conferences are now including “ethics” sections in their call for papers that explicitly state the regulations and procedures that researchers have to follow. 

After doing an initial survey of the current ethical guidelines, we collected a dataset of papers from top cybersecurity conferences to see how ethical considerations have changed over time. I created this dataset by scraping these cybersecurity conference websites using the Python libraries BeautifulSoup and Selenium. Next, I conducted a keyword search of the dataset to find mentions of words such as “ethics” or “institutional review board”. Then, we further separated the papers into smaller subfields based on the research topic of the paper. Finally, we used this information to compare the ethical considerations addressed across different subfields of cybersecurity research. 

Our results showed that there has been an overall upward trend in how often ethical considerations are addressed in cybersecurity papers. Furthermore, the data shows that more researchers are seeking approval from an institutional review board or an ethics committee before conducting their studies. Additionally, some subfields of cybersecurity such as those dealing with authentication and cyberattacks have a greater focus on ethical considerations because they are at the highest risk of potentially unethical behavior. Overall, we saw a generally positive trend in the cybersecurity research community where researchers have begun to pay more attention to the ethical impacts of their research.


- **Technologies**: Python, BeautifulSoup, Selenium
- **Publication Link**: [https://dl.acm.org/doi/abs/10.1145/3576915.3624378](https://dl.acm.org/doi/abs/10.1145/3576915.3624378)