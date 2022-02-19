REQUIREMENTS
1. Web Browser : Opera
2. VSCode
3. VSCode Extension : 1.Tailwind CSS IntelliSense 2.Live Preview 3.PostCSS Language Support
4. Package Manager : NPM (Node.js)
5. Terminal:Powershell,Git Bash dll..



INSTALASI & KONFIGURASI TAILWINDCSS
-CDN : script src="https://cdn.tailwindcss.com"></script>

-Offline
1. npm init -y
2. npm install -D tailwindcss postcss autoprefixer
3. npx tailwindcss init (create file config tailwind : tailwind.config.js)
4. config content : tailwind.config.js
5. ./src/**/*.{html,js}
6. buat file css di .src/css/input.css
7. @tailwind base;
   @tailwind components;
   @tailwind utilities;  
8. proses build > npx tailwindcss -i ./src/css/input.css -o ./public/css/style.css --watch
9.  <link rel="stylesheet" href="/trytailwind/public/css/style.css" />
10.  SELESAI
11.  

