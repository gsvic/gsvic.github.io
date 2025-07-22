---
layout: homepage
---

## About Me

I am a final-year Ph.D. student in Computer Science at Cornell University, advised by Immanuel Trummer.
My research focuses on building GenAI-native data systems that integrate Large Language Models (LLMs) to improve core database functionalities.
I am also deeply interested in database internals, particularly query optimization across heterogeneous engines—including federated and learned query optimization.
Throughout my academic and industry experience, I have built custom components for a variety of data systems, including
Spark SQL, TileDB, Dremio, Presto/Trino, and MonetDB.

## Research Interests

- **Large Language Models & Data Systems:** Systems that harness Large Language Models to enhance and optimize data systems
(GenAI for Data Systems) and design GenAI-native systems that integrate LLMs into their core functionality 
(Data Systems for GenAI).
- **Query Optimization:** Federeted Query Optimization, Learned Query Optimization, Query Engines, Internals


## Education
- **Ph.D. in Computer Science** (Current)  
  Cornell University, Ithaca, NY, USA  
  Advisor: Immanuel Trummer

- **M.Sc. in Computer Science** (2024)  
  Cornell University, Ithaca, NY, USA  
  Advisor: Immanuel Trummer

- **M.Sc. in Computer Science** (2021)  
  National and Kapodistrian University of Athens, Athens, Greece  
  Advisor: Yannis Ioannidis

- **B.Sc. in Informatics** (2017)  
  Ionian University, Corfu, Greece  
  Advisor: Dimitrios Tsoumakos

## Professional Experience
- **Research Intern** (Summer 2025)  
  Gray Systems Lab, Microsoft Research, Mountain View, CA, USA

- **Research Intern** (Summer 2023)  
  Data Systems Group, Microsoft Research, Redmond, WA, USA

- **Research Intern** (Summer 2022)  
  Almaden Research Center, IBM Research, San Jose, CA, USA

- **Senior Software Engineer** (2019 - 2021)  
  TileDB Inc., Boston, MA, USA

- **Software Engineer** (2018-2019)  
  Unravel Data Systems, Palo Alto, CA, USA

- **Data Engineer** (April 2018- Oct. 2018)  
  Aisera, Palo Alto, CA, USA

## Projects
A small summary of my projects is provided below. For more details, refer to the [publications](#publications) 
section.
### SwellDB: GenAI-Native Query Processing via On-the-Fly Table Generation
SwellDB is a GenAI-native data system that generates tables on-the-fly using LLMs.
### λ-Tune: LLMs for Database System Tuning
A system that uses Large Language Models to tune database systems. It leverages LLMs to analyze the input workload 
(SQL queries) and generate full configuration scripts.
### DBG-PT: Query Plan Debugging using Large Language Models
A system that leverages LLMs to resolve query plan regressions. It uses the LLMs in order to compare a regressed query
plan with a previously efficient one and recommend workarounds.

### A Sample Index for MonetDB
An index structure for MonetDB that accelerates the sampling operator (`SAMPLE` clause). It is based on random number
generation and priority queues (min-heaps). The thesis can be found in this 
[link](https://pergamos.lib.uoa.gr/uoa/dl/object/2942814/file.pdf).

## News

- **[June 2025]** My proposal with title "SwellDB: GenAI-Native Query Processing via On-the-Fly Table Generation" was accepted at VLDB 2025 PhD Workshop!
- **[June 2025]** Our paper "Rethinking Federated Query Optimization: From Laptops to Data Warehouses" was accepted at CDMS at VLDB 2025!
- **[May 2025]**  I am joining the Gray Systems Lab at Microsoft as a Research Intern this summer!

{% include_relative _includes/publications.md %}