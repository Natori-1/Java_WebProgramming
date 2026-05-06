자바스크립트 / 9주차 / 20250634
< 네비게이션 바 토글, 데이터 베이스 연동 >
<img width="922" height="778" alt="image" src="https://github.com/user-attachments/assets/e4af128b-20f0-436d-9c1c-7a60b06a838c" />
<img width="933" height="567" alt="image" src="https://github.com/user-attachments/assets/9ae83cea-ab9a-423a-9529-f5fbf99e6060" />

1. 네비게이션 바 토글
   function toggleTheme() {
const body = document.body;
const btn = document.getElementById('themeToggleBtn');
const navbar = document.querySelector('.navbar');
body.classList.toggle('light-mode');
'LIGHT';
if (body.classList.contains('light-mode')) {
btn.textContent = ' Light ';
navbar.classList.remove('navbar-dark', 'bg-dark');
navbar.classList.add('navbar-light', 'bg-light');
} else {
btn.textContent = ' DARK';
navbar.classList.remove('navbar-light', 'bg-light');
navbar.classList.add('navbar-dark', 'bg-dark');
}
}
