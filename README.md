# 『스택을 좇아서: 제1화—모형화 이야기』 한국어 완역

이 저장소는 알렉산더 그로텐디크의 『스택을 좇아서: 제1화—모형화 이야기』를
독립적으로 완역한 한국어판을 보존한다. 영한 대역본이 아니다. 수식, 영구 식별자,
고유명, 원문 인용, 문헌 원제처럼 동일성을 보존해야 하는 내용을 제외하고 독자용
본문과 보조 자료를 한국어로 제공한다.

## 열람과 내려받기

- [v1.3.0 완전판 릴리스](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ko-kr/releases/tag/v1.3.0)
- [열람용 PDF(502쪽)](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ko-kr/releases/download/v1.3.0/01_pursuing-stacks.ko-KR.complete.pdf)
- [원전 arXiv:2111.01000v2](https://arxiv.org/abs/2111.01000)

공개 파일은 다음 순서로 놓인다.

1. `01_pursuing-stacks.ko-KR.complete.pdf` — 502쪽의 완전한 열람용 PDF.
2. `02_pursuing-stacks.ko-KR.complete.cumulative.tex` — 직접 내려받아 읽고 편집할 수 있는 완전한 누적 LaTeX.
3. `03_pursuing-stacks.ko-KR.complete.source.zip` — 열람판을 재현하는 완전한 편집 가능 소스 묶음.
4. `04_pursuing-stacks.ko-KR.revision-review.md` — 판 설명, 원전 유래 의심 항목 및 전문가 검토 안내.
5. `05_pursuing-stacks.ko-KR.translation-choices.jsonl` — 기계 판독 가능한 한국어 번역 선택 대장.
6. `06_pursuing-stacks.ko-KR.SHA256SUMS.txt` — 앞의 다섯 파일에 대한 SHA-256 검사합.

## 수록 범위

표제지와 앞부분, 필경사 서문, 저자 서문, 제1절부터 제140절까지(삽입된 16bis를
포함한 번호 매긴 본문 단위 141개), 부록 「Larry Breen에게 보낸 세 통의 편지」의
도입부와 18개 전 소절, 각주, 방주, 표제, 도식의 독자용 글자, 목차, 참고문헌과
그 밖의 뒷부분을 수록한다.

## 원전과 편집 경계

유일한 의미상 원전은 arXiv:2111.01000v2이다. 수식, 라벨, 상호 참조, 인용,
원래 쪽 표지, 가정, 주장 강도, 연대와 배열 순서를 보존한다. 한국어 용어, 통사와
성인용 수학 문체에는 실제로 참조한 한국어 수학 문헌을 사용했다. 근거, 채택 여부와
불확실성은 번역 선택 대장에 기록했다. 원전 자체의 의심스러운 곳은 번역문에서
추측으로 고치지 않고 판 설명에 분리했다. 원전 본문이 인용하는 `SGA3`에 해당하는
항목은 동봉 서지 데이터에 없으므로 출전을 추측하여 보충하지 않았다.

이 판은 Stacks Project의 공식 판이 아니며 그 승인을 받았다고 주장하지 않는다.

## 검사 범위와 한계

소스 27개, 번호 매긴 단위 141개, 부록 18개 소절 및 보호 대상 라벨·참조·인용·쪽·
날짜 매크로 열은 구조 검사를 통과했다. 모듈형 소스와 누적 소스는 각각 502쪽의
A4 PDF를 생성했다. PyPDF와 Poppler의 쪽별 본문 추출에서 두 구성 사이의 차이 쪽은
0개였고, 쪽 상자 차이도 0개였다. 최종 누적 PDF의 제1, 5, 25, 70, 130, 200,
280, 350, 420, 470, 495, 502쪽을 한 차례 한정하여 육안으로 검사했으며, 표본 쪽에서
잘림, 겹침, 뜻하지 않은 빈 쪽, 글자 누락을 나타내는 네모 또는 판면 파손이 보이지
않았다. 이는 전체 502쪽에 대한 사람의 교열을 뜻하지 않는다.

31개 글꼴은 모두 포함·부분집합화되었고 한국어 글꼴 두 개는 ToUnicode를 갖는다.
오래된 수학 글꼴 다섯 개는 ToUnicode가 없으므로 수식의 순수 텍스트 추출에는
제어 문자나 대체 문자가 남을 수 있다. 사람인 수학 전문가의 심사·교열은 거치지
않았다.

번역, 교정과 검증 자료는 OpenAI Codex — GPT-5.6 Sol(Ultra 추론 강도)이 생성했다.
사람의 편집, 심사 또는 승인을 뜻하지 않는다.

## 다른 언어판

- [중국어 간체 완역](https://github.com/KokunoYumeto/pursuing-stacks-zh-hans-cn)
- [일본어 완역](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ja)

라이선스: CC0 1.0 Universal. 보증 없음.
