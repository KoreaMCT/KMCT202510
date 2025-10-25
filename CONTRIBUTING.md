# 기여 가이드

KMCT202510 저장소에 기여해 주셔서 감사합니다! 

## 자료 공유 방법

### 방법 1: Pull Request를 통한 기여

1. 이 저장소를 Fork 합니다
2. Fork한 저장소를 Clone 합니다
   ```bash
   git clone https://github.com/YOUR_USERNAME/KMCT202510.git
   ```
3. 새로운 브랜치를 생성합니다
   ```bash
   git checkout -b add-my-material
   ```
4. 자료를 추가합니다
   - 발표 자료: `presentations/` 폴더에 추가
   - 코드 샘플: `code-samples/` 폴더에 추가
   - 참고 자료: `resources/` 폴더의 README 업데이트
5. 변경사항을 커밋합니다
   ```bash
   git add .
   git commit -m "Add: [자료 설명]"
   ```
6. Fork한 저장소에 푸시합니다
   ```bash
   git push origin add-my-material
   ```
7. Pull Request를 생성합니다

### 방법 2: 직접 커밋 (권한이 있는 경우)

저장소에 대한 쓰기 권한이 있다면 직접 커밋하실 수 있습니다.

```bash
git clone https://github.com/KoreaMCT/KMCT202510.git
cd KMCT202510
# 자료 추가
git add .
git commit -m "Add: [자료 설명]"
git push
```

## 파일 및 폴더 규칙

### 발표 자료 (presentations/)

- 파일명 형식: `YYYYMMDD_발표자명_주제.확장자`
- 예: `20251025_홍길동_Azure소개.pdf`
- 지원 형식: PDF, PPTX, PPT 등

### 코드 샘플 (code-samples/)

- 각 프로젝트는 별도 폴더에 저장
- 폴더명: 프로젝트명 또는 간단한 설명
- 각 프로젝트 폴더에 README.md 포함
  - 프로젝트 설명
  - 실행 방법
  - 의존성 정보
  - 사용 기술

### 참고 자료 (resources/)

- README.md 파일을 업데이트하여 링크 추가
- 카테고리별로 정리

## 커밋 메시지 규칙

- `Add: 새로운 자료 추가`
- `Update: 기존 자료 업데이트`
- `Fix: 오류 수정`
- `Docs: 문서 수정`

예시:
```
Add: Azure Functions 발표 자료 추가
Update: Python 코드 샘플 개선
Fix: README 링크 오류 수정
```

## 코드 품질

- 코드는 실행 가능한 상태로 제공
- 적절한 주석 포함
- README에 명확한 실행 가이드 작성
- 민감한 정보 (API 키, 비밀번호 등) 포함 금지

## 질문이나 제안

- Issue를 통해 질문하거나 제안 사항을 남겨주세요
- Korea MCT 커뮤니티 채널에서 논의할 수 있습니다

## 라이선스

기여하신 자료는 커뮤니티 학습 목적으로 공유됩니다. 
자료에 특정 라이선스가 필요한 경우 명시해 주세요.

---

다시 한번 기여에 감사드립니다! 🙏
