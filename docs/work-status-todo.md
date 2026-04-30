# 작업 현황 & TODO (Work Status)

## 문서 작업 현황

| 문서 | 상태   |
|------|------|
| **인프라 설계서** | ✅ 완료 |
| **도메인 리스트** | ✅ 완료 |
| ERD | ✅ 완료 |
| README.md | ✅ 완료 |

---

## 앞으로 논의/결정해야 할 사항

- [x] 배포 환경 결정 (EC2 단독 vs ELB 등) => EC2 2개로 관리(APP, DB)
- [x] CI/CD 파이프라인 구성 여부 => 인프라, 배포 설계서 작성 완료
- [x] Redis 캐싱 구현 범위 결정 => 구현(블랙리스트, RT, Rate Limit)
- [x] 페이지네이션 전략 (Offset 기반 vs Cursor 기반) => Offset 기반
- [x] Soft Delete 전략 => `is_deleted` 플래그 사용