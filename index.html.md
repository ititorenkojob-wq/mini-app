  
\<\!DOCTYPE html\>\<html lang="en"\>\<head\>\<meta charSet="utf-8"/\>\<meta name="viewport" content="width=device-width, initial-scale=1"/\>\<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Onest:wght@400;500;600;700;800;900\&amp;family=Unbounded:wght@600;700;800\&amp;family=Fredoka:wght@500;600;700\&amp;display=swap" data-precedence="default"/\>\<link rel="stylesheet" href="/assets/styles-Bf4JwD2T.css" data-precedence="default"/\>\<title\>EDpower — навигатор клуба\</title\>\<meta name="author" content="EDpower"/\>\<meta property="og:title" content="EDpower — помощник мамы"/\>\<meta property="og:description" content="Telegram Mini App EDpower: курсы, клуб, база знаний и поддержка куратора."/\>\<meta property="og:type" content="website"/\>\<meta name="twitter:card" content="summary"/\>\<meta name="twitter:site" content="@Lovable"/\>\<meta name="twitter:title" content="EDpower — помощник мамы"/\>\<meta name="twitter:description" content="Telegram Mini App EDpower: курсы, клуб, база знаний и поддержка куратора."/\>\<meta property="og:image" content="https://pub-bb2e103a32db4e198524a2e9ed8f35b4.r2.dev/444508b6-6536-4fcc-a653-15803b6799a8/id-preview-cae09b3f--ffe913d6-19a3-4cb9-9bd5-aa94bebf8576.lovable.app-1780490207131.png"/\>\<meta name="twitter:image" content="https://pub-bb2e103a32db4e198524a2e9ed8f35b4.r2.dev/444508b6-6536-4fcc-a653-15803b6799a8/id-preview-cae09b3f--ffe913d6-19a3-4cb9-9bd5-aa94bebf8576.lovable.app-1780490207131.png"/\>\<meta name="description" content="Быстрый переход в нужный раздел клуба EDpower."/\>\<link rel="modulepreload" href="/assets/index-CIwy3Q32.js"/\>\<link rel="modulepreload" href="/assets/index-DsFFsKIf.js"/\>\<link rel="preconnect" href="https://fonts.googleapis.com"/\>\<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous"/\>  
\<style\>  
	@font-face {  
		font-family: 'CameraPlainVariable';  
		src: url('https://cdn.gpteng.co/mcp-widgets/v1/fonts/CameraPlainVariable.woff2') format('woff2');  
		font-weight: 100 900;  
		font-style: normal;  
		font-display: swap;  
	}

	\#lovable-badge {  
		\--badge-bg: \#1b1b1b;  
		\--badge-text: \#c5c1b9;  
		\--badge-text-hover: \#dcdad5;  
		\--badge-radius: 6px;  
		\--badge-padding: 8px;  
		\--badge-gap: 6px;  
		\--badge-shadow:   
			0 0 0 1px rgba(0, 0, 0, 0.88),  
			0 1px 0 0 rgba(0, 0, 0, 0.04),  
			0 2px 2px \-1px rgba(0, 0, 0, 0.08),  
			0 4px 4px \-2px rgba(0, 0, 0, 0.08),  
			0 8px 8px \-4px rgba(0, 0, 0, 0.08),  
			0 16px 16px \-8px rgba(0, 0, 0, 0.08);  
		\--badge-transition-duration: 0.2s;  
		\--badge-transition-easing: cubic-bezier(0.16, 1, 0.32, 1);  
		\--focus-color: \#575ECF;  
		\--focus-offset: 2px;  
		\--focus-width: 2px;  
		  
		position: fixed;  
		bottom: 12px;  
		right: 12px;  
		height: 24px;  
		display: flex;  
		align-items: center;  
		z-index: 1000000;  
		background-color: var(--badge-bg) \!important;  
		color: var(--badge-text) \!important;  
		border-radius: var(--badge-radius);  
		box-shadow: var(--badge-shadow) \!important;  
		font-size: 12px;  
		font-family: CameraPlainVariable, "CameraPlainVariable Fallback", \-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;  
		font-weight: 400 \!important;  
		text-transform: none \!important;  
		font-feature-settings: normal \!important;  
		transform: translateZ(0);  
		will-change: transform, opacity;  
	}

	\#lovable-badge-cta {  
		display: flex;  
		align-items: center;  
		gap: var(--badge-gap);  
		padding: 0 var(--badge-padding);  
		height: 100%;  
		color: inherit;  
		text-decoration: none;  
		white-space: nowrap;  
		border-radius: var(--badge-radius) 0 0 var(--badge-radius);  
		transition:   
			background-color var(--badge-transition-duration) ease,  
			color var(--badge-transition-duration) ease,  
			transform 0.1s ease;  
	}

	\#lovable-badge-cta:hover {  
		background: rgba(255, 255, 255, 0.04);  
		color: var(--badge-text-hover);  
	}

	\#lovable-badge-cta:active {  
		transform: scale(0.98);  
	}

	\#lovable-badge-cta:focus {  
		outline: none;  
	}

	\#lovable-badge-cta:focus-visible {  
		outline: var(--focus-width) solid var(--focus-color);  
		outline-offset: var(--focus-offset);  
		z-index: 1;  
	}

	\#lovable-badge-text {  
		line-height: 1;  
	}

	\#lovable-badge-divider {  
		width: 1px;  
		height: 24px;  
		background-color: rgba(255, 255, 255, 0.04);  
		flex-shrink: 0;  
	}

	\#lovable-badge-close {  
		width: 24px;  
		height: 24px;  
		min-width: 24px;  
		min-height: 24px;  
		cursor: pointer;  
		background: none;  
		border: none;  
		padding: 0;  
		display: flex;  
		align-items: center;  
		justify-content: center;  
		border-radius: 0 var(--badge-radius) var(--badge-radius) 0;  
		flex-shrink: 0;  
		transition:   
			background-color var(--badge-transition-duration) ease,  
			transform 0.1s ease;  
	}

	\#lovable-badge-close:hover {  
		background: rgba(255, 255, 255, 0.04);  
	}

	\#lovable-badge-close:active {  
		transform: scale(0.92);  
	}

	\#lovable-badge-close:focus {  
		outline: none;  
	}

	\#lovable-badge-close:focus-visible {  
		outline: var(--focus-width) solid var(--focus-color);  
		outline-offset: calc(var(--focus-offset) \* \-1);  
		z-index: 1;  
	}

	\#lovable-badge-close svg path {  
		fill: var(--badge-text);  
		transition: fill var(--badge-transition-duration) ease;  
	}

	\#lovable-badge-close:hover svg path {  
		fill: var(--badge-text-hover);  
	}

	@media (prefers-reduced-motion: reduce) {  
		\#lovable-badge-cta,  
		\#lovable-badge-close,  
		\#lovable-badge-close svg path {  
			transition: none;  
		}  
		  
		\#lovable-badge-cta:active,  
		\#lovable-badge-close:active {  
			transform: none;  
		}  
	}

	@media (prefers-contrast: high) {  
		\#lovable-badge {  
			\--badge-bg: \#000;  
			\--badge-text: \#fff;  
			\--badge-text-hover: \#fff;  
			border: 2px solid currentColor;  
		}  
		  
		\#lovable-badge-cta:focus-visible,  
		\#lovable-badge-close:focus-visible {  
			outline-width: 3px;  
		}  
	}  
\</style\>  
\<script defer src="/\~flock.js" data-proxy-url="/\~api/analytics"\>\</script\>\<script defer src="/\_\_l5e/events.js" data-artifact-kind="dwl\_content\_hash" data-artifact-id="89c219aecf39f67b852feffdae7a6044bdf136ae507b314c7bbaeb5356c2fb92" data-commit-sha="9c2bf14cf9ab3341d715ad150ac4ec5ebc4929a8" data-context-token="v1.eyJwcm9qZWN0X2lkIjoiZmZlOTEzZDYtMTlhMy00Y2I5LTliZDUtYWE5NGJlYmY4NTc2IiwiYXJ0aWZhY3Rfa2luZCI6ImR3bF9jb250ZW50X2hhc2giLCJhcnRpZmFjdF9pZCI6Ijg5YzIxOWFlY2YzOWY2N2I4NTJmZWZmZGFlN2E2MDQ0YmRmMTM2YWU1MDdiMzE0YzdiYmFlYjUzNTZjMmZiOTIiLCJjb21taXRfc2hhIjoiOWMyYmYxNGNmOWFiMzM0MWQ3MTVhZDE1MGFjNGVjNWViYzQ5MjlhOCIsImV4cCI6MTc4MjMwMTA1N30.-sxiXsgHF4UjljK7bznQ-Z86GE\_R2uvk8ZR6E9OVdAI"\>\</script\>\</head\>\<body\>\<\!--$--\>\<div class="min-h-screen w-full" style="background:var(--page)"\>\<div class="mx-auto w-full" style="max-width:420px"\>\<header class="px-6 pt-10 pb-16 text-white text-left" style="background:var(--grad-mix)"\>\<div class="min-w-0"\>\<div class="font-display font-extrabold text-white leading-tight" style="font-size:20px;letter-spacing:-0.01em"\>ЭДпауер \<span style="opacity:0.85"\>/ EDpower\</span\>\</div\>\<div class="text-white/80 font-semibold" style="font-size:11px;letter-spacing:0.14em;margin-top:2px"\>КЛУБ РОДИТЕЛЕЙ\</div\>\</div\>\<h1 class="mt-7 font-extrabold text-white" style="font-family:&\#x27;Fredoka&\#x27;, &\#x27;Onest&\#x27;, system-ui, sans-serif;font-size:30px;line-height:1.1;letter-spacing:-0.01em"\>Привет, я навигатор\! 👋\</h1\>\<p class="mt-3 text-white/90 text-\[14px\] font-semibold leading-snug break-words"\>Рад видеть вас в нашем уютном Клубе осознанных родителей\!\</p\>\<p class="mt-2 text-white/80 text-\[13px\] font-medium leading-snug break-words"\>Я помогу быстро перемещаться по интересующим разделам Клуба.\</p\>\</header\>\<main class="-mt-8 pb-28 px-6 pt-7 space-y-7" style="background:\#F7F5FA;border-top-left-radius:36px;border-top-right-radius:36px;box-shadow:0 \-20px 40px \-28px rgba(80,40,120,0.18);min-height:60vh"\>\<section class="space-y-3"\>\<div class="px-2" style="color:\#b3a8c9;font-size:11px;font-weight:700;letter-spacing:0.18em"\>НАЧАТЬ ЗДЕСЬ\</div\>\<div class="space-y-3"\>\<div class="bg-white px-3 py-3" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex items-center gap-2"\>\<div class="flex shrink-0 items-center justify-center" style="width:42px;height:42px;border-radius:12px;background:\#dff3fb;color:\#2f8fb8"\>\<svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-megaphone" aria-hidden="true"\>\<path d="M11 6a13 13 0 0 0 8.4-2.8A1 1 0 0 1 21 4v12a1 1 0 0 1-1.6.8A13 13 0 0 0 11 14H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2z"\>\</path\>\<path d="M6 14a12 12 0 0 0 2.4 7.2 2 2 0 0 0 3.2-2.4A8 8 0 0 1 10 14"\>\</path\>\<path d="M8 6v8"\>\</path\>\</svg\>\</div\>\<div class="min-w-0 flex-1 font-bold leading-snug whitespace-pre-line" style="color:var(--ink);font-size:14px"\>Канал Клуба\</div\>\<div class="flex shrink-0 items-center gap-1.5"\>\<a href="https://t.me/+dVkJGMNq38lkMmVi" target="\_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 transition-all active:scale-\[0.97\]" style="background:\#dff3fb;color:\#2f8fb8;border-radius:10px;padding:6px 8px;font-weight:700;font-size:11px;letter-spacing:0.01em"\>\<svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-send" aria-hidden="true"\>\<path d="M14.536 21.686a.5.5 0 0 0 .937-.024l6.5-19a.496.496 0 0 0-.635-.635l-19 6.5a.5.5 0 0 0-.024.937l7.93 3.18a2 2 0 0 1 1.112 1.11z"\>\</path\>\<path d="m21.854 2.147-10.94 10.939"\>\</path\>\</svg\>\<span\>Telegram\</span\>\</a\>\<a href="https://max.ru/id9704263517\_biz" target="\_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 transition-all active:scale-\[0.97\]" style="background:\#dff3fb;color:\#2f8fb8;border-radius:10px;padding:6px 8px;font-weight:700;font-size:11px;letter-spacing:0.01em"\>\<svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-message-circle" aria-hidden="true"\>\<path d="M2.992 16.342a2 2 0 0 1 .094 1.167l-1.065 3.29a1 1 0 0 0 1.236 1.168l3.413-.998a2 2 0 0 1 1.099.092 10 10 0 1 0-4.777-4.719"\>\</path\>\</svg\>\<span\>MAX\</span\>\</a\>\</div\>\</div\>\</div\>\<div class="bg-white px-3 py-3" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex items-center gap-2"\>\<div class="flex shrink-0 items-center justify-center" style="width:42px;height:42px;border-radius:12px;background:\#fde0f1;color:\#c2329b"\>\<svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-users" aria-hidden="true"\>\<path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2"\>\</path\>\<path d="M16 3.128a4 4 0 0 1 0 7.744"\>\</path\>\<path d="M22 21v-2a4 4 0 0 0-3-3.87"\>\</path\>\<circle cx="9" cy="7" r="4"\>\</circle\>\</svg\>\</div\>\<div class="min-w-0 flex-1 font-bold leading-snug whitespace-pre-line" style="color:var(--ink);font-size:14px"\>Задать вопрос  
куратору\</div\>\<div class="flex shrink-0 items-center gap-1.5"\>\<a href="https://t.me/+CtblMGJ-cbg1N2Fi" target="\_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 transition-all active:scale-\[0.97\]" style="background:\#fde0f1;color:\#c2329b;border-radius:10px;padding:6px 8px;font-weight:700;font-size:11px;letter-spacing:0.01em"\>\<svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-send" aria-hidden="true"\>\<path d="M14.536 21.686a.5.5 0 0 0 .937-.024l6.5-19a.496.496 0 0 0-.635-.635l-19 6.5a.5.5 0 0 0-.024.937l7.93 3.18a2 2 0 0 1 1.112 1.11z"\>\</path\>\<path d="m21.854 2.147-10.94 10.939"\>\</path\>\</svg\>\<span\>Telegram\</span\>\</a\>\<a href="https://max.ru/id9704263517\_biz/AZ6ID8UgBqo" target="\_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 transition-all active:scale-\[0.97\]" style="background:\#fde0f1;color:\#c2329b;border-radius:10px;padding:6px 8px;font-weight:700;font-size:11px;letter-spacing:0.01em"\>\<svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-message-circle" aria-hidden="true"\>\<path d="M2.992 16.342a2 2 0 0 1 .094 1.167l-1.065 3.29a1 1 0 0 0 1.236 1.168l3.413-.998a2 2 0 0 1 1.099.092 10 10 0 1 0-4.777-4.719"\>\</path\>\</svg\>\<span\>MAX\</span\>\</a\>\</div\>\</div\>\</div\>\<a href="https://edpower-rag.ff.pro/?embed=true\#b2500648" target="\_blank" rel="noopener noreferrer" class="group flex items-center gap-4 bg-white px-4 py-4 transition-all active:scale-\[0.98\]" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex shrink-0 items-center justify-center" style="width:48px;height:48px;border-radius:14px;background:\#ece1fb;color:\#7a3fd1"\>\<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bot" aria-hidden="true"\>\<path d="M12 8V4H8"\>\</path\>\<rect width="16" height="12" x="4" y="8" rx="2"\>\</rect\>\<path d="M2 14h2"\>\</path\>\<path d="M20 14h2"\>\</path\>\<path d="M15 13v2"\>\</path\>\<path d="M9 13v2"\>\</path\>\</svg\>\</div\>\<div class="min-w-0 flex-1"\>\<div class="font-bold leading-snug" style="color:var(--ink);font-size:14px"\>Задать вопрос ИИ 24/7\</div\>\</div\>\<div class="flex shrink-0 items-center justify-center transition-transform group-hover:translate-x-0.5" style="width:32px;height:32px;border-radius:999px;background:var(--page);color:var(--ink)"\>\<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right" aria-hidden="true"\>\<path d="M5 12h14"\>\</path\>\<path d="m12 5 7 7-7 7"\>\</path\>\</svg\>\</div\>\</a\>\</div\>\</section\>\<section class="space-y-3"\>\<div class="px-2" style="color:\#b3a8c9;font-size:11px;font-weight:700;letter-spacing:0.18em"\>МАТЕРИАЛЫ И ОБУЧЕНИЕ\</div\>\<div class="space-y-3"\>\<a href="https://school.polina-education.ru/broadcast\_as\_a\_gift" target="\_blank" rel="noopener noreferrer" class="group flex items-center gap-4 bg-white px-4 py-4 transition-all active:scale-\[0.98\]" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex shrink-0 items-center justify-center" style="width:48px;height:48px;border-radius:14px;background:\#fde0f1;color:\#c2329b"\>\<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-circle-play" aria-hidden="true"\>\<path d="M9 9.003a1 1 0 0 1 1.517-.859l4.997 2.997a1 1 0 0 1 0 1.718l-4.997 2.997A1 1 0 0 1 9 14.996z"\>\</path\>\<circle cx="12" cy="12" r="10"\>\</circle\>\</svg\>\</div\>\<div class="min-w-0 flex-1"\>\<div class="font-bold leading-snug" style="color:var(--ink);font-size:14px"\>Выбор эфира (1 раз в месяц)\</div\>\</div\>\<div class="flex shrink-0 items-center justify-center transition-transform group-hover:translate-x-0.5" style="width:32px;height:32px;border-radius:999px;background:var(--page);color:var(--ink)"\>\<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right" aria-hidden="true"\>\<path d="M5 12h14"\>\</path\>\<path d="m12 5 7 7-7 7"\>\</path\>\</svg\>\</div\>\</a\>\<a href="https://school.polina-education.ru/teach/control/stream/view/id/934573669" target="\_blank" rel="noopener noreferrer" class="group flex items-center gap-4 bg-white px-4 py-4 transition-all active:scale-\[0.98\]" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex shrink-0 items-center justify-center" style="width:48px;height:48px;border-radius:14px;background:\#ece1fb;color:\#7a3fd1"\>\<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-folder-open" aria-hidden="true"\>\<path d="m6 14 1.5-2.9A2 2 0 0 1 9.24 10H20a2 2 0 0 1 1.94 2.5l-1.54 6a2 2 0 0 1-1.95 1.5H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h3.9a2 2 0 0 1 1.69.9l.81 1.2a2 2 0 0 0 1.67.9H18a2 2 0 0 1 2 2v2"\>\</path\>\</svg\>\</div\>\<div class="min-w-0 flex-1"\>\<div class="font-bold leading-snug" style="color:var(--ink);font-size:14px"\>Материалы месяца в одном месте\</div\>\</div\>\<div class="flex shrink-0 items-center justify-center transition-transform group-hover:translate-x-0.5" style="width:32px;height:32px;border-radius:999px;background:var(--page);color:var(--ink)"\>\<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right" aria-hidden="true"\>\<path d="M5 12h14"\>\</path\>\<path d="m12 5 7 7-7 7"\>\</path\>\</svg\>\</div\>\</a\>\<a href="https://school.polina-education.ru/teach/control/stream/view/id/934575705" target="\_blank" rel="noopener noreferrer" class="group flex items-center gap-4 bg-white px-4 py-4 transition-all active:scale-\[0.98\]" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex shrink-0 items-center justify-center" style="width:48px;height:48px;border-radius:14px;background:\#dff3fb;color:\#2f8fb8"\>\<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-book-open" aria-hidden="true"\>\<path d="M12 7v14"\>\</path\>\<path d="M3 18a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h5a4 4 0 0 1 4 4 4 4 0 0 1 4-4h5a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1h-6a3 3 0 0 0-3 3 3 3 0 0 0-3-3z"\>\</path\>\</svg\>\</div\>\<div class="min-w-0 flex-1"\>\<div class="font-bold leading-snug" style="color:var(--ink);font-size:14px"\>База готовых решений\</div\>\</div\>\<div class="flex shrink-0 items-center justify-center transition-transform group-hover:translate-x-0.5" style="width:32px;height:32px;border-radius:999px;background:var(--page);color:var(--ink)"\>\<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right" aria-hidden="true"\>\<path d="M5 12h14"\>\</path\>\<path d="m12 5 7 7-7 7"\>\</path\>\</svg\>\</div\>\</a\>\</div\>\</section\>\<section class="space-y-3"\>\<div class="px-2" style="color:\#b3a8c9;font-size:11px;font-weight:700;letter-spacing:0.18em"\>БОНУСЫ И ВОЗМОЖНОСТИ\</div\>\<div class="space-y-3"\>\<div class="bg-white px-3 py-3" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex items-center gap-2"\>\<div class="flex shrink-0 items-center justify-center" style="width:42px;height:42px;border-radius:12px;background:\#ece1fb;color:\#7a3fd1"\>\<svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-messages-square" aria-hidden="true"\>\<path d="M16 10a2 2 0 0 1-2 2H6.828a2 2 0 0 0-1.414.586l-2.202 2.202A.71.71 0 0 1 2 14.286V4a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2z"\>\</path\>\<path d="M20 9a2 2 0 0 1 2 2v10.286a.71.71 0 0 1-1.212.502l-2.202-2.202A2 2 0 0 0 17.172 19H10a2 2 0 0 1-2-2v-1"\>\</path\>\</svg\>\</div\>\<div class="min-w-0 flex-1 font-bold leading-snug whitespace-pre-line" style="color:var(--ink);font-size:14px"\>Чат родителей\</div\>\<div class="flex shrink-0 items-center gap-1.5"\>\<a href="https://t.me/+CtblMGJ-cbg1N2Fi" target="\_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 transition-all active:scale-\[0.97\]" style="background:\#ece1fb;color:\#7a3fd1;border-radius:10px;padding:6px 8px;font-weight:700;font-size:11px;letter-spacing:0.01em"\>\<svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-send" aria-hidden="true"\>\<path d="M14.536 21.686a.5.5 0 0 0 .937-.024l6.5-19a.496.496 0 0 0-.635-.635l-19 6.5a.5.5 0 0 0-.024.937l7.93 3.18a2 2 0 0 1 1.112 1.11z"\>\</path\>\<path d="m21.854 2.147-10.94 10.939"\>\</path\>\</svg\>\<span\>Telegram\</span\>\</a\>\<a href="\#" target="\_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 transition-all active:scale-\[0.97\]" style="background:\#ece1fb;color:\#7a3fd1;border-radius:10px;padding:6px 8px;font-weight:700;font-size:11px;letter-spacing:0.01em"\>\<svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-message-circle" aria-hidden="true"\>\<path d="M2.992 16.342a2 2 0 0 1 .094 1.167l-1.065 3.29a1 1 0 0 0 1.236 1.168l3.413-.998a2 2 0 0 1 1.099.092 10 10 0 1 0-4.777-4.719"\>\</path\>\</svg\>\<span\>MAX\</span\>\</a\>\</div\>\</div\>\</div\>\<a href="https://school.polina-education.ru/teach/control/stream/view/id/586636948" target="\_blank" rel="noopener noreferrer" class="group flex items-center gap-4 bg-white px-4 py-4 transition-all active:scale-\[0.98\]" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex shrink-0 items-center justify-center" style="width:48px;height:48px;border-radius:14px;background:\#dff3fb;color:\#2f8fb8"\>\<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-gift" aria-hidden="true"\>\<path d="M12 7v14"\>\</path\>\<path d="M20 11v8a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-8"\>\</path\>\<path d="M7.5 7a1 1 0 0 1 0-5A4.8 8 0 0 1 12 7a4.8 8 0 0 1 4.5-5 1 1 0 0 1 0 5"\>\</path\>\<rect x="3" y="7" width="18" height="4" rx="1"\>\</rect\>\</svg\>\</div\>\<div class="min-w-0 flex-1"\>\<div class="font-bold leading-snug" style="color:var(--ink);font-size:14px"\>Скидки партнёров\</div\>\</div\>\<div class="flex shrink-0 items-center justify-center transition-transform group-hover:translate-x-0.5" style="width:32px;height:32px;border-radius:999px;background:var(--page);color:var(--ink)"\>\<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right" aria-hidden="true"\>\<path d="M5 12h14"\>\</path\>\<path d="m12 5 7 7-7 7"\>\</path\>\</svg\>\</div\>\</a\>\</div\>\</section\>\<section class="space-y-3"\>\<div class="px-2" style="color:\#b3a8c9;font-size:11px;font-weight:700;letter-spacing:0.18em"\>МОЙ КЛУБ\</div\>\<div class="space-y-3"\>\<a href="https://school.polina-education.ru/teach/control/stream/view/id/892096095" target="\_blank" rel="noopener noreferrer" class="group flex items-center gap-4 bg-white px-4 py-4 transition-all active:scale-\[0.98\]" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex shrink-0 items-center justify-center" style="width:48px;height:48px;border-radius:14px;background:\#fde0f1;color:\#c2329b"\>\<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-circle-user" aria-hidden="true"\>\<circle cx="12" cy="12" r="10"\>\</circle\>\<circle cx="12" cy="10" r="3"\>\</circle\>\<path d="M7 20.662V19a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v1.662"\>\</path\>\</svg\>\</div\>\<div class="min-w-0 flex-1"\>\<div class="font-bold leading-snug" style="color:var(--ink);font-size:14px"\>Мой тариф: посмотреть / сменить / продлить\</div\>\</div\>\<div class="flex shrink-0 items-center justify-center transition-transform group-hover:translate-x-0.5" style="width:32px;height:32px;border-radius:999px;background:var(--page);color:var(--ink)"\>\<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right" aria-hidden="true"\>\<path d="M5 12h14"\>\</path\>\<path d="m12 5 7 7-7 7"\>\</path\>\</svg\>\</div\>\</a\>\<a href="https://school.polina-education.ru/cms/system/contact" target="\_blank" rel="noopener noreferrer" class="group flex items-center gap-4 bg-white px-4 py-4 transition-all active:scale-\[0.98\]" style="border-radius:22px;box-shadow:0 6px 18px \-10px rgba(80,40,120,0.18), 0 2px 6px \-2px rgba(80,40,120,0.08)"\>\<div class="flex shrink-0 items-center justify-center" style="width:48px;height:48px;border-radius:14px;background:\#dff3fb;color:\#2f8fb8"\>\<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-life-buoy" aria-hidden="true"\>\<circle cx="12" cy="12" r="10"\>\</circle\>\<path d="m4.93 4.93 4.24 4.24"\>\</path\>\<path d="m14.83 9.17 4.24-4.24"\>\</path\>\<path d="m14.83 14.83 4.24 4.24"\>\</path\>\<path d="m9.17 14.83-4.24 4.24"\>\</path\>\<circle cx="12" cy="12" r="4"\>\</circle\>\</svg\>\</div\>\<div class="min-w-0 flex-1"\>\<div class="font-bold leading-snug" style="color:var(--ink);font-size:14px"\>Написать в техподдержку\</div\>\</div\>\<div class="flex shrink-0 items-center justify-center transition-transform group-hover:translate-x-0.5" style="width:32px;height:32px;border-radius:999px;background:var(--page);color:var(--ink)"\>\<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right" aria-hidden="true"\>\<path d="M5 12h14"\>\</path\>\<path d="m12 5 7 7-7 7"\>\</path\>\</svg\>\</div\>\</a\>\</div\>\</section\>\</main\>\</div\>\</div\>\<script\>(function(t){let s;try{s=JSON.parse(sessionStorage.getItem(t.storageKey)||"{}")}catch(e){console.error(e);return}const c=t.key||window.history.state?.\_\_TSR\_key,r=c?s\[c\]:void 0;if(t.shouldScrollRestoration&\&r&\&typeof r=="object"&\&Object.keys(r).length\>0){for(const e in r){const o=r\[e\];if(\!o||typeof o\!="object")continue;const l=o.scrollX,i=o.scrollY;if(\!(\!Number.isFinite(l)||\!Number.isFinite(i))){if(e==="window")window.scrollTo({top:i,left:l,behavior:t.behavior});else if(e){let n;try{n=document.querySelector(e)}catch{continue}n&&(n.scrollLeft=l,n.scrollTop=i)}}}return}const a=window.location.hash.split("\#",2)\[1\];if(a){const e=window.history.state?.\_\_hashScrollIntoViewOptions??\!0;if(e){const o=document.getElementById(a);o&\&o.scrollIntoView(e)}return}window.scrollTo({top:0,left:0,behavior:t.behavior})})({"storageKey":"tsr-scroll-restoration-v1\_3","shouldScrollRestoration":true});document.currentScript.remove()\</script\>\<\!--/$--\>\<script class="$tsr" id="$tsr-stream-barrier"\>(self.$R=self.$R||{})\["tsr"\]=\[\];self.$\_TSR={h(){this.hydrated=\!0,this.c()},e(){this.streamEnded=\!0,this.c()},c(){this.hydrated&\&this.streamEnded&&(delete self.$\_TSR,delete self.$R.tsr)},p(e){this.initialized?e():this.buffer.push(e)},buffer:\[\]};$\_TSR.router=($R=\>$R\[0\]={manifest:$R\[1\]={routes:$R\[2\]={\_\_root\_\_:$R\[3\]={preloads:$R\[4\]=\["/assets/index-CIwy3Q32.js"\],assets:$R\[5\]=\[$R\[6\]={tag:"script",attrs:$R\[7\]={type:"module",async:\!0},children:"import(\\"/assets/index-CIwy3Q32.js\\")"}\]},"/":$R\[8\]={preloads:$R\[9\]=\["/assets/index-DsFFsKIf.js"\]}}},matches:$R\[10\]=\[$R\[11\]={i:"\_\_root\_\_",u:1782297457610,s:"success",ssr:\!0},$R\[12\]={i:"",u:1782297457610,s:"success",ssr:\!0}\],lastMatchId:""})($R\["tsr"\]);$\_TSR.e();document.currentScript.remove()\</script\>\<script type="module" async=""\>import("/assets/index-CIwy3Q32.js")\</script\>  
\<aside  
	id="lovable-badge"  
	role="complementary"  
	dir="ltr"  
	lang="en"  
	aria-label="Edit with Lovable"\>  
	\<a  
		id="lovable-badge-cta"   
		target="\_blank"   
		href="https://lovable.dev/projects/ffe913d6-19a3-4cb9-9bd5-aa94bebf8576?utm\_source=lovable-badge"  
		rel="noopener nofollow"  
		aria-label="Edit with Lovable"\>  
		\<span id="lovable-badge-text"\>Edit with\</span\>  
		\<svg xmlns="http://www.w3.org/2000/svg" width="52" height="16" fill="none" viewBox="0 0 52 16"\>  
  \<path fill="\#FCFBF8" fill-rule="evenodd" d="M20.318 5.25c.643 0 1.206.14 1.69.418a2.81 2.81 0 0 1 1.118 1.191c.266.513.4 1.115.4 1.807s-.134 1.296-.4 1.812a2.81 2.81 0 0 1-1.118 1.193c-.484.278-1.047.418-1.69.418s-1.208-.14-1.695-.418a2.85 2.85 0 0 1-1.125-1.193c-.262-.516-.393-1.12-.393-1.812s.131-1.294.393-1.807a2.848 2.848 0 0 1 1.125-1.191c.487-.279 1.052-.418 1.695-.418Zm0 1.425c-.27 0-.504.076-.7.228-.193.147-.34.37-.443.67-.102.295-.153.66-.153 1.093 0 .435.05.801.153 1.1.102.3.25.524.443.676.196.147.43.22.7.22.27 0 .502-.073.694-.22.193-.152.341-.375.443-.67.103-.299.153-.667.153-1.106 0-.65-.112-1.145-.337-1.481a1.08 1.08 0 0 0-.953-.51ZM32.7 5.25c.61 0 1.127.1 1.549.3.422.197.74.48.953.849.217.368.325.809.325 1.32v2.704c0 .29.02.562.062.812.044.245.108.4.19.466V12h-1.935a5.895 5.895 0 0 1-.105-.684 7.745 7.745 0 0 1-.02-.228 2.293 2.293 0 0 1-.151.203c-.205.242-.47.437-.793.584-.32.143-.685.215-1.094.215-.406 0-.77-.08-1.094-.24a1.845 1.845 0 0 1-.756-.682 1.984 1.984 0 0 1-.27-1.045c0-.606.178-1.069.535-1.388.356-.324.87-.534 1.542-.633l1.125-.16c.225-.032.403-.074.534-.123a.622.622 0 0 0 .288-.196.549.549 0 0 0 .093-.327.65.65 0 0 0-.11-.367.702.702 0 0 0-.32-.27c-.14-.07-.31-.105-.51-.105-.32 0-.576.083-.768.251-.193.164-.298.39-.314.676h-1.923c.016-.434.147-.82.393-1.155.25-.34.596-.604 1.039-.792.442-.189.954-.283 1.535-.283Zm.99 3.498a.98.98 0 0 1-.215.14 2.49 2.49 0 0 1-.584.178l-.473.092c-.315.061-.553.156-.713.283-.155.127-.233.305-.233.534 0 .23.084.412.252.547.168.135.383.203.645.203s.494-.058.694-.173c.201-.118.355-.282.461-.49.11-.21.166-.448.166-.714v-.6Zm4.526-2.375c.065-.125.138-.243.221-.349.197-.25.437-.44.719-.571.282-.135.6-.203.952-.203.528 0 .988.138 1.377.412.389.275.688.67.896 1.186.21.512.314 1.12.314 1.824 0 .7-.107 1.309-.32 1.825-.213.512-.518.906-.915 1.18-.393.275-.854.412-1.383.412-.352 0-.667-.062-.946-.184a1.832 1.832 0 0 1-.7-.554 2.2 2.2 0 0 1-.234-.383V12h-1.843V3h1.862v3.373Zm1.284.296c-.274 0-.51.085-.707.253-.192.163-.338.397-.436.7a3.376 3.376 0 0 0-.148 1.05c0 .406.05.759.148 1.058.098.299.243.53.436.694.197.164.433.246.707.246.279 0 .512-.082.7-.246.193-.164.336-.395.43-.694.099-.3.148-.652.148-1.058 0-.405-.05-.757-.147-1.056-.095-.299-.238-.53-.43-.694a1.015 1.015 0 0 0-.7-.253Zm9.416-1.419c.602 0 1.136.131 1.604.393.466.262.829.643 1.086 1.143.263.5.394 1.097.394 1.794 0 .25-.002.449-.006.596H47.51c.018.288.071.538.164.75a1.3 1.3 0 0 0 .491.596c.214.13.465.196.757.196.319 0 .583-.082.792-.246.209-.167.34-.403.393-.706h1.862a2.48 2.48 0 0 1-.485 1.235 2.54 2.54 0 0 1-1.051.805c-.439.188-.949.283-1.53.283-.655 0-1.225-.125-1.708-.375a2.672 2.672 0 0 1-1.13-1.143c-.267-.508-.4-1.137-.4-1.887 0-.712.14-1.327.418-1.843a2.86 2.86 0 0 1 1.155-1.186c.491-.27 1.051-.405 1.678-.405Zm-.044 1.345c-.274 0-.516.068-.725.203a1.29 1.29 0 0 0-.479.59 2.045 2.045 0 0 0-.132.498h2.562a1.873 1.873 0 0 0-.138-.602 1.061 1.061 0 0 0-.418-.516 1.243 1.243 0 0 0-.67-.173Z" clip-rule="evenodd"/\>  
  \<path fill="\#FCFBF8" d="m26.605 9.995 1.342-4.566h1.924L27.628 12h-2.07l-2.33-6.57h1.98l1.397 4.565Zm-13.013.143h2.256c1.632 0 1.421 1.837 1.418 1.861h-5.603V3h1.93v7.138Zm31.516 1.861h-1.862V3h1.862v8.999Z"/\>  
  \<path fill="url(\#a)" fill-rule="evenodd" d="M2.7 3c1.492 0 2.7 1.192 2.7 2.663v1.012h.9c1.49 0 2.7 1.192 2.7 2.662S7.791 12 6.3 12H0V5.663C0 4.193 1.209 3 2.7 3Z" clip-rule="evenodd"/\>  
  \<defs\>  
    \<radialGradient id="a" cx="0" cy="0" r="1" gradientTransform="matrix(-1.54236 7.07838 \-10.231 \-2.15602 4.627 5.022)" gradientUnits="userSpaceOnUse"\>  
      \<stop offset=".106" stop-color="\#FE7B02"/\>  
      \<stop offset=".394" stop-color="\#FE3F21"/\>  
      \<stop offset=".608" stop-color="\#F858BC"/\>  
      \<stop offset=".929" stop-color="\#575ECF"/\>  
    \</radialGradient\>  
  \</defs\>  
\</svg\>

	\</a\>  
	  
	\<span id="lovable-badge-divider" aria-hidden="true"\>\</span\>  
	  
	\<button   
		id="lovable-badge-close"  
		aria-label="Dismiss"  
		title="Dismiss"  
		type="button"\>  
		\<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none" viewBox="0 0 16 16" aria-hidden="true"\>  
			\<path d="M10.646 4.646a.5.5 0 1 1 .707.708L8.707 8l2.646 2.646a.5.5 0 1 1-.707.707L8 8.707l-2.646 2.646a.5.5 0 1 1-.708-.707L7.293 8 4.646 5.354a.5.5 0 1 1 .708-.708L8 7.293l2.646-2.647Z"/\>  
		\</svg\>  
	\</button\>  
\</aside\>  
\<script\>  
	// Don't show the lovable-badge if the page is in an iframe or if it's being rendered by puppeteer (screenshot service)  
	if (window.self \!== window.top || navigator.userAgent.includes('puppeteer')) {  
		var badge \= document.getElementById('lovable-badge');  
		if (badge) {  
			badge.style.display \= 'none';  
		}  
	}

	// Add click event listener to close button with animation  
	var closeButton \= document.getElementById('lovable-badge-close');  
	if (closeButton) {  
		closeButton.addEventListener('click', function(event) {  
			event.preventDefault();  
			event.stopPropagation();  
			var badge \= document.getElementById('lovable-badge');  
			if (badge) {  
				badge.classList.add('closing');  
				setTimeout(function() {  
					if (badge) {  
						badge.style.display \= 'none';  
					}  
				}, 240);  
			}  
		});  
	}  
\</script\>  
\</body\>\</html\>