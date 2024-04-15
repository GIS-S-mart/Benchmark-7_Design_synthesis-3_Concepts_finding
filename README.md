# Benchmark 7. Model-Based Architecture Design Synthesis



## Introduction

- **Disciplines**: This scientific benchmark mainly concerns engineering design, systems engineering, and product lifecycle management communities.
- **Goal**: This scientific benchmark aims to collect and compare competing or complementary contributions claiming to improve the model-based architecture design synthesis process. In this benchmark, Model-Based Architecture Design Synthesis (MBADS) is a computer-based automatic problem-solving process to generate preliminary design solutions that are correct by construction.

## Glossary

An agreed-upon glossary of terms used in this benchmark is proposed below. Contributors should reuse existing terms and definitions from existing standards and not invent new ones unless they have a very specific concept that requires the introduction of a new keyword and definition. Any new keyword and definition must be motivated and explained in the discussion of the repository (e.g. navigate to '*Repositories > Benchmark-0_Template > Discussions*', or [click here](ttps://github.com/GIS-S-mart/Benchmark-7_Design_synthesis-3_Concepts_finding/discussions)).

|                    **Keyword**                    |                         **Synonyms**                         |                        **Definition**                        | **Source** |
| :-----------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|                 Design philosophy                 |                                                              | The axioms, postulates, assumptions, and convictions taken to be true to serve as a premise or starting point for further reasoning and arguments. |            |
|                 Design synthesis                  |                                                              | A problem-solving activity that consists in finding a solution to a set of needs |            |
|                  Design variable                  |                                                              | A design variable is an unknown variable whose value is computed when solving the formal design problem. |            |
|           Model-based design synthesis            |                Computational design synthesis                | A design process which relies on computer-based automatic problem-solving techniques to generate design solutions that are correct by construction. |            |
| Model-based architecture design synthesis (MBADS) |         Computational architecture design synthesis          | A design process which relies on computer-based automatic problem-solving techniques to generate architecture design solutions that are correct by construction. |            |
|          MBADS for system configuration           |                                                              | A MBADS objective that consists in choosing system elements based on a set of compatibility relationships between variants, options and cardinalities |            |
|              MBADS for system sizing              |                                                              | A MBADS objective objective that consists in determining the value of unknown design variables of a system element |            |
|           MBADS for resource allocation           |                                                              | A MBADS objective that consists in allocating hardware and/or software system elements to system functional requirements. |            |
|            MBADS for space allocation             |                                                              | A MBADS objective that consists in defining the bounding box of the subsystems and their spatial position and orientation within a system. |            |
|           MBADS for interfaces routing            |                                                              | A MBADS objective that consists in defining the path and wrapping each physical interface between two subsystems within the system bounding box. |            |
|         MBADS for architecture generation         |                                                              | A MBADS objective that combines at least two of the previous MBADS objectives, whether a logical, abstract architecture design or a physical one which mirrors the implementation. |            |
|                 Modelling method                  | Modelling methodology, modelling process, Modelling guidelines | The procedure to be followed by the practitioners to model the concepts using the preferred modelling language and modelling software. |            |
|                Modelling language                 |                    Standardised notation                     | A language or a standardised notation that is used to encode the system concept elaborated with the conceptual design method. |            |
|                Modelling software                 |                    Modelling environment                     | A software used by a practitioner to model a system concept using a modelling language. |            |


## Research objectives

The primitive research objective pursued by the benchmark community is to improve a model-based architecture design synthesis process, which includes four main activities: 1) requirements definition, 2) concept finding, 3) problem modelling, and 4) system sizing.

## Benchmarking

Once applied to the collection of benchmarks, the claimed contributions must provide empirical evidence that the research objectives have been met. The design inputs of each activity of the Model-Based Architecture Design Synthesis process change according to the MBADS objective. For instance, a research proposal can contribute to MBADS for system sizing without contributing to MBADS for interfaces routing. In addition, a research proposal can contribute to one activity of the MBADS process (e.g., concept finding) without contributing to other activities.

Hence, the MBADS benchmark is decomposed into 6 benchmarks.

<table class="tg">
<thead>
  <tr>
    <th class="tg-2eyt"></th>
    <th class="tg-44qx">MBADS for System Configuration</th>
    <th class="tg-44qx" colspan="2">MBADS for System Sizing</th>
    <th class="tg-44qx">MBADS for Resource Allocation</th>
    <th class="tg-44qx">MBADS for Space Allocation</th>
    <th class="tg-44qx">MBADS for Interface Routing</th>
    <th class="tg-44qx">MBADS for Architecture Generation</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-lboi"><b>Requirements development</b></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-0lax"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-lboi" rowspan="2"><b>Concept finding</b></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8">001 - Lean</td>
    <td class="tg-0lax" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_System_Sizing-Concept_Finding.md">Benchmark</a></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-0lax" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_Architecture_Generation-Concept_Finding.md">Benchmark</a></td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">002 - C&CA</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-lboi" rowspan="2"><b>Problem modelling</b></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8">001 - DEPS</td>
    <td class="tg-0lax" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_System_Sizing-Problem_Modeling.md">Benchmark</a></td>
    <td class="tg-0lax"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
   <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">002 - Ibex?</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-lboi" rowspan="2"><b>Problem solving</b></td>
    <td class="tg-9wq8"></td>
      <td class="tg-9wq8">001 - DEPS + DEPS Studio</td>
    <td class="tg-0lax" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_System_Sizing-Problem_Solving.md">Benchmark</a></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">002 - DEPS + Ibex</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
</tbody>
</table>


## Meta-Analysis

A meta-analysis is the analysis of all results of the benchmark for the purpose of integrating the findings. Meta-analytic results are the most trustworthy source of evidence.

## References

- 

