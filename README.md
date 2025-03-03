# Critical CVE List

This hobby project is a by-product of my daily CVE critical email.  
![cve-critical-email](https://blob.blog.huzky.dev/cvelist-v5-email.png)  

It aims to summarize CVE tags list from the cve json for easier categorization for the CVE using LLM.  
It also helps me to observe the LLM behavior so that I can tune the prompt.

The source is from daily archive of [cvelistv5](https://github.com/CVEProject/cvelistV5).  
CVE entries will be CRITICAL filtered and sent to LLM for summarization 02:00 AM everyday.  
The model used is `meta-llama/Llama-3.3-70B-Instruct-Turbo` for cost / performance measure.  

### Why CRITICAL only?
It will be too much entries to be processed.  
I use online inference platform to process data.  
Keeping it CRITICAL makes the cost predictable.  

P.S. The code itself runs on my homelab, so that there is no guarantee.  
