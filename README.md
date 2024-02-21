# FACTIFY5WQA Dataset

FACTIFY5WQA is a fact verification dataset designed to determine the veracity of claims based on provided evidence or documents. The dataset introduces a novel approach using a question-answer framework to assess the entailment of answers from claims and evidence. Unlike current fact-checking systems, which often lack human interpretability and rely solely on numerical scores, FACTIFY5WQA aims to provide a more nuanced understanding of facts by incorporating human-like reasoning processes.

## Overview

The dataset consists of natural language understanding tasks where the objective is to determine whether the given evidence supports the provided claims. It includes specific questions tailored to each claim and its context. The input (X) comprises claims, questions, and evidence, while the output (Y) categorizes the relationship between the claim and evidence as "support", "refute", or "neutral".

## Metadata

- **id:** Unique identifier for each instance.
- **claim_id:** Identifier associated with the claim.
- **claim:** The statement or claim being made.
- **evidence:** Relevant information and context supporting or relating to the claim.
- **question:** A list of questions related to the claim.
- **claim_answer:** The expected or claimed answer to each question.
- **evidence_answer:** The relevant answer extracted from the evidence.
- **label:** Indicates whether the evidence supports the claim, refutes the claim, or is inconclusive.

## Purpose

FACTIFY5WQA aims to enhance fact-checking systems by providing a transparent and interpretable framework for assessing the veracity of claims. By incorporating a 5W (Who, What, Where, When, Why) framework for question-answer-based fact explainability, the dataset facilitates a more targeted and logical approach to verifying claims, ultimately aiding fact-checkers in making informed decisions.

**Reference:** https://competitions.codalab.org/competitions/35153 
