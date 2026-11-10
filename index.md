
# DSC 180A Methodology Assignment 4

**Name:** Ganesh Kumarappan

**Email:** gkumarappan@ucsd.edu

**Section:** Quantization in ML Models

**Mentor:** Arya Mazumdar

## Quarter 2 Project Brainstorming

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic we've covered is KV-cache quantization in LLMs. I found it interesting how methods like KIVI can reduce memory usage by quantizing keys and values differently while trying to preserve model accuracy. It was also interesting to see how different quantization strategies affect attention calculations.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to investigate how different quantization bit widths affect model accuracy and memory efficiency. Specifically, I would compare 2-bit, 4-bit, and 8-bit quantization across different models and datasets to understand when lower precision is worth the tradeoff.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

One change I would make is testing our quantization methods on a wider range of models and prompts. Right now, we're mainly focusing on implementing quantization and measuring reconstruction and attention errors. I think evaluating how those errors affect actual model outputs would give us a better understanding of the practical impact.

**4. What other techniques would you be interested in using in your project?**

I would be interested in exploring adaptive quantization, where different attention layers or tokens use different bit widths depending on their importance. This could potentially reduce memory usage while preserving accuracy better than applying the same quantization method everywhere.
