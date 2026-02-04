# 북미 인플루언서 시딩 프로모션 랜딩페이지

오초(OCHO)의 북미 인플루언서 시딩 프로모션 랜딩 페이지

## 현재 상태 (2026.02.03)

### 완료된 작업
- [x] 메인 페이지 (index.html) - 2026 트렌드 반영 리디자인 완료
- [x] 상세 페이지 (details.html) - 2026 트렌드 반영 리디자인 완료
- [x] 모바일 반응형 최적화 완료
- [ ] 신청 페이지 (apply.html) - Tally 폼 임베드 (기존 유지)

### 디자인 변경 사항 (다크모드 → 라이트모드)
- 배경: 검정 → `#fafafa` (밝은 그레이)
- glassmorphism 제거 → 깔끔한 bento-card 스타일
- 그라데이션: CTA와 가격에만 절제 사용
- Bento Grid 레이아웃 적용
- 애니메이션: scroll reveal만 사용 (AOS 제거)

---

## 프로젝트 정보

| 항목 | 내용 |
|------|------|
| 회사명 | 오초 (OCHO) |
| 이메일 | contact@ocho.team |
| 협업 브랜드 | 100개+ |
| 인플루언서 풀 | 200만+ |
| 누적 콘텐츠 | 2만+ |
| 가격 | 9,900원/건 (프로모션) |

---

## 로컬 실행

```bash
cd Temp/100project
python3 -m http.server 8000
```

- 메인: http://localhost:8000/index.html
- 상세: http://localhost:8000/details.html
- 신청: http://localhost:8000/apply.html

---

## 페이지 구조

### 메인 페이지 (index.html)

1. **Hero** - "북미 인플루언서 시딩, 9,900원으로 시작하세요"
2. **Benefits (Bento Grid)** - 9,900원, 100% 보장, 2차 활용권, 브랜드 선정권
3. **Why Different** - 직접 DM 아웃리치, 브랜드 선정권, 데이터 기반
4. **Stats** - 100+ 브랜드, 200만+ 인플루언서, 2만+ 콘텐츠
5. **Process** - APPLY → SELECT → REPORT
6. **Check Points** - 배송비, 선정권, 8주 소요
7. **Final CTA**
8. **Floating CTA** (스크롤 시 표시)

### 상세 페이지 (details.html)

1. 프로모션 소개 (목적, 컨셉, 참여 대상)
2. 서비스 개요 (6개 카드)
3. 가격 비교 테이블 (일반 에이전시 vs 오초)
4. 주요 특징 및 운영 방식
5. 참여 프로세스 (8단계)
6. FAQ (6개)
7. Final CTA

---

## 기술 스택

| 구분 | 기술 |
|------|------|
| 마크업 | HTML5 |
| 스타일링 | Tailwind CSS (CDN) |
| 폰트 | Pretendard, Montserrat |
| 애니메이션 | Vanilla JS (IntersectionObserver) |

---

## 남은 작업

### 우선순위 높음
- [ ] 데스크탑에서 디자인 이상한 부분 확인 및 수정
- [ ] 실제 이미지/로고 추가
- [ ] 회사소개서, 계약서 PDF 링크 연결

### 우선순위 중간
- [ ] apply.html 스타일 통일 (현재 다크모드)
- [ ] SEO 메타태그 추가
- [ ] OG 이미지 추가

### 우선순위 낮음
- [ ] Vercel 배포
- [ ] 커스텀 도메인 연결
- [ ] GA/Pixel 추가

---

## 레퍼런스

- 메인 구조: https://project100.egongegong.com/
- 가격 테이블: https://www.roundgo.io/new-year-promotion

---

## 프로모션 조건 (상세 페이지 하단 작은 글씨)

> 9,900원 프로모션 조건: 3개월간 총 1,000건 이상 계약 시 적용되며, 첫 달 최소 300건 이상 계약이 필요합니다. 프로모션 미적용 시 건당 40,000원입니다.
