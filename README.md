# 동물상 진단소 🐶🐱🦊

카메라로 찍거나 업로드한 사진을 바탕으로, 재미로 동물상(강아지상·고양이상·여우상·토끼상·사슴상·곰상)을 매칭해주는 웹앱입니다.

- 실제 얼굴 인식·생체정보 분석을 하지 않습니다.
- 사진의 밝기·색감·대비 등 단순 이미지 통계 + 무작위 요소로 결과를 생성하는 **오락용 콘텐츠**입니다.
- 순수 HTML/CSS/JS로만 작성되어 별도 빌드 과정 없이 정적 호스팅으로 바로 배포됩니다.

## 로컬에서 보기

`index.html` 파일을 브라우저로 바로 열면 됩니다. (카메라 권한은 `https` 또는 `localhost` 환경에서만 동작합니다)

## Vercel 배포

1. 이 저장소를 GitHub에 푸시합니다.
2. [vercel.com/new](https://vercel.com/new) 에서 이 저장소를 Import 합니다.
3. Framework Preset은 **Other**로 두고, Build Command/Output Directory는 비워둔 채로 Deploy 합니다.
4. 배포 완료 후 발급되는 URL로 접속해 카메라 권한을 허용하면 바로 사용할 수 있습니다.

## 폴더 구조

```
.
├── index.html      # 전체 앱 (마크업 + 스타일 + 로직 포함)
├── vercel.json      # Vercel 정적 배포 설정
├── package.json     # 메타데이터 (빌드 불필요)
└── README.md
```
