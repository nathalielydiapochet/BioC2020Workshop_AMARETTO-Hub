# Bioconductor 2020 Workshop on *AMARETTO-Hub
## _AMARETTO-Hub for Knowledge Graph-based Embedding of *AMARETTO Multimodal and Multiscale Network-based BioMedicine_

# Instructors

Nathalie Pochet (npochet@broadinstitute.org)

Mohsen Nabian (mnabian@broadinstitute.org)

Artur Manukyan (amanukya@broadinstitute.org)


# Workshop Description

## Title

AMARETTO-Hub: a Knowledge Graph-based software platform that leverages the *AMARETTO software toolbox for multimodal and multiscale network-based fusion of multi-omics, clinical, imaging, and perturbation data across studies of patients, etiologies and model systems of cancer.

## Contents

We present AMARETTO-Hub as a Knowledge Graph-based software platform that leverages neo4j and shiny to embed and interactively interrogate results generated by the *AMARETTO software toolbox that offers modular and complementary solutions to multimodal and multiscale network-based fusion of multi-omics, clinical, imaging, and perturbation data across studies of patients, etiologies and model systems of cancer.

For several Use Cases of cancer, we provide biomedical users with R Jupyter Notebook workflows that run the Bioconductor and GitHub repositories on Google Colaboratory, and that generate HTML reports comprising queryable tables and heatmap and graph visualizations in an automated manner, and additionally provide users with neo4j-embedded shiny interactive representation and querying tools that redirect users to *AMARETTO-generated HTML reports.

(1) The AMARETTO algorithm learns networks of regulatory circuits - circuits of drivers and their target genes - from functional genomics or multi-omics data and associates these circuits to clinical, molecular and imaging-derived phenotypes within each biological system (e.g., model systems or patients).

(2) The Community-AMARETTO algorithm learns subnetworks of regulatory circuits that are shared or distinct across networks derived from multiple biological systems (e.g., model systems and patients, cohorts and individuals, diseases and etiologies, in vitro and in vivo systems)

(3) The Imaging-AMARETTO algorithm maps radiography and histopathology imaging data onto the patient-derived multi-omics networks for imaging diagnostics and prognostics to identify clinically relevant imaging biomarkers and decipher their underlying molecular mechanisms.

(4) The AMARETTO-Hub platform for Knowledge Graph-based embedding of knowledge learned via multimodal and multiscale network-based data fusion in previous steps. In these complex graphs, nodes and edges represent the diverse range of biomedical entities and the relationships between them, respectively. Graph-based embedding enables querying these complex graph-structured representations in a more sophisticated, efficient and user-friendly manner than can otherwise be accomplished by table representations alone.

We demonstrate the utility of AMARETTO-Hub via several Use Cases of pan-cancer and pan-etiology of cancer applications, investigating how complementary drug treatments target shared and distinct disease mechanisms, optimizing a trade-off between maximizing efficacy and minimizing toxicity.

## Resources

<methods description>
<use cases description>
<add links to resources: bioc, github, notebooks, html, neo4j, shiny>
  
## Audience

<audience: both biomed users for user-friendly tools, and software devs to enable further devs>

## Time outline

An outline of the 45-minute workshop:

| Activity                                        | Time |
|-------------------------------------------------|------|
| Introduction to the AMARETTO software toolbox   |  5m  |
| Introduction to the Use Cases of AMARETTO       |  5m  |
| Applying AMARETTO resources to the Use Cases    | 25m  |
| Interpreting AMARETTO results for the Use Cases | 10m  |





# Workshop Description

Along with the topic of your workshop, include how students can expect
to spend their time. For the description may also include information
about what type of workshop it is (e.g. instructor-led live demo, lab,
lecture + lab, etc.). Instructors are strongly recommended to provide
completely worked examples for lab sessions, and a set of stand-alone
notes that can be read and understood outside of the workshop.

## Pre-requisites

List any workshop prerequisites, for example:

* Basic knowledge of R syntax
* Familiarity with the GenomicRanges class
* Familiarity with xyz vignette (provide link)

List relevant background reading for the workshop, including any
theoretical background you expect students to have.

* List any textbooks, papers, or other reading that students should be
  familiar with. Include direct links where possible.

## Workshop Participation

Describe how students will be expected to participate in the workshop.

## _R_ / _Bioconductor_ packages used

List any _R_ / _Bioconductor_ packages that will be explicitly covered.

## Time outline

An example for a 45-minute workshop:

| Activity                     | Time |
|------------------------------|------|
| Packages                     | 15m  |
| Package Development          | 15m  |
| Contributing to Bioconductor | 5m   |
| Best Practices               | 10m  |

# Workshop goals and objectives

List "big picture" student-centered workshop goals and learning
objectives. Learning goals and objectives are related, but not the
same thing. These goals and objectives will help some people to decide
whether to attend the conference for training purposes, so please make
these as precise and accurate as possible.

*Learning goals* are high-level descriptions of what
participants will learn and be able to do after the workshop is
over. *Learning objectives*, on the other hand, describe in very
specific and measurable terms specific skills or knowledge
attained. The [Bloom's Taxonomy](#bloom) may be a useful framework
for defining and describing your goals and objectives, although there
are others.

## Learning goals

Some examples:

* describe how to...
* identify methods for...
* understand the difference between...

## Learning objectives

* analyze xyz data to produce...
* create xyz plots
* evaluate xyz data for artifacts

### A note about learning goals and objectives (#bloom)

While not a new or modern system for thinking about learning,
[Bloom's taxonomy][1] is one useful framework for understanding the
cognitive processes involved in learning. From lowest to highest
cognitive requirements:

1. Knowledge: Learners must be able to recall or remember the
   information.
2. Comprehension: Learners must be able to understand the information.
3. Application: Learners must be able to use the information they have
   learned at the same or different contexts.
4. Analysis: Learners must be able to analyze the information, by
   identifying its different components.
5. Synthesis: Learners must be able to create something new using
   different chunks of the information they have already mastered.
6. Evaluation: Learners must be able to present opinions, justify
   decisions, and make judgments about the information presented,
   based on previously acquired knowledge.

To use Bloom's taxonomy, consider the following sets of verbs and
descriptions for learning objectives:

1. Remember: Memorize, show, pick, spell, list, quote, recall, repeat,
   catalogue, cite, state, relate, record, name.
2. Understand: Explain, restate, alter, outline, discuss, expand,
   identify, locate, report, express, recognize, discuss, qualify,
   covert, review, infer.
3. Apply: Translate, interpret, explain, practice, illustrate,
   operate, demonstrate, dramatize, sketch, put into action, complete,
   model, utilize, experiment, schedule, use.
4. Analyze: Distinguish, differentiate, separate, take apart,
   appraise, calculate, criticize, compare, contrast, examine, test,
   relate, search, classify, experiment.
5. Evaluate: Decide, appraise, revise, score, recommend, select,
   measure, argue, value, estimate, choose, discuss, rate, assess,
   think.
6. Create: Compose, plan, propose, produce, predict, design, assemble,
   prepare, formulate, organize, manage, construct, generate, imagine,
   set-up.

[1]: https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/ "Bloom's Taxonomy"




