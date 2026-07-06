# claude_md

Claude Code 글로벌 규칙(`~/.claude/CLAUDE.md`)을 백업하고 PC 간 공유하기 위한 저장소임.

## 구성

CLAUDE.md는 두 부분으로 이루어짐:

- **행동 원칙** — [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills/blob/main/CLAUDE.md)의 CLAUDE.md를 한국어(음슴체)로 옮긴 것. 코딩 전에 생각하기, 단순함 우선, 외과적 수정, 목표 주도 실행의 4원칙임. **이 원문이 기준이며, 수정 시 항상 원문과 대조함**
- **개인 컨벤션** — 문체(음슴체, 이모티콘 금지, 한국어 주석), 주석/docstring 규칙, Git 규칙(모든 git 명령 사전 확인, 커밋은 직접)

## 새 PC 설치

원하는 위치에 clone한 뒤 Claude Code 글로벌 경로(`~/.claude/CLAUDE.md`)로 복사함:

```bash
git clone https://github.com/csw9261/claude_md.git
cp claude_md/CLAUDE.md ~/.claude/CLAUDE.md
```

## 수정 시

`~/.claude/CLAUDE.md`를 수정한 뒤 이 저장소에 복사해서 커밋함. 심링크가 아니라 수동 동기화가 필요함:

```bash
cp ~/.claude/CLAUDE.md <저장소 경로>/CLAUDE.md
```
