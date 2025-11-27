# hompage
데이터 사이언티스트 포트폴리오용 정적 사이트 템플릿입니다.

로컬에서 간단히 확인하려면 다음을 실행하세요:

```bash
# 현재 디렉터리에서 간단한 서버 실행
python3 -m http.server 8000
# 그런 다음 브라우저에서 http://localhost:8000 열기
```

배포 옵션:
- GitHub Pages: 이 저장소의 `main` 브랜치에 `index.html`이 있으면 바로 사용 가능
- Netlify / Vercel: 빌드 없이 정적 파일을 그대로 업로드 가능

다음 단계 제안:
- `index.html`의 콘텐츠를 사용자의 실제 프로젝트, 노트북, GitHub 링크로 교체
- 도메인 연결, 연락처 폼(서버 또는 Netlify Forms), 분석(예: Plausible) 추가

원하시면 제가 아래 작업도 해드릴게요:
- GitHub Pages 배포 설정
- Jupyter 노트북을 `/notebooks` 폴더로 추가하고 미리보기 페이지 만들기
- Streamlit 데모 연결 또는 Dockerfile 추가

