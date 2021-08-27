# 마진리 마을연구 프로젝트

## theme
- tailwind-aa-theme
```bash
git submodule foreach git pull origin master
```

## data(Dropbox)
```
rclone sync dropbox:/content/items /Users/woonjjang/hugo/majin/content/items
rclone sync /Users/woonjjang/hugo/majin/content/items dropbox:/content/items
```
- dropbox & text editor(windows)
- PDF, audio file 등에 관해 테스트 하고 싶다. 

## metafield 관련
- 주소 부분 처리(도로명? / 위도경도)


## 앞으로 적용해 보면 좋은 것들

- 메인 구성 / 사이트빌딩
- 주소 / 위도, 경도 찍은 아이템을 맵위에서 브라우징 해서 보여주는 것


## Update(08.27)

- 스크립트로 생성되는 md 파일 적용
- 테마 업데이트 
- 드롭박스 자료 업데이트
- footer 링크 정리