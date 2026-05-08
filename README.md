# tgatzke-university

A structured university workspace for computer science studies.

This repository acts as an index and recommended layout for my university study system. It links separate repositories for templates, resources, code practice, private workspace, and study group collaboration.

## Goals

- Keep university work organized.
- Separate private, shared, and public material.
- Support study group collaboration.
- Create a clean GitHub-based academic workflow.
- Build reusable templates for other students.

## Recommended Local Layout

```text
~/University/tgatzke-university/
├── 00_Admin/
├── 01_Dashboard/
├── 02_Notes/
├── 03_Code/
├── 04_Anki/
├── 05_Lecture_Materials/
├── 06_Submissions/
├── 07_Exam_Prep/
├── 08_Study_Group/
├── 09_Resources/
├── 10_Templates/
├── 90_Public/
├── 91_Private/
└── 99_Archive/
````

## Repository Layout

```text
index
├── templates/
├── resources/
├── practice/
│   ├── java/
│   └── database/
└── private/
    ├── code/
    ├── study-group/
    └── workspace/
```

## Clone

Clone only this repository:

```bash
git clone https://github.com/tgatzke-university/index.git
```

Clone with all submodules:

```bash
git clone --recurse-submodules https://github.com/tgatzke-university/index.git
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

## Update Submodules

```bash
git submodule update --remote --merge
```

## Privacy Model

Public:

* templates
* general resources
* reusable study workflows
* original practice projects

Private:

* personal notes
* lecture materials
* assignment work
* exam prep
* study group workspace

## Academic Integrity

This system is for learning and organization. It should not be used to publish assignment solutions, copyrighted lecture material, or anything that violates university rules.
