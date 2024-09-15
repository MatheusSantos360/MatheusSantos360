<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Github profile</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-default_background {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 237, 214, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-default_background {
	color: inherit;
	fill: inherit;
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 237, 214, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-transparentGray { background-color: rgba(227, 226, 224, 0); }
.select-value-color-translucentGray { background-color: rgba(0, 0, 0, 0.06); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(249, 228, 188, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="101a609f-c584-800d-95d9-e51fdfa49b20" class="page sans"><header><img class="page-cover-image" src="https://images.unsplash.com/photo-1489875347897-49f64b51c1f8?ixlib=rb-4.0.3&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><img class="icon" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSYnC0c7Mayqdusbi61p9V2WYcyX1Bur2ppChB_zi0APtkrKMwKH24msrXz&amp;s=10"/></div><h1 class="page-title">Github profile</h1><p class="page-description"></p></header><div class="page-body"><p id="101a609f-c584-8099-8ca9-da77af3a1d0d" class="">&lt;a href=&quot;https://github.com/MatheusSantos360&quot;&gt;&lt;img width=100% src=&quot;https://capsule-render.vercel.app/api?type=waving&amp;height=100&amp;color=gradient&amp;fontColor=260928&quot;/&gt;&lt;/a&gt;</p><p id="101a609f-c584-8009-b23e-e8a6e8a2eb52" class="">
</p><p id="714b5727-3ae0-4575-aa90-a8d9bb255928" class="">[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&amp;weight=500&amp;size=100&amp;pause=1000&amp;color=FFFFFF&amp;center=true&amp;width=600&amp;height=80&amp;lines=Matheus+dos+Santos+Paix%C3%A3o;Ou...;Primegame360x)](https://git.io/typing-svg)</p><p id="101a609f-c584-80d9-901d-cbe782edcb5b" class="">
</p><h1 id="101a609f-c584-80a5-95b3-fe9e94efad4b" class="">About me </h1><p id="101a609f-c584-80ec-9883-f981e9297e05" class="">Nice to meet you! My name is Matheus and I am passionate about technology, especially when it comes to &quot;Websites&quot;. Creation, whether Front-end or Back-end, gives me even more enthusiasm to continue learning about it! I am studying to continue in the area and use my knowledge in different ways and means to achieve a result: &quot;Solving problems&quot;. As Da Vinci said: &quot;Learning is the only thing the mind never tires of, never fears and never regrets.&quot; For each dream, a goal and a mission. </p><p id="945604d6-a976-42a5-b77f-f578071d52fe" class="">
</p><ul id="102a609f-c584-80cc-a081-d148f5bd7d23" class="bulleted-list"><li style="list-style-type:disc"><strong>I&#x27;m 15 years old;</strong></li></ul><ul id="102a609f-c584-800a-a371-ed52b737f9b5" class="bulleted-list"><li style="list-style-type:disc"><strong>I started programming when I was 14 years old;</strong></li></ul><ul id="ff36b298-75c1-4715-86bd-981bc2bbc237" class="bulleted-list"><li style="list-style-type:disc"><strong>I study a lot 😅.</strong></li></ul><p id="102a609f-c584-809b-8ffa-dd723de67861" class="">
</p><h1 id="101a609f-c584-8054-a00f-f43e78691cba" class="">Skills ⚡</h1><details open=""><summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0"><strong>🎨 Front</strong>-<strong>End</strong></summary><div class="indented"><p id="101a609f-c584-801c-9a39-fb245d7ccfc7" class="">&lt;img align=&quot;center&quot; alt=&quot;HTML&quot; src=&quot;https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-805f-abc4-d291574ad57d" class="">&lt;img align=&quot;center&quot; alt=&quot;CSS&quot; src=&quot;https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&amp;logo=css3&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-80f4-876e-ecfb42e06245" class="">&lt;img align=&quot;center&quot; alt=&quot;JavaScript&quot; src=&quot;https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black&quot; /&gt;</p><p id="102a609f-c584-80a2-b6e3-c89d99805c59" class="">&lt;img align=&quot;center&quot; alt=&quot;JQuery&quot; src=&quot;https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&amp;logo=jquery&amp;logoColor=white” /&gt;</p><p id="101a609f-c584-80bf-bf4e-e8c097f29014" class="">&lt;img align=&quot;center&quot; alt=&quot;React&quot; src=&quot;https://img.shields.io/badge/React-61DAFB?style=for-the-badge&amp;logo=react&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-8002-aab0-d22a507891ef" class="">&lt;img align=&quot;center&quot; alt=&quot;Tailwind CSS&quot; src=&quot;https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&amp;logo=tailwind-css&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-80fe-a0b3-d9fe752651e1" class="">&lt;img align=&quot;center&quot; alt=&quot;Daisy UI&quot; src=&quot;https://img.shields.io/badge/DaisyUI-5A67D8?style=for-the-badge&amp;logo=daisyui&amp;logoColor=white&quot; /&gt;</p></div></details><details open=""><summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0"><strong>⚙️ Back</strong>-<strong>end</strong></summary><div class="indented"><p id="99479f5b-6cc0-4b0f-ad41-22ff581f13f1" class="">&lt;img align=&quot;center&quot; alt=&quot;Node.js&quot; src=&quot;https://img.shields.io/badge/Node.js-339933?style=for-the-badge&amp;logo=nodedotjs&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-807f-9cde-fa3357c13683" class="">&lt;img align=&quot;center&quot; alt=&quot;PHP&quot; src=&quot;https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&amp;logo=php&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-8060-a834-cea217fc6593" class="">&lt;img align=&quot;center&quot; alt=&quot;Express.js&quot; src=&quot;https://img.shields.io/badge/Express.js-000000?style=for-the-badge&amp;logo=express&amp;logoColor=white&quot; /&gt;</p></div></details><details open=""><summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0"><strong>🗂 Bancos de dados</strong></summary><div class="indented"><p id="657eda45-9ca3-4aab-be1b-d4d14b967642" class="">&lt;img align=&quot;center&quot; alt=&quot;MongoDB&quot; src=&quot;https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&amp;logo=mongodb&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-80f5-a0cf-faa8a0ae12e9" class="">&lt;img align=&quot;center&quot; alt=&quot;MySQL&quot; src=&quot;https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&amp;logo=mysql&amp;logoColor=white&quot; /&gt;</p></div></details><details open=""><summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0"><strong>🛠 Tools</strong></summary><div class="indented"><p id="101a609f-c584-803d-8af9-c02b39ecba4e" class="">&lt;img align=&quot;center&quot; alt=&quot;Visual Studio Code&quot; src=&quot;https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&amp;logo=visual-studio-code&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-800f-8d03-f601045bab6d" class="">&lt;img align=&quot;center&quot; alt=&quot;Git&quot; src=&quot;https://img.shields.io/badge/Git-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-80d2-91c5-fda2bacce5d8" class="">&lt;img align=&quot;center&quot; alt=&quot;Github&quot; src=&quot;https://img.shields.io/badge/GitHub-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white&quot; /&gt;</p><p id="7e320ca5-978d-4247-9e10-99e4f176271f" class="">&lt;img align=&quot;center&quot; alt=&quot;Vite&quot; src=&quot;https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&amp;logo=vite&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-80f4-a0c5-d10cecdc37c4" class="">&lt;img align=&quot;center&quot; alt=&quot;Notion&quot; src=&quot;https://img.shields.io/badge/Notion-000000?style=for-the-badge&amp;logo=notion&amp;logoColor=white&quot; /&gt;</p></div></details><details open=""><summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0"><strong>⚡ DevOps</strong></summary><div class="indented"><ul id="101a609f-c584-80cc-acf0-cdeedd9bd856" class="toggle"><li><details open=""><summary><strong>Continuous Integration/Delivery &amp; IaC tools</strong></summary><p id="102a609f-c584-800e-9a36-c5ed3cc6250a" class="">&lt;img align=&quot;center&quot; alt=&quot;Github Actions&quot; src=&quot;https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&amp;logo=github-actions&amp;logoColor=white&quot; /&gt;</p></details></li></ul><ul id="101a609f-c584-8095-99be-ec5a31e68495" class="toggle"><li><details open=""><summary><strong>Containerization &amp; orquestration</strong></summary><p id="e374505d-7335-4d5c-9c22-1a7c0e360ab9" class="">Studing…</p></details></li></ul><ul id="6f4e06da-689f-4bfc-b031-180a80b1d7b7" class="toggle"><li><details open=""><summary><strong>Monitoring Tools</strong> </summary><p id="102a609f-c584-802f-b4ac-cfb0ffb7b25b" class="">Studing…</p></details></li></ul><ul id="101a609f-c584-80e6-af20-d93fc460c5bb" class="toggle"><li><details open=""><summary><strong>Test tools</strong></summary><p id="102a609f-c584-8054-beae-e0ecb88d8beb" class="">&lt;img align=&quot;center&quot; alt=&quot;Mocha&quot; src=&quot;https://img.shields.io/badge/Mocha-8D6748?style=for-the-badge&amp;logo=mocha&amp;logoColor=white&quot; /&gt;</p><p id="102a609f-c584-8015-88b6-e8663f9d84ae" class="">&lt;img align=&quot;center&quot; alt=&quot;Postman&quot; src=&quot;https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&amp;logo=postman&amp;logoColor=white&quot; /&gt;</p></details></li></ul></div></details><details open=""><summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">🔧 Others</summary><div class="indented"><p id="101a609f-c584-80dd-bf70-c55d216d535f" class="">&lt;img align=&quot;center&quot; alt=&quot;Python&quot; src=&quot;https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white&quot; /&gt;</p><p id="102a609f-c584-8080-a893-d771a556be91" class="">&lt;img align=&quot;center&quot; alt=&quot;C#&quot; src=&quot;https://img.shields.io/badge/C%23-239120?style=for-the-badge&amp;logo=c-sharp&amp;logoColor=white&quot; /&gt;</p></div></details><p id="102a609f-c584-801d-90b0-f5fb970f15f7" class="">
</p><h1 id="102a609f-c584-8076-a200-c18dbf0163ad" class="">Achievements 🏆</h1><ul id="102a609f-c584-8010-b0b4-c85d261373f7" class="bulleted-list"><li style="list-style-type:disc"><strong>I created a visual website for a city: Entrepreneur&#x27;s Room.</strong></li></ul><p id="102a609f-c584-8028-ae8a-e5e753654c9f" class="">
</p><h1 id="101a609f-c584-807c-9e5f-da3897a8aaad" class="">Goals 🎯</h1><ul id="102a609f-c584-80c5-b6c9-f50c3709e5db" class="bulleted-list"><li style="list-style-type:disc"><strong>Applying Test-Driven Development (TDD) practices to my projects</strong></li></ul><details open=""><summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">🎯 Technologies</summary><div class="indented"><p id="101a609f-c584-8041-855a-f79ae1ac2388" class="">&lt;img align=&quot;center&quot; alt=&quot;Jest&quot; src=&quot;https://img.shields.io/badge/Jest-C21325?style=for-the-badge&amp;logo=jest&amp;logoColor=white&quot; /&gt;</p><p id="102a609f-c584-80b8-bda3-d722d1dea259" class="">&lt;img align=&quot;center&quot; alt=&quot;Chai&quot; src=&quot;https://img.shields.io/badge/Chai-A30701?style=for-the-badge&amp;logo=chai&amp;logoColor=white&quot; /&gt;</p><p id="102a609f-c584-8032-9aea-d09250fa8fa7" class="">&lt;img align=&quot;center&quot; alt=&quot;Supertest&quot; src=&quot;https://img.shields.io/badge/SuperTest-000000?style=for-the-badge&amp;logo=supertest&amp;logoColor=white&quot; /&gt;</p><p id="102a609f-c584-80cb-b12b-c9a2bae33fe3" class="">&lt;img align=&quot;center&quot; alt=&quot;Cypress&quot; src=&quot;https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&amp;logo=cypress&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-800f-8dcf-ded6bbc290e8" class="">&lt;img align=&quot;center&quot; alt=&quot;Three.js&quot; src=&quot;https://img.shields.io/badge/Three.js-000000?style=for-the-badge&amp;logo=three.js&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-80a7-bf97-ccda07db61b1" class="">&lt;img align=&quot;center&quot; alt=&quot;Framer Motion&quot; src=&quot;https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&amp;logo=framer&amp;logoColor=white&quot; /&gt;</p></div></details><details open=""><summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">🎯 Tools</summary><div class="indented"><p id="101a609f-c584-8049-8602-ed6723cfe6e5" class="">&lt;img align=&quot;center&quot; alt=&quot;Jenkins&quot; src=&quot;https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&amp;logo=jenkins&amp;logoColor=white&quot; /&gt;</p><p id="51e69728-a4b6-4c62-bc3e-e786c3f0221b" class="">&lt;img align=&quot;center&quot; alt=&quot;ArgoCD&quot; src=&quot;https://img.shields.io/badge/ArgoCD-EB5424?style=for-the-badge&amp;logo=argo&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-8035-8651-e768d9321815" class="">&lt;img align=&quot;center&quot; alt=&quot;Terraform&quot; src=&quot;https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&amp;logo=terraform&amp;logoColor=white&quot; /&gt;</p><p id="102a609f-c584-804c-9b80-fd514f560ac6" class="">&lt;img align=&quot;center&quot; alt=&quot;JMeter&quot; src=&quot;https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&amp;logo=apache-jmeter&amp;logoColor=white&quot; /&gt;</p><p id="102a609f-c584-80ae-be5e-cfc1039818fe" class="">&lt;img align=&quot;center&quot; alt=&quot;Kubernetes&quot; src=&quot;https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&amp;logo=kubernetes&amp;logoColor=white&quot; /&gt;</p><p id="eb1c9f69-03b5-47d1-a729-da2ac8e9fedd" class="">&lt;img align=&quot;center&quot; alt=&quot;Docker&quot; src=&quot;https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&amp;logo=docker&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-80c5-a3ed-dd63e926086a" class="">&lt;img align=&quot;center&quot; alt=&quot;Prometheus&quot; src=&quot;https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&amp;logo=prometheus&amp;logoColor=white&quot; /&gt;</p><p id="101a609f-c584-8078-9430-cac9829df3ed" class="">&lt;img align=&quot;center&quot; alt=&quot;Grafana&quot; src=&quot;https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&amp;logo=grafana&amp;logoColor=white&quot; /&gt;</p></div></details><p id="102a609f-c584-80bf-8249-c15f07d5be92" class="">
</p><h1 id="101a609f-c584-8047-abce-c5eadb3f3339" class="">Currently studing/improving 🔍</h1><ul id="102a609f-c584-80f0-a58c-ea0371926a51" class="bulleted-list"><li style="list-style-type:disc"><strong>DevOps: Continuous Integration (CI), Continuous Delivery (CD) and IaC (Infrastructure as Code)</strong></li></ul><details open=""><summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0"><strong>⚙️ Technologies</strong></summary><div class="indented"><p id="101a609f-c584-80dd-99bc-cd44eca147ff" class="">&lt;img align=&quot;center&quot; alt=&quot;Redux&quot; src=&quot;https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&amp;logo=redux&amp;logoColor=white&quot; /&gt;</p><p id="102a609f-c584-8048-8769-e77a653adbdf" class="">&lt;img align=&quot;center&quot; alt=&quot;Tailwind CSS&quot; src=&quot;https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&amp;logo=tailwind-css&amp;logoColor=white&quot; /&gt;<br/>&lt;img align=&quot;center&quot; alt=&quot;Daisy UI&quot; src=&quot;https://img.shields.io/badge/DaisyUI-5A67D8?style=for-the-badge&amp;logo=daisyui&amp;logoColor=white&quot; /&gt;<br/></p></div></details><p id="102a609f-c584-8005-8ded-eba764241059" class="">
</p><h1 id="102a609f-c584-805c-9693-f036b481798c" class="">Languages 🌎</h1><ul id="102a609f-c584-807a-b6bc-efb87a937d83" class="bulleted-list"><li style="list-style-type:disc"><strong>🇧🇷 Portuguese;</strong></li></ul><ul id="102a609f-c584-80cc-9fbf-d0b441f11ba0" class="bulleted-list"><li style="list-style-type:disc"><strong>🇺🇸 English.</strong></li></ul><h1 id="101a609f-c584-8044-b064-e78a2177afce" class="">Contact</h1><p id="d9080c0a-958e-4714-9283-c0d09570354a" class="">&lt;img align=&quot;center&quot; alt=&quot;Gmail&quot; src=&quot;https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&amp;logo=gmail&amp;logoColor=white&quot; /&gt;</p><p id="cee71eca-13ca-40ca-821d-b69925aeb023" class="">&lt;img align=&quot;center&quot; alt=&quot;Github&quot; src=&quot;https://img.shields.io/badge/GitHub-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white&quot; /&gt;</p><p id="3f70a668-810e-49fb-b2e5-fce4f4c113de" class="">
</p><p id="101a609f-c584-808b-8aaa-e85ba0ef79a9" class="">&lt;img src=&quot;https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png&quot; min-width=&quot;400px&quot; max-width=&quot;400px&quot; width=&quot;400px&quot; align=&quot;right&quot;&gt;</p><p id="101a609f-c584-80ff-9072-d73bf50e22af" class="">
</p><p id="101a609f-c584-80fc-8e25-cb653fa9c098" class="">&lt;img width=100% src=&quot;https://capsule-render.vercel.app/api?type=waving&amp;height=100&amp;color=gradient&amp;fontColor=260928&amp;reversal=true&amp;section=footer&quot;/&gt;</p><p id="5b6f81dc-8ec6-4342-b3bc-373454800a7c" class="">
</p><p id="101a609f-c584-80e7-afeb-f32cc1c3e1d3" class="">
</p><p id="1d11712f-4afd-4e68-9d12-75711f789e06" class="">
</p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
