# ⌨️ 키보드 추천 서비스 `tadak`
다양한 키보드 정보와 리뷰를 공유할 수 있는 커뮤니티형 웹 플랫폼 

## 배포 사이트 
[Link]tadak-163.vercel.app

## 📸 데모
|CRUD|무한스크롤|
|---|---|
|<img src='https://github.com/user-attachments/assets/6fa95589-6b36-4f58-8c9a-545c0a3faa51'/>|<img src='https://github.com/user-attachments/assets/2dfe8ce8-7bab-4a6a-89de-661c8b58f21f'/>|

|인증 시스템|필터링|
|---|---|
|<img src='https://github.com/user-attachments/assets/00b176d3-61d3-4d6b-b434-e50a47fa802e'/>|<img src='https://github.com/user-attachments/assets/541edea9-5dab-405e-982e-4ae1e5b9b60c'/>|


## 기술 스택
<img src='https://img.shields.io/badge/Node.js-22-white?labelColor=5FA04E' /> <img src='https://img.shields.io/badge/Next.js-15.4-white?labelColor=black' /> <img src='https://img.shields.io/badge/TypeScript-5-white?labelColor=3178C6' /> <img src='https://img.shields.io/badge/TailwindCSS-4-white?labelColor=06B6D4' /> 
<img src='https://img.shields.io/badge/clsx-2-white?labelColor=gray'/> <img src='https://img.shields.io/badge/tailwindMerge-3.3-white?labelColor=gray' /> <img src='https://img.shields.io/badge/HeadlessUI-2.2-white?labelColor=66E3FF'/> <img src='https://img.shields.io/badge/React%20Hook%20Form-7.6-white?labelColor=EC5990' /> <img src='https://img.shields.io/badge/Zustand-5-white?labelColor=9C4121' />
<img src='https://img.shields.io/badge/axios-1.10-white?labelColor=5A29E4' /> <img src='https://img.shields.io/badge/Swiper-11-white?labelColor=6332F6' /> <img src='https://img.shields.io/badge/Framer%20Motion-12-white?labelColor=0055FF'/>

<!-- [Nest](https://github.com/nestjs/nest) framework TypeScript starter repository. -->
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).




## Access to Swagger Document

- Swagger Document [Link](https://winereview-api.vercel.app/docs/#/) :
  해당 서버가 실행시 접속가능
- teamId는 16-3 사용

## Reference

- Figma 기획 변경본(tadak) [Link](https://www.figma.com/design/Pxl73BvQHgy14e9AsuPqbv/tadak--WHYNE-copy-?node-id=140-7165&t=I25vjOIk2ZbbJx5p-0)
- Figma 원본(WHYNE) [Link](https://www.figma.com/design/KKEgdM0NWLI4kSqEpdR3RB/WINE-BBB-?node-id=6-1760&p=f&t=47Iv300lVqLIDEGI-0)
- Discord [Link](https://discord.com/channels/1344520737691668561/1385486572992073788)
- Notion [Link](https://www.notion.so/2318ca8d39728171822aeb14df352b13?pvs=13)

## 폴더 구조

```
📦public
 ┣ 📂fonts
 ┃ ┣ 📜Pretendard-Bold.woff
 ┃ ┣ 📜Pretendard-Medium.woff
 ┃ ┣ 📜Pretendard-Regular.woff
 ┃ ┗ 📜Pretendard-SemiBold.woff
 ┗ 📂images
 ┃ ┣ 📜logoImg.svg
 ┃
 📦src
 ┣ 📂app
 ┃ ┣ 📂(auth)
 ┃ ┃ ┣ 📂signin
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┗ 📜layout.tsx
 ┃ ┣ 📂(global)
 ┃ ┃ ┗ 📜page.tsx
 ┃ ┣ 📜favicon.ico
 ┃ ┣ 📜globals.css
 ┃ ┗ 📜layout.tsx
 ┣ 📂components
 ┃ ┣ 📂feature
 ┃ ┃ ┣ 📜SignInForm.tsx
 ┃ ┃ ┗ 📜SignUpForm.tsx
 ┃ ┣ 📂layout
 ┃ ┃ ┗ 📜Header.tsx
 ┃ ┗ 📂ui
 ┃ ┃ ┣ 📜Button.tsx
 ┃ ┃ ┗ 📜Modal.tsx
 ┣ 📂constants
 ┃ ┗ 📜constants.ts
 ┣ 📂hooks
 ┃ ┗ 📜useWindowDimension.ts
 ┣ 📂lib
 ┃ ┗ 📜axios.ts
 ┣ 📂types
 ┗ 📂utils
 ┃ ┣ 📜formatDate.ts
 ┃ ┗ 📜formatPrice.ts
 ┗ package.json
 ┗ package-lock.json
 ┗ .gitignore
 ┗ .dockerignore
 ┗ Dockerfile
 ┗ .prettierrc
 ┗ .prettierignore
 ┗ eslint.config.mjs
 ┗ next.config.ts
 ┗ tsconfig.json
 ┗ README.md
```

## 시작하기

개발 서버 실행:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.





