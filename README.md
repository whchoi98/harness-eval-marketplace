# harness-eval-marketplace

[![English](https://img.shields.io/badge/lang-English-blue.svg)](#english)
[![한국어](https://img.shields.io/badge/lang-한국어-red.svg)](#한국어)

---

# English

## Overview

Independent Claude Code plugin marketplace for harness engineering quality evaluation tools. This marketplace provides systematic evaluation plugins that assess Claude Code project maturity across correctness, safety, completeness, actionability, consistency, and testability dimensions.

## Available Plugins

| Plugin | Version | Description |
|--------|---------|-------------|
| [harness-eval](https://github.com/whchoi98/harness-eval) | 0.1.0 | 3-tier evaluation (Quick/Standard/Full) with multi-agent review, history tracking, and badge generation |

## Quick Start

### 1. Add the marketplace

```bash
claude plugin marketplace add https://github.com/whchoi98/harness-eval-marketplace
```

### 2. Install the plugin

```bash
claude plugin install harness-eval@harness-eval-marketplace
```

### 3. Use the evaluation commands

```bash
# Quick evaluation — checklist-based, < 30 seconds
/harness-eval quick

# Standard evaluation — static + dynamic analysis
/harness-eval standard

# Full evaluation — multi-agent comprehensive review
/harness-eval full

# Compare two evaluations
/harness-eval compare
```

## Uninstall

```bash
# Remove the plugin
/plugin remove harness-eval

# Remove the marketplace
/plugin marketplace remove harness-eval-marketplace
```

## Documentation

See the [harness-eval repository](https://github.com/whchoi98/harness-eval) for detailed documentation, architecture, and contributing guidelines.

## License

MIT

---

# 한국어

## 개요

하네스 엔지니어링 품질 평가 도구를 위한 독립 Claude Code 플러그인 마켓플레이스입니다. 이 마켓플레이스는 Claude Code 프로젝트의 정확성, 안전성, 완전성, 실행 가능성, 일관성, 검증 가능성을 체계적으로 평가하는 플러그인을 제공합니다.

## 제공 플러그인

| 플러그인 | 버전 | 설명 |
|---------|------|------|
| [harness-eval](https://github.com/whchoi98/harness-eval) | 0.1.0 | 3단계 평가 (Quick/Standard/Full), 멀티 에이전트 리뷰, 이력 추적, 뱃지 생성 |

## 빠른 시작

### 1. 마켓플레이스 추가

```bash
claude plugin marketplace add https://github.com/whchoi98/harness-eval-marketplace
```

### 2. 플러그인 설치

```bash
claude plugin install harness-eval@harness-eval-marketplace
```

### 3. 평가 커맨드 사용

```bash
# Quick 평가 — 체크리스트 기반, 30초 미만
/harness-eval quick

# Standard 평가 — 정적 + 동적 분석
/harness-eval standard

# Full 평가 — 멀티 에이전트 종합 리뷰
/harness-eval full

# 두 평가 비교
/harness-eval compare
```

## 제거

```bash
# 플러그인 제거
/plugin remove harness-eval

# 마켓플레이스 제거
/plugin marketplace remove harness-eval-marketplace
```

## 문서

상세 문서, 아키텍처, 기여 가이드는 [harness-eval 저장소](https://github.com/whchoi98/harness-eval)를 참조하세요.

## 라이선스

MIT
