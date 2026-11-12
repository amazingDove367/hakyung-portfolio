# hakyung-portfolio

손하경의 마케팅 포트폴리오 제출용 웹페이지. MORH(모르) 화장품 브랜드(미백크림, 20~30대 여성 타겟, 가상 브랜드) 프로젝트를 콘텐츠·퍼포먼스·그로스 3축으로 정리한다. 기간은 2026.09.14~11.11이고, 광고는 11/14~16까지 돌릴 예정.

- 페이지: `portfolio/index.html` (A4 가로 장표형 템플릿), 캡처: `portfolio/img/`
- 배포: GitHub Pages → https://amazingdove367.github.io/hakyung-portfolio/portfolio/
- 제출물: 위 URL + 크롬 인쇄로 만든 PDF (가로 · 여백 없음 · 배경 그래픽 켬)

## 작업 순서
1. `02_자료모으기_체크리스트.md`를 채우고 캡처를 `portfolio/img/`에 모은다 (파일 이름은 영어 소문자).
2. 채운 체크리스트로 `portfolio/index.html`을 채운다 → PR.
3. 숫자를 원본 화면과 대조하고, `[ ]`가 하나도 남지 않았는지 확인한다.
4. PDF로 저장하고 제출한다.

## index.html 채우기 규칙
1. 디자인과 칸 배치는 바꾸지 않는다. `[ ]` 자리와 빈 칸·빈 표에 글만 넣는다.
2. 체크리스트 문장을 그대로 옮긴다. 다듬거나 늘리거나 새 문장을 만들지 않는다.
3. 체크리스트에 없는 숫자·날짜·성과를 만들지 않는다. "모름"·"하지 않음"은 그대로 쓴다.
4. 체크리스트에 없는 장은 section을 통째로 지우고, 남은 장 번호(`.no`와 `.ft` 오른쪽)를 순서대로 다시 매긴다. 00장 축 표의 '장표' 칸도 새 번호로 바꾼다.
5. 배지는 도구 `<span class="b">이름</span>`, 역량 `<span class="b skill">이름</span>`. 쓰지 않는 배지는 지운다.
6. 숫자 출처는 `<span class="tag real">실측</span>` / `<span class="tag assume">가정</span>` / `<span class="tag none">미측정</span>`.
7. 증거 칸은 `.shot` 안에 `<img src="img/파일이름" alt="">`.
8. 10장 '도구 · 역량' 칸에는 모든 장의 배지를 중복 없이 모은다.
9. noindex 메타는 지우지 않는다. `portfolio` 폴더 밖 파일과 GA4·GTM·픽셀 코드는 건드리지 않는다.

PR 설명에는 비어 있는 칸과 남은 `[ ]` 목록만 적는다.
