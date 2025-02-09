# 🎨 Movie Web 
☕️ **영화 웹사이트**  
🔹 **개인 프로젝트**  
📅 **개발 기간:** 2024.11.13 ~ 2024.11.20 

<br/>

## 📝 Project Introduce
Next.js를 공부하기 위해 제작한 웹사이트입니다.

<br/>

## 🚀 Getting Started
### 📦 Installation  
```bash
$ git clone https://github.com/seung-mii/movie-web.git
$ cd movie-web
```


### 🖥 Execution
``` bash
npm install
npm run dev
```

<br/>

## 🔧 Tech Stack
### ⚙️ Environment  
<p align="left">
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
</p>

### 🛠️ Development  
<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
</p>


<br/>


## ✨ Key Features
### 💡 영화별 상세 정보
- 영화마다 동적 라우팅을 하여 해당 영화에 대한 정보만 볼 수 있습니다.
- 영화 예고편 및 비디오를 렌더링하여 사용자에게 제공합니다.


<br/>


## 🏛️ Architecture
### 📂 디렉토리 구조
```bash
├── README.md
├── package-lock.json
├── package.json
├── tsconfig.json
├── app/
│   ├── constants.ts
│   ├── layout.tsx
│   ├── not-found.tsx
│   ├── (home)/
│   │   ├── loading.tsx
│   │   └── page.tsx
│   ├── (movie)/movies/[id]
│   │   ├── loading.tsx
│   │   └── page.tsx
│   └── about-us/
│       ├── layout.tsx
│       └── page.tsx
├── components/
│   ├── movie-info.tsx
│   ├── movie-videos.tsx
│   ├── movie.tsx
│   └── navigation.tsx
└── styles/
    ├── global.css
    ├── home.module.css
    ├── movie.module.css
    ├── movie-info.module.css
    ├── movie-videos.module.css
    └── navigation.module.css

```

<br/>

<p align="right">
  <a href="https://github.com/seung-mii/movie-web/tree/main">
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fseung-mii%2Fmovie-web&count_bg=%23748DA6&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false">
  </a>
</p>
