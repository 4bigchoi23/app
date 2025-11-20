# app/www

## 👇 미리보기 👀

- https://app-4bigchoi23.netlify.app/www/
- https://app-4bigchoi23.netlify.app/www/index.html
- https://app-4bigchoi23.netlify.app/www/login.html
- https://app-4bigchoi23.netlify.app/www/admin.html
- https://app-4bigchoi23.netlify.app/www/theme.html

## 👇 레퍼런스 ✨

- https://cdn.jsdelivr.net/gh/4bigchoi23/app/www/theme.js
- https://cdn.jsdelivr.net/gh/4bigchoi23/app/www/theme.css

### ⚡ CDN

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/4bigchoi23/app/www/theme.css">
<script src="https://cdn.jsdelivr.net/gh/4bigchoi23/app/www/theme.js"></script>
```

### 🔖 Theme Select
```html
<div class="theme-select dropdown dropdown-menu-end">
	<button type="button" class="btn btn-outline-secondary dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false" id="theme-select">
		<i class="bi-circle-half" id="theme-select-icon"></i>
		<span class="visually-hidden" id="theme-select-text">Auto</span>
	</button>
	<ul class="dropdown-menu p-1 rounded" aria-labelledby="theme-select-text">
		<li class="mt-0">
			<button type="button" class="dropdown-item rounded d-flex align-items-center active" data-bs-theme-value="auto" aria-pressed="true">
				<i class="bi-circle-half" data-theme-pickup-icon></i>
				<span class="mx-2" data-theme-pickup-text>Auto</span>
				<i class="bi-check2 ms-auto d-none" data-theme-pickup-mark></i>
			</button>
		</li>
		<li class="mt-1">
			<button type="button" class="dropdown-item rounded d-flex align-items-center" data-bs-theme-value="light" aria-pressed="false">
				<i class="bi-sun-fill" data-theme-pickup-icon></i>
				<span class="mx-2" data-theme-pickup-text>Light</span>
				<i class="bi-check2 ms-auto d-none" data-theme-pickup-mark></i>
			</button>
		</li>
		<li class="mt-1">
			<button type="button" class="dropdown-item rounded d-flex align-items-center" data-bs-theme-value="dark" aria-pressed="false">
				<i class="bi-moon-stars" data-theme-pickup-icon></i>
				<span class="mx-2" data-theme-pickup-text>Dark</span>
				<i class="bi-check2 ms-auto d-none" data-theme-pickup-mark></i>
			</button>
		</li>
	</ul>
</div>

```

### 🔖 Theme Switch
```html
<div class="theme-switch">
	<button type="button" class="theme-switch-button" data-bs-theme-value="light" aria-pressed="false">
		<svg class="" fill="none" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" width="32" height="32" style="color: currentcolor;"><circle cx="12" cy="12" r="5"></circle><path d="M12 1v2"></path><path d="M12 21v2"></path><path d="M4.22 4.22l1.42 1.42"></path><path d="M18.36 18.36l1.42 1.42"></path><path d="M1 12h2"></path><path d="M21 12h2"></path><path d="M4.22 19.78l1.42-1.42"></path><path d="M18.36 5.64l1.42-1.42"></path></svg>
		<span class="visually-hidden">Light</span>
	</button>
	<button type="button" class="theme-switch-button active" data-bs-theme-value="auto" aria-pressed="true">
		<svg class="" fill="none" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" width="32" height="32" style="color: currentcolor;"><rect x="2" y="3" width="20" height="14" rx="2" ry="2"></rect><path d="M8 21h8"></path><path d="M12 17v4"></path></svg>
		<span class="visually-hidden">Auto</span>
	</button>
	<button type="button" class="theme-switch-button" data-bs-theme-value="dark" aria-pressed="false">
		<svg class="" fill="none" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" width="32" height="32" style="color: currentcolor;"><path d="M21 12.79A9 9 0 1111.21 3 7 7 0 0021 12.79z"></path></svg>
		<span class="visually-hidden">Dark</span>
	</button>
</div>
```

### 🔖 Theme Toggle
```html
<div class="theme-toggle">
	<button type="button" class="theme-toggle-button position-absolute d-none" data-bs-theme-value="light" aria-pressed="false">
		<svg class="" fill="none" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" width="32" height="32" style="color: currentcolor;"><circle cx="12" cy="12" r="5"></circle><path d="M12 1v2"></path><path d="M12 21v2"></path><path d="M4.22 4.22l1.42 1.42"></path><path d="M18.36 18.36l1.42 1.42"></path><path d="M1 12h2"></path><path d="M21 12h2"></path><path d="M4.22 19.78l1.42-1.42"></path><path d="M18.36 5.64l1.42-1.42"></path></svg>
		<span class="visually-hidden">Light</span>
	</button>
	<button type="button" class="theme-toggle-button position-relative invisible z-n1" data-bs-theme-value="auto" aria-pressed="false">
		<svg class="" fill="none" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" width="32" height="32" style="color: currentcolor;"><rect x="2" y="3" width="20" height="14" rx="2" ry="2"></rect><path d="M8 21h8"></path><path d="M12 17v4"></path></svg>
		<span class="visually-hidden">Auto</span>
	</button>
	<button type="button" class="theme-toggle-button position-absolute d-none" data-bs-theme-value="dark" aria-pressed="false">
		<svg class="" fill="none" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" width="32" height="32" style="color: currentcolor;"><path d="M21 12.79A9 9 0 1111.21 3 7 7 0 0021 12.79z"></path></svg>
		<span class="visually-hidden">Dark</span>
	</button>
</div>
```
