<div align="center">

# SimonLecake · AI Application Portfolio

### Turning business problems into usable, inspectable AI workflows.

LLM Evaluation · Retrieval-Augmented Generation · Analytics Agents · Computer Vision

[简体中文](README.md) · **English** · [GitHub profile](https://github.com/SimonLecake)

</div>

**Source status: all four project repositories are Public. Follow the repository links below for source code, documentation and usage instructions.**

## Four projects, four application contexts

My work focuses on the full application workflow: understanding requirements, selecting models and tools, organizing data, building interfaces, and designing verification and human feedback around the results.

| Project | Problem | Representative design | Repository and case study |
| --- | --- | --- | --- |
| **[JD Evaluation Calibrator](https://github.com/SimonLecake/jd-rewrite-skill)** | AI and human reviewers interpret hiring requirements differently | 17 error patterns, criteria calibration and sample-based review | [View source →](https://github.com/SimonLecake/jd-rewrite-skill) · [Case study](projects/jd-evaluation-calibrator.en.md) |
| **[Bilibili Knowledge Assistant](https://github.com/SimonLecake/bilibili-knowledge-assistant)** | Videos and notes are difficult to search and reuse together | Transcription, document ingestion, multi-query RAG and rank fusion | [View source →](https://github.com/SimonLecake/bilibili-knowledge-assistant) · [Case study](projects/bilibili-knowledge-assistant.en.md) |
| **[ChatBI Stock Assistant](https://github.com/SimonLecake/chatbi-stock-assistant)** | Answering a data question requires SQL, calculations and charts | Natural-language queries, three analysis tools and read-only data access | [View source →](https://github.com/SimonLecake/chatbi-stock-assistant) · [Case study](projects/chatbi-stock-assistant.en.md) |
| **[Steel Defect Inspection](https://github.com/SimonLecake/steel-defect-inspection)** | Detection is disconnected from review and error-case collection | YOLO / VLM alternatives, inspection records, review and export | [View source →](https://github.com/SimonLecake/steel-defect-inspection) · [Case study](projects/steel-defect-inspection.en.md) |

## Watch the applications in use

Three author-recorded demonstrations. Select a cover or “Watch demo” to open the player in the corresponding project README. Continue there for architecture, source code and usage instructions.

| Steel Defect Inspection | Bilibili Knowledge Assistant | ChatBI Stock Assistant |
| :---: | :---: | :---: |
| [![Steel Defect Inspection](assets/demos/steel.jpg)](https://github.com/SimonLecake/steel-defect-inspection/blob/main/README.en.md#recorded-demo) | [![Bilibili Knowledge Assistant](assets/demos/bilibili.jpg)](https://github.com/SimonLecake/bilibili-knowledge-assistant/blob/main/README.en.md#recorded-demo) | [![ChatBI Stock Assistant](assets/demos/chatbi.jpg)](https://github.com/SimonLecake/chatbi-stock-assistant/blob/main/README.en.md#recorded-demo) |
| **03:10** · [▶ Watch demo](https://github.com/SimonLecake/steel-defect-inspection/blob/main/README.en.md#recorded-demo) | **04:05** · [▶ Watch demo](https://github.com/SimonLecake/bilibili-knowledge-assistant/blob/main/README.en.md#recorded-demo) | **01:41** · [▶ Watch demo](https://github.com/SimonLecake/chatbi-stock-assistant/blob/main/README.en.md#recorded-demo) |
| Detection → review → export | Video → summary and storage → QA | Question → analysis tools → tables and charts |

Recordings, architectural illustrations and synthetic-data charts are labeled separately. A demonstration is not an independent model-quality evaluation.

## What the projects demonstrate

| Capability | Evidence in the projects |
| --- | --- |
| **Clarifying business rules** | Turning hiring requirements into explicit criteria, separating preferences from rejection conditions |
| **Building complete workflows** | Connecting transcription, retrieval, database queries, analysis tools and user interfaces |
| **Making results inspectable** | Preserving source information, structured outputs, inspection records and human review |
| **Reasoning about engineering choices** | Balancing local storage, service calls, read-only access, retrieval strategies and operating costs |
| **Separating implementation from effectiveness** | Distinguishing engineering checks, model quality, historical observations and proposed work |

The JD project emphasizes evaluation workflow design. Bilibili and ChatBI emphasize application implementation and integration. Steel inspection builds on existing learning materials and highlights engineering organization, adaptation and verification. Each case describes its contribution scope and limitations.

## Reading and technical discussion

- **Quick review:** open a Public repository from the table, or read its concise case study.
- **Technical review:** project READMEs provide architecture and usage instructions alongside browsable source; case studies explain value, tradeoffs and verification scope.
- **Further discussion:** use the contact details in my CV or application materials to discuss implementation details or arrange a demonstration.

This portfolio collects project descriptions, screenshots and demonstrations. Source code is published in the four Public repositories linked above; business data, personal corpora, credentials and model weights are excluded from the portfolio. Public visibility and reuse permissions are documented separately: no common open-source license has been added, so consult each project’s licensing and third-party provenance notes before reuse. [Publication scope and asset notes](PUBLICATION.md)
