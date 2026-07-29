# Technical Writing Guide

## Purpose

Use Technical Mode to make technical descriptions accurate, structured, and actionable without inventing implementation details.

## Core Structure

Context or Object

→

Observed Fact or Completed Work

→

Technical Effect

→

Next Action or Supported Capability

## Rules

- Preserve product names, metrics, interfaces, methods, and technical terms.
- Distinguish confirmed facts from possibilities, assumptions, and recommendations.
- Add diagnostic dimensions only as suggestions, not as completed work.
- Do not introduce unmentioned modules, architectures, algorithms, or test results.
- Prefer specific verbs such as validate, configure, integrate, monitor, compare, and verify.

## Example

Before:

接口偶尔失败，需要看一下。

After:

当前接口存在间歇性调用失败，建议结合错误日志、返回码及调用链路开展排查，进一步定位异常环节，为接口稳定性优化提供依据。

## Quality Check

Ensure that the rewrite:

- preserves the original technical scope
- separates fact from recommendation
- remains concise and operational
- avoids unsupported root-cause claims
