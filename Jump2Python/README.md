<div align="center">

# 🇰🇷 Jump to Python · 점프 투 파이썬

### 위키독스 · 한국어 파이썬 입문의 정석

**점프 투 파이썬 학습 노트 (Jupyter Notebook)**
_Study notes from "Jump to Python", cell by cell._

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Lang](https://img.shields.io/badge/notes-한국어-306998?style=flat-square)

[⬅️ 메인으로 · Back to main README](../README.md)

</div>

---

## 📖 소개 · About

한국어 파이썬 입문서의 정석 **점프 투 파이썬**을 따라가며, **Jupyter 노트북**으로 코드를 직접 실행하고 결과를 눈으로 확인하며 개념을 익힙니다. 읽고 끝내는 게 아니라 **돌려 보며** 체득하는 트랙입니다.

_Following the classic Korean intro **"Jump to Python"**, this track learns by running code in **Jupyter notebooks** — see the output, then understand it._

- 🐍 **Python** 3.12 (`.python-version`)
- 📓 실행 가능한 Jupyter 노트북(`.ipynb`)
- 🔗 원본 교재: [wikidocs.net/book/1](https://wikidocs.net/book/1)

---

## 🗂️ 목차 · Contents

### 01 · 자료형 · Data Types

| # | 노트북 · Notebook | 내용 · Topic |
|:--:|:--|:--|
| 01 | [숫자형](01_DataType/01_숫자형.ipynb) | 정수 · 실수 · 사칙연산 |
| 02 | [문자열 자료형](01_DataType/02_문자열자료형.ipynb) | 문자열 생성 · 인덱싱 · 슬라이싱 · 포매팅 |
| 03 | [리스트 자료형](01_DataType/03_리스트자료형.ipynb) | 인덱싱 · 슬라이싱 · 관련 함수 |
| 04 | [튜플 자료형](01_DataType/04_튜플자료형.ipynb) | 튜플의 특징과 활용 |

> 이어서 딕셔너리 · 집합 · 불(bool) 자료형, 그리고 제어문 · 함수 · 클래스로 확장됩니다.
> _Dictionaries, sets, booleans, then control flow, functions, and classes come next._

---

## ⚡ 실행하기 · Run

```bash
cd Jump2Python
uv sync                 # Python 3.12 가상환경 구성
uv run jupyter lab      # 브라우저에서 노트북 열기
```

> 💡 VS Code를 쓴다면 `.ipynb` 파일을 열고 커널로 `.venv`를 선택하면 바로 실행됩니다.

---

## 📜 저작권 · Copyright

이 폴더의 **노트북**은 제가 직접 정리·작성한 것으로 루트 [MIT License](../LICENSE)를 따릅니다.
원본 교재 **점프 투 파이썬**의 저작권은 **박응용(Pahkey) 및 위키독스(WikiDocs)**에 있습니다.

_My notebooks here are MIT-licensed. The "Jump to Python" book itself is © 박응용 / WikiDocs._
