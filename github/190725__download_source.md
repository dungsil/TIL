# 깃허브 소스 다운로드 링크 별 특징

## 공식 API
```https://api.github.com/repos/<소유자>/<프로젝트>/zipball/<브런치 or 태그>```
 - API 리밋에 포함 됨
 - ```codeload.github.com```으로 리다이렉트 됨
 
 ## 깃허브 웹 서비스
 ```https://github.com/<소유자>/<프로젝트>/archive/<브런치 or 태그>.zip```
 - github.com에서 파일 다운로드 시 사용되는 형식
 - ```codeload.github.com```으로 리다이렉트 됨
 
 ## 실제 파일 위치
 ```https://codeload.github.com/<소유자>/<프로젝트>/zip/<태그 or 브런치>```
  - 상위에 2개가 바라 보고 있는 실제 파일의 위치
  - 리다이렉트 없음

## 참고
 - https://github.com/adobe/git-server/issues/5#issuecomment-403072428
