---
name: bullshit-master
description: Transform casual, vague, or task-oriented text into one concise, professional, context-aware paragraph with evidence-based value enhancement and value elevation. Use for rewriting, polishing, reports, emails, project summaries, performance statements, technical documents, and finance or risk-management writing; trigger on requests such as optimize, polish, rewrite, 优化文本, 润色表达, 改写句子, 写得更专业, 修改汇报材料, or 优化邮件.
---

# Bullshit Master

## Objective

Rewrite text so that it is clear, professional, logically structured, and useful while preserving the user's meaning and factual scope.

Make real contributions and value visible. Do not replace weak wording with empty jargon.

## Workflow

### 1. Understand the request

Determine:

- audience
- scenario
- purpose
- expected tone
- whether the user needs direct polishing, value enhancement, or a more formal rewrite

Infer reasonable defaults when the context is clear. Ask a question or provide limited alternatives only when a missing choice would materially change the result.

### 2. Detect terminology

Identify abbreviations, industry terminology, product names, company names, methodologies, and professional frameworks.

Proceed directly when the terminology is common and clearly used. Read `references/research-guidance.md` only when a term is unfamiliar, ambiguous, proprietary, or dependent on current external information.

Research must improve understanding without adding unrelated facts, unsupported outcomes, or exaggerated contributions.

### 3. Select modes and references

Combine modes when the request spans multiple objectives.

| Mode | Use for | Read |
|---|---|---|
| General | Everyday rewriting and clarity | No reference required |
| Business | Emails and workplace communication | `references/business-writing.md` |
| Value Enhancement | Projects, achievements, and performance statements | `references/value-enhancement.md` |
| Finance | Financial analysis, credit risk, models, and risk reports | `references/finance-writing.md` |
| Technical | Technical documents and methodology descriptions | `references/technical-writing.md` |
| Report | Management updates, project summaries, and executive materials | `references/report-writing.md` |
| Research-Assisted | Unfamiliar or ambiguous professional context | `references/research-guidance.md` |

For finance or technical project summaries, combine the domain mode with Value Enhancement.

### 4. Build an evidence map

Separate the input into:

1. explicit facts
2. inherent capability contribution
3. supported business or management impact
4. evidence-supported value elevation

Keep status distinctions accurate, including completed, in progress, planned, pending, validated, and expected.

### 5. Rewrite

Improve wording, flow, logical sequence, and professional visibility.

For business, finance, project, and performance scenarios, use this progression when supported:

Professional Fact

→

Capability Contribution

→

Business Impact

→

Value Elevation

Integrate the supported layers naturally into one coherent paragraph.

### 6. Quality check

Verify:

- the original intent is preserved
- no facts, scope, deliverables, methods, metrics, or results were invented
- completed work and recommendations are not mixed
- value claims stay within the evidence boundary
- terminology remains accurate
- the result is concise, natural, and free of empty buzzwords

## Evidence Boundary

### Allowed

- explain capabilities inherent in explicitly mentioned work
- connect a model to its standard assessment or decision-support purpose
- connect data cleaning to data quality and downstream analytical readiness
- connect recurring updates to continuous monitoring or management
- connect feedback-driven revision to iterative improvement
- connect reusable outputs to reusable assets or capability foundations
- connect related deliverables to an integrated working capability

### Avoid

- adding unmentioned modules, methods, processes, or deliverables
- turning development into validation unless validation was stated
- claiming financial outcomes or quantitative improvement without evidence
- claiming strategic transformation, organization-wide impact, or industry leadership
- using “闭环,” “体系化,” “持续机制,” or similar elevated language for one isolated task without supporting context
- replacing concrete information with vague consulting language

## Value Elevation

Use Value Elevation to explain the broader capability, management mechanism, or sustainable foundation supported by the facts.

Preferred mappings:

| Evidence | Supported elevation |
|---|---|
| recurring updates, reviews, or monitoring | continuous monitoring or management mechanism |
| feedback followed by revision | iterative improvement loop |
| connected data, model, report, or process work | integrated capability |
| reusable outputs or accumulated assets | reusable asset or long-term capability foundation |
| risk quantification work | more systematic, data-driven risk management |

Value Elevation must synthesize existing facts. It must not introduce a new achievement.

## Output Contract

By default, return only the polished result.

For business, finance, project, and performance scenarios:

- return one paragraph
- integrate professional facts, capability contribution, business impact, and supported value elevation
- keep business impact and value elevation shorter than the factual description
- do not display headings such as Original, Optimized Version, Value Added, Impact Enhancement, Value Elevation, or Key Improvements
- do not explain the rewriting process

For simple general, email, or technical rewrites, include only the layers that improve the requested communication. Do not force value elevation where it is not supported or useful.

Provide the original text, separate analysis, research context, key improvements, or style variations only when the user explicitly requests them.

### Example

Input:

本项目完成20张数据表的清洗与整合，构建120个还款行为变量，并完成LGD模型开发。经验证，新模型的预测能力较上一版本进一步提升。

Output:

本项目围绕信用风险量化评估需求开展数据治理与模型优化工作，完成20张业务数据表的清洗与整合，夯实模型建设数据基础；构建120个还款行为特征变量，丰富客户行为风险刻画维度，完善风险识别特征体系；完成LGD模型开发与效果验证，新模型预测能力较上一版本进一步提升，增强违约损失水平量化评估能力，为信用风险计量及精细化风险管理提供更加有效的模型支持，进一步完善以数据和模型为支撑的信用风险量化管理体系。

## Final Rule

Understand more. Assume less. Express better.
