---
name: bullshit-master
description: Transform casual, vague, or informal text into professional, polished, and context-aware expressions. Use when users ask to rewrite, polish, optimize, or improve writing.
---

# Bullshit Master

## Purpose

Bullshit Master is an AI writing optimization skill that transforms casual, vague, or poorly structured expressions into clear, professional, and value-oriented communication.

The goal is not to change the original meaning, but to improve:

- clarity
- professionalism
- logical structure
- communication effectiveness
- business value expression


## Philosophy

Bullshit Master does not create meaningless jargon.

It helps users express real ideas, contributions, and value in a clearer and more professional way.

Professional communication should make value visible, not make words empty.


## When to use

Use this skill when users request:

- optimize text
- polish writing
- rewrite sentences
- make expression more professional
- improve reports, emails, documents
- improve communication quality
- make wording more formal
- optimize business materials
- 优化文本
- 润色表达
- 改写句子
- 写得更专业
- 修改汇报材料
- 优化邮件

---

# Workflow

When receiving text:


## Step 0: Understand User Intent

Determine:

- target audience
- expected tone
- communication purpose
- whether the user wants optimization, value enhancement, or professional rewriting


If unclear:

- ask clarification
- or provide multiple styles


---

## Step 1: Identify Context

Determine:

- writing scenario
- industry context
- target audience
- communication objective


Common scenarios:

- Business communication
- Financial analysis
- Risk management
- Technical documentation
- Project summary
- Management reporting

---


## Step 1.5: Professional Term Detection

Before optimization, identify whether the input contains terms that may affect expression accuracy.

Detect:

- technical abbreviations
- industry-specific terminology
- product names
- company names
- methodology names
- professional frameworks


Examples:


Input:

协助客户建设RAG智能风控系统


Detection:

Professional Terms:
- RAG
- 智能风控系统


Decision:

If terminology understanding affects optimization quality:

Activate Research Assisted Mode.

---

## Step 2: Select Optimization Mode

Select one or more optimization modes based on context.

Multiple modes should be combined when multiple objectives exist.

Research Assisted Mode can be combined with other modes.

Examples:

| Scenario | Mode |
|---|---|
| Unknown professional terminology | Research Assisted Mode |
| Credit risk term optimization | Research Assisted Mode + Finance Mode |
| Technical concept explanation | Research Assisted Mode + Technical Mode |
| Consulting proposal improvement | Research Assisted Mode + Value Enhancement Mode |

---

## Step 3: Determine Research Requirement

Check whether the input contains:

- professional abbreviations
- industry-specific terminology
- technical concepts
- company or product names
- unclear domain expressions


If domain understanding is required:

Automatically activate Research Assisted Mode.

Only ask user preference when:

- research may significantly change output direction
- external information is required
- multiple interpretations exist


Options:

1. Direct Optimization

Optimize using current understanding.


2. Research-Assisted Optimization

Research terminology and domain context before optimization.


Use:

- references/research-guidance.md

---

## Step 4: Apply Relevant Guidelines

Use corresponding reference materials when available.

If multiple modes apply, combine relevant guidelines.


---

## Step 5: Rewrite

Improve the text while:

- preserving original meaning
- avoiding unsupported assumptions
- maintaining factual accuracy
- improving professional expression
- highlighting actual value


---

## Step 6: Quality Check

Verify:

- no fabricated information
- no exaggerated claims
- no meaningless buzzwords
- no change of original intent

---

# Optimization Modes


## General Mode

Focus on:

- clarity
- readability
- natural expression
- preserving original intent

Use when no specific scenario is identified.


---

## Business Mode

Focus on:

- professionalism
- concise communication
- executive-friendly wording
- clear action direction


Suitable for:

- emails
- workplace communication
- business documents


---

## Value Enhancement Mode

Focus on:

- highlighting business value
- explaining impact and contribution
- connecting actions with outcomes
- transforming task descriptions into achievement-oriented expressions


### Transformation Pattern

Convert:

Task Description

↓

Capability Building

↓

Business Impact


Example:

Input:

帮助客户开发A卡


Transformation:

Task:

开发A卡


Capability:

建设信用风险评估体系


Business Impact:

提升客户风险识别及精细化管理能力


Suitable for:

- project summaries
- performance reports
- consulting documents
- business proposals


---

## Finance Mode

Focus on:

- objective risk expression
- analytical tone
- professional financial terminology
- avoiding emotional wording


Use when:

- writing risk reports
- describing model performance
- preparing financial analysis
- communicating risk management topics
- credit scoring
- A-card / B-card development
- risk model development
- credit risk modeling


Suitable for:

- risk reports
- model development documents
- credit risk analysis
- financial analysis


### Finance Domain Enhancement Rules

For finance and risk-related scenarios:

Do not only describe technical activities.

Always connect:

Technical Work

↓

Risk Management Capability

↓

Business Value


Example:


Input:

帮助客户开发A卡


Avoid:

协助客户完成A卡开发工作。


Prefer:

协助客户完成A卡体系建设，构建基于数据驱动的信用风险评估能力，完善客户准入及风险分层管理体系，提升风险管理精细化水平。


---

## Technical Mode

Focus on:

- accuracy
- logical structure
- technical terminology


Use for:

- technical documents
- system design documents
- methodology explanations


---

## Report Mode

Focus on:

- structured analysis
- objective tone
- formal expression
- decision-support perspective


Use for:

- management reports
- project summaries
- executive presentations

---

## Research Assisted Mode

Purpose:

Understand professional concepts before rewriting.


Research Process:

1. Identify unknown terms
2. Understand domain meaning
3. Determine business context
4. Apply optimized expression


Important:

Research should improve accuracy,
not introduce additional claims.

---


# Reference Materials

Use relevant reference materials according to selected modes.


## Value Enhancement Mode

Read:

- references/value-enhancement.md


Use when:

- summarizing achievements
- writing project outcomes
- describing business value


---

## Finance Mode

Read:

- references/finance-writing.md


Use when:

- writing risk documents
- describing model performance
- explaining credit risk scenarios
- writing financial analysis


---

## Business Mode

Read:

- references/business-writing.md


Use when:

- writing emails
- preparing workplace communication
- creating management updates


---

## Technical Mode

Use when available:

- references/technical-writing.md


---

## Report Mode

Use when available:

- references/report-writing.md

---

## Research Assisted Mode

Read:

- references/research-guidance.md


Use when:

- professional terminology needs clarification
- industry context is unclear
- technical concepts require deeper understanding
- user requests deep optimization

---

# Output Format

Always return:

## Original

[Original text]


## Optimized Version

[Improved text]


## Value Added

Mandatory for project, finance, and business scenarios.

Explain:

- business value
- technical contribution
- expected impact


## Style Variations

Provide different styles when useful.

Do not generate unnecessary variations for simple requests.

Examples:

- concise version
- formal version
- executive version


## Key Improvements

Explain:

- wording improvements
- structure improvements
- tone adjustments
- value improvements


## Research Context

Only include when Research-Assisted Optimization is activated.

Do not include unnecessary research explanations for common expressions.

Explain:

- identified professional terms
- understood domain context
- applied knowledge


### Example

Input:

协助客户建设RAG智能风控系统


Research Context:

Detected Terms:

- RAG


Understanding:

- Retrieval-Augmented Generation
- A technology combining external knowledge retrieval with generative models


Applied Knowledge:

- Used professional terminology accurately
- Connected technical concepts with business scenarios
- Improved expression quality without introducing unsupported claims

---

# Quality Control

Avoid:

- meaningless buzzwords
- excessive formal expressions
- inflated claims
- changing original intent
- unnecessary complexity
- vague statements without actionable meaning


Professional writing should be:

- clear
- accurate
- specific
- useful

---

# Rules

- Do not fabricate information
- Do not exaggerate facts
- Keep technical accuracy
- Prefer concise and professional expressions
