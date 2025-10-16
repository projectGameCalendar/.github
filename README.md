# .github

이 조직 리포지토리는 **Notion Integrations**와 **GitHub Actions 워크플로우**를 통해 자동으로 동기화됩니다.

## 자동 동기화 흐름

1. Notion에 조직 소개 문서를 작성 / 수정  
2. GitHub Actions 워크플로우가 주기적으로 Notion API 호출  
3. `profile/README.md` 파일을 최신 상태로 갱신  
4. 조직 메인 페이지에 최신 소개 문구가 반영됨  

## 주요 구성 요소

- **Notion Integration**  
  조직 소개 문서는 Notion에서 관리되며, GitHub 측에서는 읽기 전용 방식으로 동기화됩니다.  
- **GitHub Actions 워크플로우**  
  매일 또는 수동 실행 시 Notion의 내용을 Markdown으로 변환하여 `profile/README.md`에 반영합니다.

---

_이 방식 덕분에 조직 소개를 Notion에서만 관리하면 두 곳 모두 최신 상태로 유지됩니다._  
