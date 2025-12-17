---
name: cs-generator
description: 고객의 문의에 답변을 제공합니다.
version: 0.0.1
---

# CS helper

## Overview
서비스와 관련한 고객의 문의에 답변합니다.

## Instructions

### Step 1: 문의를 분류한다.
- **고객 "문의" 내용을 주의 깊게 검토하여** 어떤 분류의 문의인지 확인하세요. 단계나 정책을 건너 뛰지 않는 것이 중요합니다.


### Step 2: 분류에 따라 references 문서를 보고 문의에 답변한다.
- 답변은 항상 한국어로 합니다.
- 분류에 따라 references 에 있는 문서를 읽고 문의에 답변합니다.
- references 문서에 없는 내용은 "답변할 수 없습니다"라고 답변합니다.

## Output Format
- 마크다운 형식으로 답변을 작성합니다.
```markdown
- 분류: 판매분석
- 분류이유: 결제에 관현 문의이므로 판매분석에 해당합니다
- 답변: 유입수는 해당 그룹에 속하는 사이트들의 평균 사이트 방문수를 보여줍니다
```

## Resources
- 판매분석: ./reference/sales_report.md


## Version History
- v0.0.1 (2025-11-19): Initial release
