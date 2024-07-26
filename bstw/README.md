# app/bstw

- Bootstrap 5.3.3 + TailwindCSS 3.4.7  
- npm install -D bootstrap tailwindcss  
- bootstrap: reboot / components  
- tailwindcss: utilities  
- 각 프로젝트 수준의 스타일시트(폰트/색상 등)는 부트스트랩의 CSS variables 활용  

## 👇 미리보기 👀

- https://app-4bigchoi23.netlify.app/bstw/  

## 👇 레퍼런스 ✨

- https://getbootstrap.com/docs/5.3/getting-started/download/#npm  
- https://getbootstrap.com/docs/5.3/customize/sass/  
- https://tailwindcss.com/docs/installation  

## 👇 프로젝트 구조

```
app/bstw
│  .editorconfig
│  .gitignore
│  index.html
│  README.md
│  
├─dist
│  ├─css
│  │      .gitkeep
│  │      bootstrap.css
│  │      bootstrap.min.css
│  │      tailwind.css
│  │      tailwind.min.css
│  │      
│  └─js
│          .gitkeep
│          
└─src
    ├─css
    │      .gitkeep
    │      tailwind.css
    │      
    ├─js
    │      .gitkeep
    │      
    └─scss
            .gitkeep
            custom.scss
```