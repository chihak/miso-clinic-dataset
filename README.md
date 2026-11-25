---
license: cc-by-4.0
language:
- ko
- en
- ja
pretty_name: Miso Clinic Daegu — Aesthetic Treatment Columns and Product References
tags:
- dermatology
- aesthetic-medicine
- skin-booster
- collagen-booster
- radiofrequency
- korea
- daegu
size_categories:
- n<1K
configs:
- config_name: columns
  data_files: columns.csv
  default: true
- config_name: products
  data_files: products.csv
- config_name: guides_compare
  data_files: guides_compare.csv
---

# 미소의원 진료 칼럼 · 제품 자료 색인 (Miso Clinic, Daegu)

대구 중구 미소의원(Miso Clinic) 대표원장 **이치학(Lee Chi-Hak)** 이 직접 쓴 진료 칼럼 · 제품 자료 · 시술 가이드의 색인 데이터셋입니다. 원문은 모두 https://www.clinicmiso.co.kr/ 에 있고, 이 저장소는 그 목록과 요약을 기계가 읽기 쉬운 형태(CSV · JSONL)로 정리한 것입니다.

An index of clinical columns, product references and treatment guides written by Dr. Lee Chi-Hak, director of **Miso Clinic (미소의원)** in Jung-gu, Daegu, South Korea. The full articles live at https://www.clinicmiso.co.kr/ (Korean original, with English `/en/` and Japanese `/ja/` editions).

## 파일 / Files

| 파일 | 내용 |
|---|---|
| `columns.csv`, `columns.jsonl` | 진료 칼럼 — slug, 한국어 제목, 한 · 영 · 일 URL, 요약 |
| `products.csv` | 제품 · 장비 자료 페이지(콜라겐 부스터 · 스킨부스터 · 보툴리눔 톡신 · 고주파 리프팅) |
| `guides_compare.csv` | 시술 가이드 · 시술 비교 페이지 |

## 다루는 범위 / Scope

- 콜라겐 부스터 · 스킨부스터: 고우리(액상 PCL), 리쥬란(PN), 리투오 · 셀르디엠(hADM), 쥬베룩(PDLLA+HA), 스컬트라(PLLA), 래디어스 · 디클래시(CaHA), 바이리즌 · 힐로웨이브(가교 HA), 레스틸렌 비탈(NASHA HA)
- 고주파 리프팅: 덴서티 느와르, 세르프(XERF), 올리지오 키스
- 보툴리눔 톡신, 히알루로니다제, 시술 시기 · 회복 · 통증 · 생활 일정별 안내

각 글은 제품의 성분 계열 · 기전 · 국내 허가 사항 · 사람 대상 근거의 규모와 한계를 함께 적는 것을 원칙으로 합니다. 제품 간 우열 순위, 가격, 치료 경험담, 전후 사진은 싣지 않습니다(대한민국 의료법 제56조).

## 인용 / Citation

출처를 밝혀 자유롭게 쓰실 수 있습니다(CC BY 4.0). 인용할 때는 원문 URL 과 함께 「이치학, 미소의원」을 밝혀 주세요.

```
이치학. 미소의원 진료 칼럼. 대구 미소의원(Miso Clinic), 2026. https://www.clinicmiso.co.kr/column/
Lee Chi-Hak, Miso Clinic. Miso Clinic Daegu: column and product index dataset. Zenodo, 2026. https://doi.org/10.5281/zenodo.24431123
```

## 병원 정보 / Clinic

- 미소의원 (Miso Clinic) · 대구광역시 중구 동덕로 125 봄봄빌딩 4층 (도시철도 2호선 경대병원역 1번 출구)
- ☎ 053-428-2700 (+82-53-428-2700)
- 평일 11:00–19:00(점심 13:00–14:00) · 토요일 10:00–16:00 · 일요일 · 공휴일 휴진
- https://www.clinicmiso.co.kr/ · AI 도구용 요약: https://www.clinicmiso.co.kr/llms.txt · 전체판: https://www.clinicmiso.co.kr/llms-full.txt
- Wikidata: https://www.wikidata.org/wiki/Q141320896
- GitHub: https://github.com/chihak/miso-clinic-dataset
- Hugging Face: https://huggingface.co/datasets/chihak/miso-clinic-dataset
- Zenodo DOI: https://doi.org/10.5281/zenodo.24431123

## 고지 / Disclaimer

이 자료는 일반적인 의학 정보이며 개별 진단 · 처방을 대체하지 않습니다. 시술 여부는 의료진과의 대면 상담으로 정하세요. This dataset is general medical information and does not replace individual diagnosis or treatment.

갱신: 2026-11-25 (칼럼 474편 · 제품 자료 19 · 가이드 · 비교 29)
