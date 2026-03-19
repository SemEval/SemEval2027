# Call for SemEval Task Proposals 2027

## Introduction

We invite proposals for tasks to be run as part of SemEval-2027. SemEval (the International Workshop on Semantic Evaluation) is an ongoing series of evaluations of computational semantics systems, organized under the umbrella of SIGLEX, the Special Interest Group on the Lexicon of the Association for Computational Linguistics.

SemEval tasks investigate the nature of meaning in natural languages, exploring how to characterize and compute meaning. This is achieved in practical terms, using shared datasets and standardized evaluation metrics to quantify the strengths and weaknesses and possible solutions. SemEval tasks encompass a broad range of semantic topics from the lexical level to the discourse level, including word sense identification, semantic parsing, coreference resolution, and sentiment analysis, among others.

For SemEval-2027, we welcome tasks that can test an automatic system for semantic analysis of text (e.g., intrinsic semantic evaluation, or an application-oriented evaluation). We especially encourage tasks for languages other than English, cross-lingual tasks, and tasks that develop novel applications of computational semantics. See the websites of previous editions of SemEval to get an idea about the range of tasks explored, e.g., [SemEval-2020](http://alt.qcri.org/semeval2020/) and [SemEval-2021/2026](https://semeval.github.io).

We strongly encourage proposals based on pilot studies that have already generated initial data, evaluation measures, and baselines. In this way, we can avoid unforeseen challenges down the road that may delay the task. We suggest providing a reasonable baseline (e.g., providing a Transformer / LLM baseline for a classification task) apart from the majority vote / random guess.

In case you are not sure whether a task is suitable for SemEval, please feel free to get in touch with the SemEval organizers at <semevalorganizers@gmail.com> to discuss your idea.

## Task Selection

Task proposals will be reviewed by experts, and reviews will serve as the basis for acceptance decisions. Everything else being equal, more innovative new tasks will be given preference over task reruns. Task proposals will be evaluated on:

**Novelty**: Is the task on a compelling new problem that has not been explored much in the community? Is the task a rerun, but covering substantially new ground (new subtasks, new types of data, new languages, etc. - one addition is not sufficient)?

**Interest**: Is the proposed task likely to attract a sufficient number of participants?

**Data**: Are the plans for collecting data convincing? Will the resulting data be of high quality? Will annotations have meaningfully high inter-annotator agreements? Have all appropriate licenses for use and re-use of the data after the evaluation been secured? Have all international privacy concerns been addressed? Will the data annotation be ready on time?

**Evaluation**: Is the methodology for evaluation sound? Is the necessary infrastructure available, or can it be built in time for the shared task? Will research inspired by this task be able to evaluate in the same manner and on the same data after the initial task? Is the task significantly challenging (e.g., room for improvement over the baselines)?

**Impact**: What is the expected impact of the data in this task on future research beyond the SemEval Workshop?

**Ethical**: The data must be compliant with privacy policies. e.g.
- avoid personally identifiable information (PII). Tasks aimed at identifying specific people will not be accepted.
- avoid medical decision making (compliance with HIPAA, do not try to replace medical professionals, especially if it has anything to do with mental health).
- these are representative and not exhaustive.

## Roles

**Lead Organizer** - main point of contact, expected to ensure deliverables are met on time and participate in contributing to task duties (see below).

**Co-Organizers** - provide significant contributions to ensuring the task runs smoothly. Some examples include maintaining communication with task participants, preparing data, creating and running evaluation scripts, leading paper reviewing, and acceptance.

**Advisory Organizers** - more of a supervisor role, may not contribute to detailed tasks, but will provide guidance and support.

## New Tasks vs. Task Reruns

We welcome both new tasks and task reruns. For a new task, the proposal should address whether the task would be able to attract participants. Preference will be given to novel tasks that have not received much attention yet.

For reruns of previous shared tasks (whether or not the previous task was part of SemEval), the proposal should address the need for another iteration of the task. Valid reasons include: a new form of evaluation (e.g., a new evaluation metric, a new application-oriented scenario), new genres or domains (e.g., social media, domain-specific corpora), or a significant expansion in scale. We further discourage carrying over a previous task and just adding new subtasks, as this can lead to the accumulation of too many subtasks. Evaluating on a different dataset with the same task formulation, or evaluating on the same dataset with a different evaluation metric, typically should not be considered a separate subtask.

## Task Organization

We welcome people who have never organized a SemEval task before, as well as those who have. Apart from providing a dataset, task organizers are expected to:

- Verify the data annotations have sufficient inter-annotator agreement.
- Verify licenses for the data allow its use in the competition and afterwards. In particular, text that is publicly available online is not necessarily in the public domain; unless a license has been provided, the author retains all rights associated with their work, including copying, sharing and publishing. For more information, see: https://creativecommons.org/faq/#what-is-copyright-and-why-does-it-matter
- Resolve any potential security, privacy, or ethical concerns about the data.
- Commit to make the data available also after the task in a long-term repository under an appropriate license, preferably using Zenodo: https://zenodo.org/communities/semeval/
- Provide task participants with format checkers and standard scorers.
- Provide task participants with baseline systems to use as a starting point (in order to lower the obstacles to participation). A baseline system typically contains code that reads the data, creates a baseline response (e.g., random guessing, majority class prediction), and outputs the evaluation results. Whenever possible, baseline systems should be written in widely used programming languages and/or should be implemented as a component for standard NLP pipelines.
- Create a mailing list and website for the task and post all relevant information there.
- Create a CodaLab or other similar competition for the task and upload the evaluation script.
- Manage submissions on CodaLab or a similar competition site.
- Write a task description paper to be included in SemEval proceedings, and present it at the workshop.
- Manage participants' submissions of system description papers, manage participants' peer review of each other's papers, and possibly shepherd papers that need additional help in improving the writing.
- Review other task description papers.

## Desk Rejects

- To ensure tasks have sufficient support, we require a minimum of two organizers at the time of proposal submission. A task proposal with only one organizer will be desk-rejected. Running a SemEval task is a significant time commitment; therefore, we highly recommend that a task have at least three-four organizers.
- A person can be a lead organizer on only one task. The second mandatory organizer on the task must be committed to the task as a key co-organizer. Any other organizers (beyond the lead and co-organizer) can participate in other tasks.
- All data should have a research-friendly license. The licensing must be provided in the proposal.
- Task organizers must commit to keeping the data available after the task, either by keeping the task alive, by uploading it to Zenodo or some other public data storage location that will be permanent, and sharing the link with the organizers.

## Important Dates

- **Task proposals due**: 13 April 2026 (Anywhere on Earth)
- **Task selection notification**: 25 May 2026

## Preliminary Timetable

- **Sample data ready**: 15 July 2026
- **Training data ready**: 1 September 2026
- **Evaluation data ready**: 1 December 2026 (internal deadline; not for public release)
- **Evaluation start**: 10 January 2027
- **Evaluation end by**: 31 January 2027 (latest date; task organizers may choose an earlier date)
- **Paper submission due**: February 2027
- **Notification to authors**: March 2027
- **Camera ready due**: April 2027
- **SemEval workshop**: Summer 2027 (co-located with a major NLP conference)

Tasks that fail to keep up with crucial deadlines (such as the dates for having the task and CodaLab website up and dates for uploading sample, training, and evaluation data) may be cancelled at the discretion of SemEval organizers. While consideration will be given to extenuating circumstances, our goal is to provide sufficient time for the participants to develop strong and well-thought-out systems. Cancelled tasks will be encouraged to submit proposals for the subsequent year's SemEval. To reduce the risk of tasks failing to meet the deadlines, we are unlikely to accept multiple tasks with overlap in the task organizers.

## Submission Details

The task proposal should be a self-contained document of no longer than 3 pages (plus additional pages for references). All submissions must be in PDF format, following the [ACL template](https://github.com/acl-org/acl-style-files).

Each proposal should contain the following:

### Overview
- Summary of the task
- Why this task is needed and which communities would be interested in participating
- Expected impact of the task

### Data & Resources
- How the training/testing data will be produced. Please discuss whether existing corpora will be reused.
- Details of copyright and license, so that the data can be used by the research community both during the SemEval evaluation and afterwards
- How much data will be produced
- How data quality will be ensured and evaluated
- An example of what the data would look like
- Resources required to produce the data and prepare the task for participants (annotation cost, annotation time, computation time, etc.)
- Assessment of any concerns with respect to ethics, privacy, or security (e.g., personally identifiable information of private individuals; potential for systems to cause harm)

### Pilot Task (strongly recommended)
- Details of the pilot task
- What lessons were learned, and how these will impact the task design

### Evaluation
- The evaluation methodology to be used, including clear evaluation criteria

### For Task Reruns
- Justification for why a new iteration of the task is needed (see criteria above)
- What will differ from the previous iteration
- Expected impact of the rerun compared with the previous iteration

### Task Organizers
- Names, affiliations, email addresses
- (optional) brief description of relevant experience or expertise
- (if applicable) years and task numbers of any SemEval tasks you have run in the past

Proposals will be reviewed by an independent group of area experts who may not have familiarity with recent SemEval tasks, and therefore, all proposals should be written in a self-explanatory manner and contain sufficient examples.

**Submission webpage**: https://softconf.com/acl2026/semevaltasks2027/

## Chairs

- **Debanjan Ghosh**, Analog Devices, USA
- **Kai North**, Cambium Assessment, USA
- **Ekaterina Kochmar**, Mohamed bin Zayed University of Artificial Intelligence (MBZUAI), UAE
- **Mamoru Komachi**, Hitotsubashi University, Japan
- **Marcos Zampieri**, George Mason University, USA

**Contact**: semevalorganizers@gmail.com