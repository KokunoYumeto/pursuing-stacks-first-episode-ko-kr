# 『스택을 좇아서: 제1화—모형화 이야기』 전 범위 한국어 번역판

이 저장소는 등록된 영어 권위본 arXiv:2111.01000v2를 바탕으로 알렉산더
그로텐디크의 『스택을 좇아서: 제1화—모형화 이야기』를 한국어로 직접 옮긴
전 범위 한국어 번역판을 보존한다. 영한 대역본이 아니며, 수식,
영구 식별자, 고유명, 문헌 원제처럼 정체성을 보존해야 하는 내용만 원형을
유지하며, 본문과 앞부분, 부록, 주석, 목차, 검증 자료를 한국어로 제공한다.

## 열람과 내려받기

- [Zenodo v1.2.0 영구 DOI](https://doi.org/10.5281/zenodo.22949505)
- [Zenodo 개념 DOI—항상 이 계보의 최신 판을 가리킴](https://doi.org/10.5281/zenodo.22870236)
- [GitHub v1.2.0 공개판](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ko-kr/releases/tag/v1.2.0)
- [원자료 arXiv:2111.01000v2](https://arxiv.org/abs/2111.01000)
- [CJK 수학 표기 백엔드 v1.0.1](https://doi.org/10.5281/zenodo.21939358)

공개 파일은 다음 순서로 놓인다.

1. `01_pursuing-stacks.ko-KR.complete.pdf` — 502쪽의 누적 열람용 PDF,
   3,153,034바이트, SHA-256
   `83E618E5BEA747DC471A5DF88408D18CAEA480ED4080447770D2B92DC33022A7`.
2. `02_pursuing-stacks.ko-KR.complete.cumulative.tex` — 직접 내려받아
   열람·편집할 수 있는 완전한 누적 LaTeX, 2,020,446바이트, SHA-256
   `2038A897EDDF1F39A0054D18EFC654E602F87EF167BCBD6F424D77A966AC2F1B`.
3. `03_pursuing-stacks.ko-KR.complete.source.zip` — 모듈형 TeX, 누적 TeX,
   서지, 그림, 글꼴, 빌드 안내와 스크립트를 포함한 완전 소스 ZIP,
   12,362,443바이트, SHA-256
   `F152C843D0B07300AD934CE055387B1EE9178B4E1C3DDF78F06024AB3FD9EFA6`.
4. `04_pursuing-stacks.ko-KR.revision-review.md` — 한국어 교정·검증 기록,
   29,233바이트, SHA-256
   `6E7E4910278AE25F2FB0D08C8C2CF8C1F595568EB1DB4B57F4F229312FD9B16F`.
5. `05_pursuing-stacks.ko-KR.translation-choices.jsonl` — 기계 판독 가능한
   번역 선택 대장 21건, 43,230바이트, SHA-256
   `5ED2984D6FBB1896FDD39E82BC913368706A8EB9B386BD992527563E57A29F8F`.
6. `06_pursuing-stacks.ko-KR.SHA256SUMS.txt` — 위 다섯 파일의 검사합,
   557바이트, SHA-256
   `8FDC04DE1F4DF91DF297583ACA151C958165E03F635939251B81E75B85ED6AF6`.

## 수록 범위

표제지와 앞부분, 필경사 서문, 저자 서문, 삽입된 16bis절을 포함한 제1절부터
제140절까지의 번호 매긴 본문 단위 141개, 부록 「Larry Breen에게 보낸 세 통의
편지」의 도입부와 번호가 붙은 18개 소절, 각주, 방주, 표제, 도식의 독자용 글자,
목차, 참고문헌과 그 밖의 뒷부분을 포함한다.

## 원자료와 편집 경계

유일한 의미상 권위 자료는 arXiv:2111.01000v2이다. 수식, 라벨, 상호 참조,
인용, 원래 쪽 표지, 가정, 주장 강도, 시간 순서와 배열 순서를 보존한다. 원자료
자체의 의심스러운 수식, 참조, 연대, 철자와 서지는 추측으로 고치지 않고 한국어
교정·검증 기록에 분리했다. 원자료가 인용하는 `SGA3`의 서지 항목은 동봉 데이터에
없으므로 추측하여 보충하지 않았다.

이 판은 Stacks Project의 공식 판이 아니며 그 승인을 받았다고 주장하지 않는다.

## v1.2.0의 교정과 검증

영문 권위 자료와 한국어판의 앞부분 및 `ps1.tex`부터 `ps7.tex`까지를 다시
대조하여 의미 누락, 조건의 약화, 지시 대상의 뒤바뀜, 미번역 독자용 문구와 용어
불일치를 교정했다. 번역 선택 21건을 근거와 함께 기록했으며, 원자료에서 물려받은
의심 항목 201건은 번역 결함과 분리했다.

최종 모듈형·누적 PDF는 각각 502쪽이다. 두 구성의 추출 본문 차이, 페이지 상자
차이와 90dpi 페이지별 렌더링 502쌍의 차이는 모두 0건이었다. 모든 글꼴이
포함·부분집합화되었고 한국어 글꼴은 모두 ToUnicode를 갖는다. 32개 접촉 시트로
전 쪽을 한 번씩 확인하여 잘림, 겹침, 우발적 빈쪽과 누락 글리프 상자가 없음을
확인했다. 오래된 수학 글꼴 5개의 ToUnicode 부재와 그에 따른 동일한 수학 기호
추출 경고는 두 PDF에 남아 있다.

Zenodo 공개 직후 여섯 파일을 익명으로 다시 내려받아 바이트 수와 SHA-256이
일치함을 확인했다. 기계 검사는 인간의 전문 판단을 뜻하지 않으며, 번역어와
역사적 함의에 오류가 남을 수 있다.

이 한국어판의 인공지능 번역·교정·편집과 검증 자료 작성은
OpenAI Codex — GPT-5.6 Sol(추론 강도: Ultra)가 수행했다.
인간 전문가의 심사·교열·승인은 거치지 않았다.

## 다른 언어판

- [중국어 간체판 Zenodo v1.2.0](https://doi.org/10.5281/zenodo.22931280) · [중국어 간체판 GitHub 저장소](https://github.com/KokunoYumeto/pursuing-stacks-zh-hans-cn)
- [일본어판 Zenodo v1.2.0](https://doi.org/10.5281/zenodo.22938804) · [일본어판 GitHub 저장소](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ja)

라이선스: CC0 1.0 Universal. 보증 없음.
