# twin_sni

`twin tower disaster 대비 앱` 프로젝트 저장소

---

로컬에서 MkDocs로 매뉴얼을 미리보기/빌드하려면:

1. 가상환경 생성(권장)

Windows (PowerShell):

```
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

2. 로컬 서버 실행

```
mkdocs serve
```

3. 정적 사이트 빌드

```
mkdocs build -d site
```

참고: 문서 콘텐츠는 `docs/` 폴더에 있습니다. `mkdocs.yml`은 루트에 남겨둔 채 `docs_dir: "docs"`로 구성합니다.

참고: 테마를 변경하려면 `mkdocs.yml`의 `theme` 항목을 수정하세요.
